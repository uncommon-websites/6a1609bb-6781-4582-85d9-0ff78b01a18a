<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-serif text-4xl text-gray-900">Complete certification solution</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="AI-Powered Automation"
      title="Document generation at scale"
      description="Access 100+ regulatory document templates and leverage our AI co-pilot to generate compliant documentation in minutes, not months. From technical files to risk management reports, our platform automates the heavy lifting while maintaining audit-ready quality."
    >
      <!-- Visual for Block 1: Document Templates -->
      <div class="relative w-full h-full flex items-center justify-center">
        <!-- Central AI Hub -->
        <div class="w-16 h-16 bg-white shadow-lg rounded-lg flex items-center justify-center z-10 border border-gray-100">
           <svg class="w-8 h-8 text-primary-600" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
             <path d="M12 2L13.2 9.92154L20.6603 7L14.4 12L20.6603 17L13.2 14.0785L12 22L10.8 14.0785L3.33975 17L9.6 12L3.33975 7L10.8 9.92154L12 2Z" fill="currentColor"/>
           </svg>
        </div>
        
        <!-- Connected Documents -->
        <div class="absolute top-1/4 left-1/4 bg-white p-3 shadow rounded border border-gray-100 animate-pulse">
            <div class="w-8 h-10 bg-primary-100 rounded flex items-center justify-center text-[10px] font-bold text-primary-700">ISO</div>
            <div class="mt-1 text-[10px] text-center">13485</div>
        </div>
        <div class="absolute top-1/4 right-1/4 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-primary-600 rounded flex items-center justify-center text-[10px] font-bold text-white">MDR</div>
            <div class="mt-1 text-[10px] text-center">Tech File</div>
        </div>
        <div class="absolute bottom-1/4 left-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-primary-400 rounded flex items-center justify-center text-[10px] font-bold text-white">FDA</div>
            <div class="mt-1 text-[10px] text-center">510(k)</div>
        </div>
         <div class="absolute bottom-1/4 right-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-gray-200 rounded flex items-center justify-center text-[10px] font-bold text-gray-600">IEC</div>
            <div class="mt-1 text-[10px] text-center">62304</div>
        </div>
        
        <!-- Connecting Lines -->
        <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-20" viewBox="0 0 400 300">
            <path d="M100 100 L200 150 M300 100 L200 150 M150 220 L200 150 M250 220 L200 150" stroke="currentColor" stroke-width="1" stroke-dasharray="4 4" />
        </svg>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="Expert Regulatory Support"
      title="Dedicated compliance experts"
      description="Every client gets a dedicated regulatory expert with hands-on FDA and EU MDR experience. From initial consultation to post-market surveillance, your expert guides you through every step, eliminating costly consultant email chains and uncertainty."
      reversed={true}
    >
      <!-- Visual for Block 2: Expert Dashboard -->
      <div class="bg-white rounded-lg shadow-xl p-6 w-3/4 max-w-sm border border-gray-100">
        <div class="flex items-center space-x-3 mb-4">
            <div class="w-8 h-8 rounded-full bg-primary-600 flex items-center justify-center text-white text-xs font-bold">
                ST
            </div>
            <div class="text-xs text-gray-500">Spencer Todd • Regulatory Expert</div>
        </div>
        <h4 class="font-serif text-xl mb-4">CE Marking Progress</h4>
        <div class="space-y-2 mb-6">
            <div class="flex items-center justify-between text-xs mb-1">
                <span class="text-gray-600">Quality Management System</span>
                <span class="text-green-600 font-medium">Complete</span>
            </div>
            <div class="h-2 bg-gray-100 rounded w-full overflow-hidden">
                <div class="h-full bg-green-500 w-full"></div>
            </div>
            <div class="flex items-center justify-between text-xs mb-1 mt-3">
                <span class="text-gray-600">Technical Documentation</span>
                <span class="text-primary-600 font-medium">In Progress</span>
            </div>
            <div class="h-2 bg-gray-100 rounded w-full overflow-hidden">
                <div class="h-full bg-primary-600 w-4/6"></div>
            </div>
        </div>
        <button class="w-full bg-primary-600 text-white py-2 rounded text-sm font-medium flex items-center justify-center space-x-2 hover:bg-primary-700 transition-colors">
            <span>Schedule Expert Review</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </button>
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Electronic Quality Management"
      title="Continuous compliance monitoring"
      description="Our integrated eQMS keeps you compliant from certification through post-market. Automated change management, real-time regulatory alerts, complaint handling, and surveillance activities ensure you maintain certification without the administrative burden."
    >
       <!-- Visual for Block 3: Compliance Dashboard -->
       <div class="bg-white rounded shadow-lg p-8 w-2/3 max-w-xs border border-gray-100 relative">
          <div class="flex justify-between items-center mb-6 border-b pb-2">
              <div class="font-bold text-xs">FormlyAI eQMS</div>
              <div class="w-4 h-4 bg-green-500 rounded-full"></div>
          </div>
          <div class="mb-4">
              <h5 class="font-bold text-sm">Compliance Status</h5>
              <div class="text-[10px] text-gray-400">Real-time monitoring across all devices</div>
          </div>
          <div class="space-y-3 text-[9px] text-gray-600">
              <div class="flex items-center justify-between p-2 bg-green-50 rounded">
                  <span>MDR Compliance</span>
                  <span class="font-bold text-green-600">✓ Active</span>
              </div>
              <div class="flex items-center justify-between p-2 bg-blue-50 rounded">
                  <span>ISO 13485 Audit</span>
                  <span class="font-bold text-blue-600">Due 45d</span>
              </div>
              <div class="flex items-center justify-between p-2 bg-gray-50 rounded">
                  <span>Change Requests</span>
                  <span class="font-bold text-gray-600">3 Pending</span>
              </div>
          </div>
       </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
