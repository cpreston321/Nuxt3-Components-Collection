<template>

  <div class="container">
    
    
   <!-- Rectangular switch -->
    <div>
        <label class="relative inline-block w-16 h-9">
            <input type="checkbox" class="peer opacity-0 w-0 h-0">
            <span class="absolute cursor-pointer top-0 left-0 right-0 bottom-0 bg-gray-300 duration-300 before:content-[''] before:absolute before:w-7 before:h-7 before:bottom-1 before:left-1
                before:bg-white before:duration-300 peer-checked:before:translate-x-7 peer-checked:bg-blue-500"></span>
        </label>
    </div>

    <!-- Rounded switch -->
    <div class="mt-5">
        <label class="relative inline-block w-16 h-9 rounded-full">
            <input type="checkbox" class="peer opacity-0 w-0 h-0">
            <span class="absolute cursor-pointer top-0 left-0 right-0 bottom-0 bg-gray-300 rounded-full duration-300 before:content-[''] before:absolute before:w-7 before:h-7 before:bottom-1 before:left-1 before:rounded-full
                before:bg-white before:duration-300 peer-checked:before:translate-x-7 peer-checked:bg-blue-500"></span>
        </label>
    </div>
    

  </div>

</template>

<script setup>
  useHead({
    titleTemplate: (titleChunk) => {
      return titleChunk ? `${titleChunk} - Toggle Switches` : 'Toggle Switches';
    }
  })
</script>
