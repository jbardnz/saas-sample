<template>
  <div class="h-full">
    <ul class="list-reset flex border-b mt-5 container mx-auto px-20">
      <li class="p-0 rounded-t border border-b-0 border-gray-300">
        <a
          class="bg-gray-200 inline-block py-2 px-4 text-green-500 active"
          data-select="one"
          id="one"
          href="javascript:void(0)"
        >
          <svg
            class="h-6 w-6 inline"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M16 8v8m-4-5v5m-4-2v2m-2 4h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"
            />
          </svg>
          Activity</a
        >
      </li>
      <li class="p-0">
        <a
          class="bg-white inline-block py-2 px-4 text-gray-400  hover:text-green-600 font-semibold"
          data-select="two"
          id="two"
          href="javascript:void(0)"
          ><svg
            class="h-6 w-6 inline"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"
            /></svg
          >Detail</a
        >
      </li>
    </ul>
    <div class="bg-gray-200 border-t border-gray-300 h-full">
      <div class="container mx-auto px-20 pt-5">
        Content Goes Here
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tabs',
}
</script>
