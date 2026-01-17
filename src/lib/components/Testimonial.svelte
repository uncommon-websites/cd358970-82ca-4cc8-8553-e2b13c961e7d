<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 mb-16 text-center">
    <h2 class="font-serif text-4xl text-gray-900">Empower your revenue team</h2>
  </div>

  <div class="px-4 md:px-12 max-w-5xl mx-auto">
    <div class="flex flex-col md:flex-row gap-12 items-center">
      <!-- Image -->
      <div class="w-full md:w-1/3">
        <div class="aspect-[3/4] bg-gray-200 rounded-lg overflow-hidden relative shadow-lg">
          <img 
            src="/generated/image-a-portrait-of-a-confident-medical-practi-1768693612541-3.webp" 
            alt="Sarah Jenkins" 
            class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500"
          />
          <div class="absolute bottom-4 left-4 text-white text-[10px] font-bold uppercase tracking-widest opacity-80 bg-black/20 px-2 py-1 rounded">
            Summit Health
          </div>
        </div>
      </div>

      <!-- Quote -->
      <div class="w-full md:w-2/3">
        <blockquote class="font-light text-xl md:text-2xl text-gray-500 leading-relaxed mb-8">
          "The complexity of specialty billing was draining our resources. <span class="text-gray-900">Company simplified the mess between patient, practice, and payer</span>, allowing our staff to focus on patient care instead of chasing codes."
        </blockquote>
        
        <div class="border-t border-gray-200 border-dashed pt-6">
          <div class="font-serif text-lg font-bold text-gray-900">Sarah Jenkins</div>
          <div class="text-sm text-gray-500">Practice Manager</div>
          <div class="text-sm text-gray-500">Summit Health Group</div>
        </div>
      </div>
    </div>
  </div>
</SectionWrapper>
