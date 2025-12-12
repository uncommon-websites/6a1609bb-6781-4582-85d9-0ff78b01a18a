<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-12">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-8">
    <!-- Logos -->
    <div class="flex flex-wrap items-center gap-8 md:gap-12 grayscale opacity-70">
        <!-- Lipocheck -->
        <div class="h-6 font-bold text-lg tracking-tight">Lipocheck</div>
        <!-- Myoact -->
        <div class="h-6 font-medium text-lg uppercase tracking-wider">Myoact</div>
        <!-- Coobi -->
        <div class="h-6 font-bold text-lg lowercase font-serif">coobi</div>
        <!-- Ovul -->
        <div class="h-6 font-medium text-lg tracking-wide">Ovul</div>
        <!-- Hoopsy -->
        <div class="h-6 font-bold text-lg">Hoopsy</div>
    </div>

    <!-- Trust Text -->
    <div class="text-gray-400 text-sm font-light text-right md:text-left">
      Trusted by innovative medtech startups
    </div>
  </div>
</SectionWrapper>
