<template>
    <div class="" style="">
    <div class="px-4 sm:px-6 lg:px-8 py-6 bg-white">
      <div class="max-w-7xl mx-auto">
      
    <div>
      <div class="sm:hidden">
        <label for="tabs" class="sr-only">Select a tab</label>
        <select id="tabs" name="tabs" class="block w-full focus:ring-indigo-500 focus:border-indigo-500 border-gray-300 rounded-md">
        
            <option>My Account</option>
        
            <option>Company</option>
        
            <option selected="">Team Members</option>
        
            <option>Billing</option>
        
        </select>
      </div>
      <div class="hidden sm:block">
        <nav class="flex space-x-4" aria-label="Tabs">
        
            <a href="#" class="text-gray-500 hover:text-gray-700 px-3 py-2 font-medium text-sm rounded-md" x-state:on="Current" x-state:off="Default" x-state-description="Current: &quot;bg-gray-100 text-gray-700&quot;, Default: &quot;text-gray-500 hover:text-gray-700&quot;">
              My Account
            </a>
        
            <a href="#" class="text-gray-500 hover:text-gray-700 px-3 py-2 font-medium text-sm rounded-md" x-state-description="undefined: &quot;bg-gray-100 text-gray-700&quot;, undefined: &quot;text-gray-500 hover:text-gray-700&quot;">
              Company
            </a>
        
            <a href="#" class="bg-gray-100 text-gray-700 px-3 py-2 font-medium text-sm rounded-md" aria-current="page" x-state-description="undefined: &quot;bg-gray-100 text-gray-700&quot;, undefined: &quot;text-gray-500 hover:text-gray-700&quot;">
              Team Members
            </a>
        
            <a href="#" class="text-gray-500 hover:text-gray-700 px-3 py-2 font-medium text-sm rounded-md" x-state-description="undefined: &quot;bg-gray-100 text-gray-700&quot;, undefined: &quot;text-gray-500 hover:text-gray-700&quot;">
              Billing
            </a>
        
        </nav>
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
