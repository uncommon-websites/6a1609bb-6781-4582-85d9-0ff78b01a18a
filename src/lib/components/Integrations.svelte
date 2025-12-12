<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center mb-16">
    <div class="text-xs font-mono uppercase tracking-widest text-gray-500 mb-4">
      Regulatory Coverage
    </div>
    <h2 class="font-serif text-4xl text-gray-900 mb-6">
      All major regulatory pathways
    </h2>
    <p class="text-gray-500 leading-relaxed max-w-2xl mx-auto">
      From FDA 510(k) to EU MDR and IVDR, we support all device types and classes across US, European, and international markets with comprehensive standards compliance.
    </p>
  </div>

  <div class="px-4 md:px-12 relative">
    <!-- Connecting Line -->
    <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -translate-y-1/2 hidden md:block"></div>

    <!-- Standards Row -->
    <div class="flex flex-wrap md:flex-nowrap items-center justify-center md:justify-between gap-8 relative z-10">
      
      <!-- FDA -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-700">FDA</div>
      </div>

       <!-- ISO 13485 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[9px] font-bold text-gray-700 text-center leading-tight">ISO<br/>13485</div>
      </div>

       <!-- Center Logo (FormlyAI) -->
      <div class="w-24 h-24 bg-gray-900 rounded-full shadow-lg border-4 border-white flex items-center justify-center p-2 relative">
        <svg class="w-10 h-10 text-white" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M12 2L13.2 9.92154L20.6603 7L14.4 12L20.6603 17L13.2 14.0785L12 22L10.8 14.0785L3.33975 17L9.6 12L3.33975 7L10.8 9.92154L12 2Z" fill="currentColor"/>
        </svg>
        <!-- Orbit ring visual -->
        <div class="absolute inset-0 rounded-full border border-gray-700 scale-110 opacity-50"></div>
      </div>

       <!-- MDR -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-700">MDR</div>
      </div>

       <!-- IVDR -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-700">IVDR</div>
      </div>

    </div>
  </div>
</SectionWrapper>
