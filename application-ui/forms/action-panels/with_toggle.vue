<template>
    <div class="" style="">
    <div class="bg-gray-100">
      <div class="max-w-7xl mx-auto py-12 sm:px-6 lg:px-8">
        <div class="max-w-3xl mx-auto">
        
    <div class="bg-white shadow sm:rounded-lg">
      <div class="px-4 py-5 sm:p-6">
        <h3 class="text-lg leading-6 font-medium text-gray-900" id="renew-subscription-label" @click="on = !on; $refs.switch.focus()">
          Renew subscription automatically
        </h3>
        <div class="mt-2 sm:flex sm:items-start sm:justify-between">
          <div class="max-w-xl text-sm text-gray-500">
            <p id="renew-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo totam non cumque deserunt officiis ex maiores nostrum.
            </p>
          </div>
          <div class="mt-5 sm:mt-0 sm:ml-6 sm:flex-shrink-0 sm:flex sm:items-center">
            <button type="button" class="bg-gray-200 relative inline-flex flex-shrink-0 h-6 w-11 border-2 border-transparent rounded-full cursor-pointer transition-colors ease-in-out duration-200 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500" aria-pressed="false" x-ref="switch" x-state:on="Enabled" x-state:off="Not Enabled" :class="{ 'bg-indigo-600': on, 'bg-gray-200': !(on) }" aria-labelledby="renew-subscription-label" :aria-pressed="on.toString()" @click="on = !on">
              <span class="sr-only">Use setting</span>
              <span aria-hidden="true" class="translate-x-0 inline-block h-5 w-5 rounded-full bg-white shadow transform ring-0 transition ease-in-out duration-200" x-state:on="Enabled" x-state:off="Not Enabled" :class="{ 'translate-x-5': on, 'translate-x-0': !(on) }"></span>
            </button>
          </div>
        </div>
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
	on: false,
  })
}
</script>
