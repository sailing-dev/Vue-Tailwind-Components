<template>
    <div class="" style="">
    <div class="bg-white">
      <div class="px-4 py-12 max-w-7xl mx-auto sm:px-6 lg:px-8">
      
    <div class="pb-5 border-b border-gray-200 sm:pb-0">
      <h3 class="text-lg leading-6 font-medium text-gray-900">
        Candidates
      </h3>
      <div class="mt-3 sm:mt-4">
        <div class="sm:hidden" x-description="Dropdown menu on small screens">
          <label for="current-tab" class="sr-only">Select a tab</label>
          <select id="current-tab" name="current-tab" class="block w-full pl-3 pr-10 py-2 text-base border-gray-300 focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm rounded-md">
          
              <option>Applied</option>
          
              <option>Phone Screening</option>
          
              <option selected="">Interview</option>
          
              <option>Offer</option>
          
              <option>Hired</option>
          
          </select>
        </div>
        <div class="hidden sm:block" x-description="Tabs at small breakpoint and up">
          <nav class="-mb-px flex space-x-8">
          
              <a href="#" class="border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300 whitespace-nowrap pb-4 px-1 border-b-2 font-medium text-sm" x-state:on="Current" x-state:off="Default" x-state-description="Current: &quot;border-indigo-500 text-indigo-600&quot;, Default: &quot;border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300&quot;">
                Applied
              </a>
          
              <a href="#" class="border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300 whitespace-nowrap pb-4 px-1 border-b-2 font-medium text-sm" x-state-description="undefined: &quot;border-indigo-500 text-indigo-600&quot;, undefined: &quot;border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300&quot;">
                Phone Screening
              </a>
          
              <a href="#" class="border-indigo-500 text-indigo-600 whitespace-nowrap pb-4 px-1 border-b-2 font-medium text-sm" aria-current="page" x-state-description="undefined: &quot;border-indigo-500 text-indigo-600&quot;, undefined: &quot;border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300&quot;">
                Interview
              </a>
          
              <a href="#" class="border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300 whitespace-nowrap pb-4 px-1 border-b-2 font-medium text-sm" x-state-description="undefined: &quot;border-indigo-500 text-indigo-600&quot;, undefined: &quot;border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300&quot;">
                Offer
              </a>
          
              <a href="#" class="border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300 whitespace-nowrap pb-4 px-1 border-b-2 font-medium text-sm" x-state-description="undefined: &quot;border-indigo-500 text-indigo-600&quot;, undefined: &quot;border-transparent text-gray-500 hover:text-gray-700 hover:border-gray-300&quot;">
                Hired
              </a>
          
          </nav>
        </div>
      </div>
    </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
	
  })
}
</script>
