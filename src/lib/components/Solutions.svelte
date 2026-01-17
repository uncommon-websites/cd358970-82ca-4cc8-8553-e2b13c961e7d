<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-serif text-4xl text-gray-900">Our solutions</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="Eligibility & Intake"
      title="Check eligibility, automatically"
      description="Real-time insurance validation at the front desk. Our platform instantly verifies coverage, co-pays, and deductibles before the patient even sees the doctor, reducing front-end denials."
    >
      <!-- Visual for Block 1: Verification -->
      <div class="relative w-full h-full flex items-center justify-center">
        <div class="w-64 bg-white shadow-xl rounded-xl border border-gray-100 p-6">
          <div class="flex items-center justify-between mb-6">
            <div class="h-4 w-24 bg-gray-100 rounded"></div>
            <div class="px-2 py-1 bg-green-100 text-green-700 text-[10px] font-bold rounded">VERIFIED</div>
          </div>
          <div class="space-y-4">
            <div class="flex justify-between items-center">
              <div class="h-3 w-32 bg-gray-50 rounded"></div>
              <div class="h-3 w-12 bg-gray-100 rounded"></div>
            </div>
            <div class="flex justify-between items-center border-t pt-4">
              <div class="text-xs font-bold">Co-pay Due</div>
              <div class="text-xs font-bold text-blue-600">$45.00</div>
            </div>
          </div>
        </div>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="Claims Automation"
      title="Send cleaner claims"
      description="Built-in coding and rules engine checks for errors before submission. We identify missing modifiers, mismatched codes, and payer-specific requirements to ensure your claims are 'clean' the first time."
      reversed={true}
    >
      <!-- Visual for Block 2: Image -->
      <div class="w-full h-full rounded-lg overflow-hidden shadow-xl border border-gray-100">
        <img 
          src="/generated/image-a-close-up-of-a-medical-professionals-ha-1768693608159-1.webp" 
          alt="Medical professional using tablet" 
          class="w-full h-full object-cover"
        />
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Integrated Collections"
      title="Collect faster, work less"
      description="Payer-integrated workflows handle follow-ups, appeals, and patient balances so your team doesn't have to. We bridge the gap between your EHR and the payer's bank account."
    >
       <!-- Visual for Block 3: Team collaboration -->
       <div class="w-full h-full rounded-lg overflow-hidden shadow-xl border border-gray-100">
        <img 
          src="/generated/image-a-diverse-team-of-healthcare-administrat-1768693610155-2.webp" 
          alt="Healthcare administrators collaborating" 
          class="w-full h-full object-cover"
        />
      </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
