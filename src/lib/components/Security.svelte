<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-12">
    <!-- Text -->
    <div class="w-full md:w-1/2">
      <h2 class="font-serif text-3xl md:text-4xl text-gray-900 mb-6">
        HIPAA compliant and secure by design
      </h2>
      <p class="text-gray-500 mb-2">Privacy. Security. Compliance.</p>
      <p class="text-gray-500 mb-2">PHI is always encrypted and protected.</p>
      <p class="text-gray-500 mb-8">Bank-level security for healthcare payments.</p>
      
      <a href="#" class="text-[var(--color-primary-600)] font-medium hover:underline text-sm">
        View our security whitepaper
      </a>
    </div>

    <!-- Badges -->
    <div class="w-full md:w-1/2 flex justify-center md:justify-end gap-6">
      <!-- Badge 1 -->
      <div class="w-24 h-24 rounded-full bg-gray-100 flex flex-col items-center justify-center text-center p-2">
        <div class="text-[10px] font-bold text-gray-900 mb-1">HIPAA</div>
        <div class="text-[10px] text-gray-500">COMPLIANT</div>
      </div>

      <!-- Badge 2 -->
      <div class="w-24 h-24 rounded-full bg-gray-100 flex flex-col items-center justify-center text-center p-2 relative border border-dashed border-gray-300">
        <div class="absolute inset-0 rounded-full border border-dashed border-gray-400 animate-spin-slow"></div>
        <div class="text-[10px] font-bold text-gray-900">SOC 2</div>
        <div class="text-[10px] text-gray-500">TYPE II</div>
      </div>

      <!-- Badge 3 -->
      <div class="w-24 h-24 rounded-full bg-gray-100 flex flex-col items-center justify-center text-center p-2">
        <div class="mb-1">
             <svg class="w-4 h-4 text-gray-900 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path></svg>
        </div>
        <div class="text-[10px] font-bold text-gray-900">PCI-DSS</div>
        <div class="text-[10px] text-gray-500">LEVEL 1</div>
      </div>
    </div>
  </div>
</SectionWrapper>
