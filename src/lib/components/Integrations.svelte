<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center mb-16">
    <div class="text-xs font-mono uppercase tracking-widest text-gray-500 mb-4">
      Integrations
    </div>
    <h2 class="font-serif text-4xl text-gray-900 mb-6">
      Fits into your existing systems
    </h2>
    <p class="text-gray-500 leading-relaxed max-w-2xl mx-auto">
      Our cloud platform connects through secure APIs with your EHR, billing software, and practice management system. No rip-and-replace needed.
    </p>
  </div>

  <div class="px-4 md:px-12 relative">
    <!-- Connecting Line -->
    <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -translate-y-1/2 hidden md:block"></div>

    <!-- Logos Row -->
    <div class="flex flex-wrap md:flex-nowrap items-center justify-center md:justify-between gap-8 relative z-10">
      
      <!-- Logo 1 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-400">Epic</div>
      </div>

       <!-- Logo 2 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-blue-500">Athena</div>
      </div>

       <!-- Center Logo (Company) -->
      <div class="w-24 h-24 bg-[var(--color-primary-900)] rounded-full shadow-lg border-4 border-white flex items-center justify-center p-2 relative">
        <div class="text-white font-serif font-bold text-[10px] tracking-widest">COMPANY</div>
        <!-- Orbit ring visual -->
        <div class="absolute inset-0 rounded-full border border-primary-700 scale-110 opacity-50"></div>
      </div>

       <!-- Logo 3 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-green-600">Cerner</div>
      </div>

       <!-- Logo 4 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-blue-400">eCW</div>
      </div>

    </div>
  </div>
</SectionWrapper>
