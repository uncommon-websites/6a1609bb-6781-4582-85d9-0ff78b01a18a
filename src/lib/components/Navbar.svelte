<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} withBorderTop={true} className="py-6">
  <nav class="flex items-center justify-between px-4 md:px-12">
    <!-- Logo -->
    <div class="flex items-center gap-2">
      <svg class="w-6 h-6 text-gray-900" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M12 2L13.2 9.92154L20.6603 7L14.4 12L20.6603 17L13.2 14.0785L12 22L10.8 14.0785L3.33975 17L9.6 12L3.33975 7L10.8 9.92154L12 2Z"
          fill="currentColor"
        />
      </svg>
      <span class="font-serif text-2xl font-medium tracking-wide">FormlyAI</span>
    </div>

    <!-- Links -->
    <div class="hidden md:flex items-center space-x-8 text-sm text-gray-600 font-medium">
      <a href="#" class="hover:text-gray-900">Platform</a>
      <a href="#" class="hover:text-gray-900">Customers</a>
      <a href="#" class="hover:text-gray-900">Pricing</a>
      <a href="#" class="hover:text-gray-900">Resources</a>
    </div>

    <!-- Action -->
    <div>
      <a href="#" class="inline-block px-6 py-2 bg-gray-100 hover:bg-gray-200 text-gray-900 text-sm font-medium rounded transition-colors">
        Get Started
      </a>
    </div>
  </nav>
</SectionWrapper>
