<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 flex flex-col md:flex-row">
    <!-- Stat 1 -->
    <div class="w-full md:w-1/2 md:pr-12 md:border-r border-gray-200 border-dashed mb-12 md:mb-0">
      <div class="font-serif text-5xl md:text-6xl text-gray-900 mb-4">
        15%
      </div>
      <p class="text-gray-500 text-sm max-w-xs">
        Average increase in net collection rate for practices using our automated eligibility and coding validation
      </p>
    </div>

    <!-- Stat 2 -->
    <div class="w-full md:w-1/2 md:pl-12">
      <div class="font-serif text-5xl md:text-6xl text-gray-900 mb-4">
        22 Days
      </div>
      <p class="text-gray-500 text-sm max-w-xs">
        Reduction in average Days Sales Outstanding (DSO) through payer-integrated collection workflows
      </p>
    </div>
  </div>
</SectionWrapper>
