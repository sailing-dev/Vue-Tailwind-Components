<template>
    <div class="" style="">
    <div class="bg-white" style="min-height: 648px;">
      <div class="flex items-center justify-center p-8">
      
    <div class="relative" x-data="Components.popover({ open: true, focus: false })" x-init="init()" @keydown.escape="onEscape" @close-popover-group.window="onClosePopoverGroup">
      <button type="button" x-state:on="Item active" x-state:off="Item inactive" class="text-gray-500 group bg-white rounded-md inline-flex items-center text-base font-medium hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500" :class="{ 'text-gray-900': open, 'text-gray-500': !(open) }" @click="toggle" @mousedown="if (open) $event.preventDefault()" aria-expanded="false" :aria-expanded="open.toString()">
        <span>Solutions</span>
        <svg x-state:on="Item active" x-state:off="Item inactive" class="text-gray-400 ml-2 h-5 w-5 group-hover:text-gray-500" :class="{ 'text-gray-600': open, 'text-gray-400': !(open) }" x-description="Heroicon name: solid/chevron-down" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
    <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path>
  </svg>
      </button>

    
        <transition enter-active-class="transition ease-out duration-200" enter-class="opacity-0 translate-y-1" enter-to-class="opacity-100 translate-y-0" leave-active-class="transition ease-in duration-150" leave-class="opacity-100 translate-y-0" leave-to-class="opacity-0 translate-y-1"><div v-if="open" x-description="Flyout menu, show/hide based on flyout menu state." class="absolute z-10 left-1/2 transform -translate-x-1/2 mt-3 px-2 w-screen max-w-xs sm:px-0" x-ref="panel" @click.away="open = false">
          <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 overflow-hidden">
            <div class="relative grid gap-6 bg-white px-5 py-6 sm:gap-8 sm:p-8">
            
                <a href="#" class="-m-3 p-3 block rounded-md hover:bg-gray-50 transition ease-in-out duration-150">
                  <p class="text-base font-medium text-gray-900">
                    Blog
                  </p>
                  <p class="mt-1 text-sm text-gray-500">
                    Learn about tips, product updates and company culture.
                  </p>
                </a>
            
                <a href="#" class="-m-3 p-3 block rounded-md hover:bg-gray-50 transition ease-in-out duration-150">
                  <p class="text-base font-medium text-gray-900">
                    Help Center
                  </p>
                  <p class="mt-1 text-sm text-gray-500">
                    Get all of your questions answered in our forums of contact support.
                  </p>
                </a>
            
                <a href="#" class="-m-3 p-3 block rounded-md hover:bg-gray-50 transition ease-in-out duration-150">
                  <p class="text-base font-medium text-gray-900">
                    Guides
                  </p>
                  <p class="mt-1 text-sm text-gray-500">
                    Learn how to maximize our platform to get the most out of it.
                  </p>
                </a>
            
                <a href="#" class="-m-3 p-3 block rounded-md hover:bg-gray-50 transition ease-in-out duration-150">
                  <p class="text-base font-medium text-gray-900">
                    Events
                  </p>
                  <p class="mt-1 text-sm text-gray-500">
                    Check out webinars with experts and learn about our annual conference.
                  </p>
                </a>
            
                <a href="#" class="-m-3 p-3 block rounded-md hover:bg-gray-50 transition ease-in-out duration-150">
                  <p class="text-base font-medium text-gray-900">
                    Security
                  </p>
                  <p class="mt-1 text-sm text-gray-500">
                    Understand how we take your privacy seriously.
                  </p>
                </a>
            
            </div>
          </div>
        </div></transition>
    
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
