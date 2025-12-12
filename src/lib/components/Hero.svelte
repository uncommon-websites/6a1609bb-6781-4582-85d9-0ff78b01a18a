<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-20 md:py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center">
    <h1 class="font-serif text-5xl md:text-7xl text-gray-900 mb-6 leading-tight">
      Medical device certification, <br/> made simple
    </h1>
    <p class="text-gray-500 text-lg md:text-xl max-w-2xl mx-auto mb-10 leading-relaxed font-light">
      Get your medical device certified faster with AI-guided compliance automation and expert regulatory support. From FDA 510(k) to EU CE marking, we handle the complexity so you can focus on innovation.
    </p>
    <a href="#" class="inline-flex items-center px-6 py-3 bg-[var(--color-primary-blue)] text-white font-medium rounded hover:opacity-90 transition-opacity">
      Start your certification <span class="ml-2">→</span>
    </a>
  </div>

  <div class="mt-16 md:mt-20 px-4 md:px-12">
    <div class="relative w-full aspect-[16/9] md:aspect-[21/9] rounded-lg overflow-hidden bg-gray-200">
      <!-- Hero image -->
      <img 
        src="/generated/image-medical-device-startup-founders-collabor-1765523073774-0.webp" 
        alt="Medical device founders working on certification" 
        class="w-full h-full object-cover"
      />
    </div>
  </div>
</SectionWrapper>
