<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 mb-16 text-center">
    <h2 class="font-serif text-4xl text-gray-900">Trusted by medtech founders</h2>
  </div>

  <div class="px-4 md:px-12 max-w-5xl mx-auto">
    <div class="flex flex-col md:flex-row gap-12 items-center">
      <!-- Image -->
      <div class="w-full md:w-1/3">
        <div class="aspect-[3/4] bg-gray-200 rounded-lg overflow-hidden relative">
          <img 
            src="/generated/image-confident-medtech-startup-ceo-in-profess-1765523077560-1.webp" 
            alt="Medtech Founder" 
            class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500"
          />
          <div class="absolute bottom-4 left-4 text-white text-xs font-bold uppercase tracking-widest opacity-80">
            Medtech
          </div>
        </div>
      </div>

      <!-- Quote -->
      <div class="w-full md:w-2/3">
        <blockquote class="font-light text-xl md:text-2xl text-gray-500 leading-relaxed mb-8">
          "No BS, no fluff. <span class="text-gray-900">FormlyAI helped us get CE marked in a fraction of the time we expected</span>, and their hands-on support made the whole process surprisingly pleasant. Best decision we made for our startup."
        </blockquote>
        
        <div class="border-t border-gray-200 border-dashed pt-6">
          <div class="font-serif text-lg font-bold text-gray-900">Medtech Founder</div>
          <div class="text-sm text-gray-500">CEO</div>
          <div class="text-sm text-gray-500">Medical Device Startup</div>
        </div>
      </div>
    </div>
  </div>
</SectionWrapper>
