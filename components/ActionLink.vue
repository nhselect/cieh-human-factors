<template>
  <div class="nhsuk-action-link">
    <a class="nhsuk-action-link__link" :href="action_url">
      <svg class="nhsuk-icon nhsuk-icon__arrow-right-circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" aria-hidden="true" width="36" height="36">
        <path d="M0 0h24v24H0z" fill="none"></path>
        <path d="M12 2a10 10 0 0 0-9.95 9h11.64L9.74 7.05a1 1 0 0 1 1.41-1.41l5.66 5.65a1 1 0 0 1 0 1.42l-5.66 5.65a1 1 0 0 1-1.41 0 1 1 0 0 1 0-1.41L13.69 13H2.05A10 10 0 1 0 12 2z"></path>
      </svg>
      <span class="nhsuk-action-link__text">Read more</span>
    </a>
</div>
</template>

<script lang="ts">
import { Vue, Component, Prop } from 'nuxt-property-decorator'

@Component
export default class BackLink extends Vue {
  @Prop({ required:false, default: '/' }) readonly action_url!: string
}
</script>

<style lang="scss">
@import 'node_modules/nhsuk-frontend/packages/components/action-link/action-link';

.nhsuk-action-link {
  margin-top: 10px;
  margin-bottom: 10px;
  padding-right: 15px;
  text-align: right;
}
</style>
\