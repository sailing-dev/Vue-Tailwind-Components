<template>
    <div class="" style="">
    <div class="bg-gray-100 py-12 px-4 flex justify-center sm:px-6 lg:py-16 lg:px-8">
      <div class="w-full max-w-3xl mx-auto">
      
    <fieldset x-data="window.Components.radioGroup({ initialCheckedIndex: 0 })" x-init="init()">
      <legend class="sr-only">
        Privacy setting
      </legend>
      <div class="bg-white rounded-md -space-y-px">
      
          <label x-radio-group-option="" class="border-gray-200 rounded-tl-md rounded-tr-md  relative border p-4 flex cursor-pointer " x-state:on="Checked" x-state:off="Not Checked" :class="{ 'bg-indigo-50 border-indigo-200 z-10': value === 'Public access', 'border-gray-200': !(value === 'Public access') }">
            <input type="radio" x-model="value" name="privacy_setting" value="Public access" class="h-4 w-4 mt-0.5 cursor-pointer text-indigo-600 border-gray-300 focus:ring-indigo-500" aria-labelledby="privacy-setting-0-label" aria-describedby="privacy-setting-0-description">
            <div class="ml-3 flex flex-col">
              <span id="privacy-setting-0-label" class="text-gray-900 block text-sm font-medium" x-state:on="Checked" x-state:off="Not Checked" :class="{ 'text-indigo-900': value === 'Public access', 'text-gray-900': !(value === 'Public access') }">
                Public access
              </span>
              <span id="privacy-setting-0-description" class="text-gray-500 block text-sm" x-state:on="Checked" x-state:off="Not Checked" :class="{ 'text-indigo-700': value === 'Public access', 'text-gray-500': !(value === 'Public access') }">
                This project would be available to anyone who has the link
              </span>
            </div>
          </label>
      
          <label x-radio-group-option="" class="border-gray-200   relative border p-4 flex cursor-pointer " x-state:on="Checked" x-state:off="Not Checked" :class="{ 'bg-indigo-50 border-indigo-200 z-10': value === 'Private to Project Members', 'border-gray-200': !(value === 'Private to Project Members') }">
            <input type="radio" x-model="value" name="privacy_setting" value="Private to Project Members" class="h-4 w-4 mt-0.5 cursor-pointer text-indigo-600 border-gray-300 focus:ring-indigo-500" aria-labelledby="privacy-setting-1-label" aria-describedby="privacy-setting-1-description">
            <div class="ml-3 flex flex-col">
              <span id="privacy-setting-1-label" class="text-gray-900 block text-sm font-medium" x-state:on="Checked" x-state:off="Not Checked" :class="{ 'text-indigo-900': value === 'Private to Project Members', 'text-gray-900': !(value === 'Private to Project Members') }">
                Private to Project Members
              </span>
              <span id="privacy-setting-1-description" class="text-gray-500 block text-sm" x-state:on="Checked" x-state:off="Not Checked" :class="{ 'text-indigo-700': value === 'Private to Project Members', 'text-gray-500': !(value === 'Private to Project Members') }">
                Only members of this project would be able to access
              </span>
            </div>
          </label>
      
          <label x-radio-group-option="" class="border-gray-200  rounded-bl-md rounded-br-md relative border p-4 flex cursor-pointer " x-state:on="Checked" x-state:off="Not Checked" :class="{ 'bg-indigo-50 border-indigo-200 z-10': value === 'Private to you', 'border-gray-200': !(value === 'Private to you') }">
            <input type="radio" x-model="value" name="privacy_setting" value="Private to you" class="h-4 w-4 mt-0.5 cursor-pointer text-indigo-600 border-gray-300 focus:ring-indigo-500" aria-labelledby="privacy-setting-2-label" aria-describedby="privacy-setting-2-description">
            <div class="ml-3 flex flex-col">
              <span id="privacy-setting-2-label" class="text-gray-900 block text-sm font-medium" x-state:on="Checked" x-state:off="Not Checked" :class="{ 'text-indigo-900': value === 'Private to you', 'text-gray-900': !(value === 'Private to you') }">
                Private to you
              </span>
              <span id="privacy-setting-2-description" class="text-gray-500 block text-sm" x-state:on="Checked" x-state:off="Not Checked" :class="{ 'text-indigo-700': value === 'Private to you', 'text-gray-500': !(value === 'Private to you') }">
                You are the only one able to access this project
              </span>
            </div>
          </label>
      
      </div>
    </fieldset>

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
