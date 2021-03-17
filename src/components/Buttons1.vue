<template>
  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="bg-gray-900 hover:bg-gray-800 text-white transition-all duration-150 ease-in-out font-semibold px-5 py-2 rounded"
    >
      <template v-slot:textbtn>Click Me prop</template>
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="bg-gray-900 hover:bg-gray-800 text-white transition-all duration-150 ease-in-out font-semibold px-5 py-2 rounded flex items-center"
    >
      <template v-slot:svg>
        <svg
            viewBox="0 0 20 20"
            fill="currentColor"
            class="search w-5 h-5 mr-1"
        >
          <path
              fill-rule="evenodd"
              d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
              clip-rule="evenodd"
          ></path>
        </svg>
      </template>

      <template v-slot:textaftersvg>Search</template>
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="bg-gray-900 hover:bg-gray-800 text-white transition-all duration-150 ease-in-out font-semibold px-5 py-2 rounded flex items-center"
    >
      <template v-slot:svg>
        <svg
            viewBox="0 0 20 20"
            fill="currentColor"
            class="search w-5 h-5 mr-1"
        >
          <path
              fill-rule="evenodd"
              d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
              clip-rule="evenodd"
          ></path>
        </svg>
      </template>
      <template v-slot:textaftersvg>Search</template>
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="bg-transparent border-2 border-gray-900 hover:bg-gray-900 text-gray-900 hover:text-white transition-all duration-150 ease-in-out font-semibold px-5 py-2 rounded flex items-center"
    >
      <template v-slot:svg>
        <svg
            viewBox="0 0 20 20"
            fill="currentColor"
            class="search w-5 h-5 mr-1"
        >
          <path
              fill-rule="evenodd"
              d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
              clip-rule="evenodd"
          ></path>
        </svg>
      </template>
      <template v-slot:textaftersvg>Search</template>
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="bg-transparent hover:bg-gray-300 text-gray-900 hover:text-gray-900 transition-all duration-300 ease-in-out font-semibold px-5 py-2 rounded flex items-center"
    >
      <template v-slot:svg>
        <svg
            viewBox="0 0 20 20"
            fill="currentColor"
            class="search w-5 h-5 mr-1"
        >
          <path
              fill-rule="evenodd"
              d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
              clip-rule="evenodd"
          ></path>
        </svg>
      </template>
      <template v-slot:textaftersvg>Search</template>
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="inline-block px-4 py-2 mr-2 bg-gray-900 hover:bg-gray-800 rounded font-semibold text-white"
    >
      Filled Button
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="inline-block px-4 py-2 mr-2 border-2 border-gray-900 hover:bg-gray-800 rounded font-semibold text-black hover:text-white"
    >
      Hollow Button
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="inline-block px-4 py-2 mr-2 border-2 border-gray-900 hover:bg-gray-800 rounded font-semibold text-black hover:text-white"
    >
      Hollow Button
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <Button1
        btn-class="inline-block pl-2 pr-4 py-2 mr-2 bg-gray-900 hover:bg-gray-800 rounded font-semibold text-white"
    >
      <template v-slot:svg>
        <svg
            class="float-left w-6 h-6 fill-current mr-2"
            viewBox="0 0 100 100"
            xmlns="http://www.w3.org/2000/svg"
        >
          <g>
            <path
                d="m72.082 36.668l-17.914 17.914v-42.082h-8.3359v42.082l-17.914-17.914-5.8359 5.832 27.918 27.918 27.918-27.918z"
            />
            <path d="m27.082 79.168h45.832v8.332h-45.832z"/>
          </g>
        </svg>
      </template>

      <template v-slot:textaftersvg>
        Filled Icon Button
      </template>
    </Button1>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button
        class="inline-block pl-2 pr-4 py-2 mr-2 border-2 border-gray-900 hover:bg-gray-800 rounded font-semibold text-black hover:text-white"
    >
      <svg
          class="float-left w-6 h-6 fill-current mr-2"
          viewBox="0 0 100 100"
          xmlns="http://www.w3.org/2000/svg"
      >
        <g>
          <path
              d="m72.082 36.668l-17.914 17.914v-42.082h-8.3359v42.082l-17.914-17.914-5.8359 5.832 27.918 27.918 27.918-27.918z"
          />
          <path d="m27.082 79.168h45.832v8.332h-45.832z"/>
        </g>
      </svg>
      Hollow Button
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button
        class="inline-block px-4 py-2 mr-2 bg-gray-200 hover:bg-gray-800 rounded font-semibold text-black hover:text-white"
    >
      Light Button
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button
        class="inline-block pl-2 pr-4 py-2 mr-2 bg-gray-200 hover:bg-gray-800 rounded font-semibold text-black hover:text-white"
    >
      <svg
          class="float-left w-6 h-6 fill-current mr-2"
          viewBox="0 0 100 100"
          xmlns="http://www.w3.org/2000/svg"
      >
        <g>
          <path
              d="m72.082 36.668l-17.914 17.914v-42.082h-8.3359v42.082l-17.914-17.914-5.8359 5.832 27.918 27.918 27.918-27.918z"
          />
          <path d="m27.082 79.168h45.832v8.332h-45.832z"/>
        </g>
      </svg>
      Light Icon Button
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button
        class="inline-block px-4 py-2 mr-2 bg-gray-900 hover:bg-gray-800 rounded font-semibold text-white hover:shadow-xl"
    >
      Hover Shadow Button
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button
        class="inline-block pl-2 pr-4 py-2 mr-2 bg-gray-900 hover:bg-gray-800 rounded font-semibold text-white hover:shadow-xl"
    >
      <svg
          class="float-left w-6 h-6 fill-current mr-2"
          viewBox="0 0 100 100"
          xmlns="http://www.w3.org/2000/svg"
      >
        <g>
          <path
              d="m72.082 36.668l-17.914 17.914v-42.082h-8.3359v42.082l-17.914-17.914-5.8359 5.832 27.918 27.918 27.918-27.918z"
          />
          <path d="m27.082 79.168h45.832v8.332h-45.832z"/>
        </g>
      </svg>

      Filled Icon Button
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button class='relative bg-blue-500 text-white p-6 rounded text-2xl font-bold overflow-hidden'>
      Example button
      <div class="ribbon bg-red-500 text-sm whitespace-no-wrap px-4">premium</div>
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button class='relative bg-blue-500 text-white p-6 rounded text-2xl font-bold overflow-hidden'>
      Example button
      <div class="ribbon bg-red-500 text-sm whitespace-no-wrap px-4">for sale</div>
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <button class='relative bg-blue-500 text-white p-6 rounded text-2xl font-bold overflow-hidden'>
      Example button
      <div class="ribbon bg-red-500 text-sm whitespace-no-wrap px-4">ABC</div>
    </button>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <div class="flex">
      <button
          class="border border-teal-500 text-teal-500 block rounded-sm font-bold py-4 px-6 mr-2 flex items-center hover:bg-teal-500 hover:text-white">
        <svg class="h-5 w-5 mr-2 fill-current" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg"
             xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="-49 141 512 512"
             style="enable-background:new -49 141 512 512;" xml:space="preserve">
            <path id="XMLID_10_"
                  d="M438,372H36.355l72.822-72.822c9.763-9.763,9.763-25.592,0-35.355c-9.763-9.764-25.593-9.762-35.355,0 l-115.5,115.5C-46.366,384.01-49,390.369-49,397s2.634,12.989,7.322,17.678l115.5,115.5c9.763,9.762,25.593,9.763,35.355,0 c9.763-9.763,9.763-25.592,0-35.355L36.355,422H438c13.808,0,25-11.193,25-25S451.808,372,438,372z"></path>
        </svg>
        Previous page
      </button>
      <button
          class="border border-teal-500 bg-teal-500 text-white block rounded-sm font-bold py-4 px-6 ml-2 flex items-center">
        Next page
        <svg class="h-5 w-5 ml-2 fill-current" clasversion="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg"
             xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
             viewBox="-49 141 512 512" style="enable-background:new -49 141 512 512;" xml:space="preserve">
        <path id="XMLID_11_" d="M-24,422h401.645l-72.822,72.822c-9.763,9.763-9.763,25.592,0,35.355c9.763,9.764,25.593,9.762,35.355,0
            l115.5-115.5C460.366,409.989,463,403.63,463,397s-2.634-12.989-7.322-17.678l-115.5-115.5c-9.763-9.762-25.593-9.763-35.355,0
            c-9.763,9.763-9.763,25.592,0,35.355l72.822,72.822H-24c-13.808,0-25,11.193-25,25S-37.808,422-24,422z"/>
        </svg>
      </button>
    </div>
  </div>

  <div class="inline-flex rounded shadow-sm my-2"><!-- This is an example component -->
    <div class="flex mt-5">
      <div class="m-3">
        <button
            class="w-32 bg-white tracking-wide text-gray-800 font-bold rounded border-b-2 border-blue-500 hover:border-blue-600 hover:bg-blue-500 hover:text-white shadow-md py-2 px-6 inline-flex items-center">
          <span class="mx-auto">Male</span>
        </button>
      </div>
      <div class="m-3">
        <button
            class="w-32 bg-white tracking-wide text-gray-800 font-bold rounded border-b-2 border-red-500 hover:border-red-600 hover:bg-red-500 hover:text-white shadow-md py-2 px-6 inline-flex items-center">
          <span class="mx-auto">Female</span>

        </button>
      </div>
    </div>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <!-- component -->
    <span class="text-sm font-medium bg-green-100 py-1 px-2 rounded text-green-500 align-middle">Paid</span>
    <span class="text-sm font-medium bg-red-100 py-1 px-2 rounded text-red-500 align-middle">Overdue</span>

  </div>

  <div class="inline-flex rounded shadow-sm my-2"><!-- component -->
    <div class="flex flex-shrink-0">
      <div class="flex flex-shrink-0 text-sm items-center px-2">
        <div class="bg-gray-400 text-gray-600 px-2 py-1 rounded-l-md">Type</div>
        <div class="bg-gray-500 text-green-100 px-2 py-1 rounded-r-md">Primary</div>
      </div>

      <div class="flex flex-shrink-0 text-sm items-center pr-2">
        <div class="bg-gray-300 text-gray-600 px-2 py-1 rounded-l">Status</div>
        <div class="bg-green-200 text-green-700 px-2 py-1 rounded-r">Active</div>
      </div>

      <div class="flex flex-shrink-0 text-sm items-center pr-2">
        <div class="bg-gray-300 text-gray-600 px-2 py-1 rounded-l">Status</div>
        <div class="bg-red-200 text-red-900 px-2 py-1 rounded-r">Closed</div>
      </div>
    </div>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <div class="mb-5">
      <a href="#"
         class="cursor-pointer bg-blue-600 hover:bg-blue-500 shadow-xl px-5 py-2 inline-block text-blue-100 hover:text-white rounded">Primary</a>
      <button type="submit"
              class="cursor-pointer bg-orange-600 hover:bg-orange-500 shadow-xl px-5 py-2 inline-block text-orange-100 hover:text-white rounded">
        Warning
      </button>
      <input type="button"
             class="cursor-pointer bg-red-600 hover:bg-red-500 shadow-xl px-5 py-2 inline-block text-orange-100 hover:text-white rounded"
             value="Danger">
      <a href="#"
         class="cursor-pointer bg-gray-700 hover:bg-gray-600 shadow-xl px-5 py-2 inline-block text-blue-100 hover:text-white rounded">Inverse</a>
      <a href="#"
         class="cursor-pointer bg-teal-600 hover:bg-teal-500 shadow-xl px-5 py-2 inline-block text-teal-100 hover:text-white rounded">Success</a>
    </div>
    <div class="mb-5">
      <button
          class="bg-blue-500 hover:bg-blue-400 text-white font-semibold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
        3D Button
      </button>
    </div>
    <div class="mb-5">
      <div class="inline-flex">
        <button class="bg-gray-400 hover:bg-gray-500 text-gray-800 font-bold py-2 px-4 rounded-l">
          Prev
        </button>
        <button class="bg-gray-400 hover:bg-gray-500 text-gray-800 font-bold py-2 px-4 rounded-r">
          Next
        </button>
      </div>
    </div>
    <div class="mb-5">
      <button
          class="cursor-pointer bg-teal-600 hover:bg-teal-500 text-teal-100 py-2 px-4 rounded inline-flex items-center">
        <svg class="fill-current w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
          <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z"/>
        </svg>
        <span>Download</span>
      </button>
      <a href="#"
         class="cursor-pointer bg-blue-600 hover:bg-blue-500 text-blue-100 py-2 px-4 rounded inline-flex items-center">
        <svg class="fill-current w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg"
             xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 20 20"
             enable-background="new 0 0 20 20" xml:space="preserve"> <path
            d="M17.316,6.246c0.008,0.162,0.011,0.326,0.011,0.488c0,4.99-3.797,10.742-10.74,10.742c-2.133,0-4.116-0.625-5.787-1.697 c0.296,0.035,0.596,0.053,0.9,0.053c1.77,0,3.397-0.604,4.688-1.615c-1.651-0.031-3.046-1.121-3.526-2.621 c0.23,0.043,0.467,0.066,0.71,0.066c0.345,0,0.679-0.045,0.995-0.131c-1.727-0.348-3.028-1.873-3.028-3.703c0-0.016,0-0.031,0-0.047 c0.509,0.283,1.092,0.453,1.71,0.473c-1.013-0.678-1.68-1.832-1.68-3.143c0-0.691,0.186-1.34,0.512-1.898 C3.942,5.498,6.725,7,9.862,7.158C9.798,6.881,9.765,6.594,9.765,6.297c0-2.084,1.689-3.773,3.774-3.773 c1.086,0,2.067,0.457,2.756,1.191c0.859-0.17,1.667-0.484,2.397-0.916c-0.282,0.881-0.881,1.621-1.66,2.088 c0.764-0.092,1.49-0.293,2.168-0.594C18.694,5.051,18.054,5.715,17.316,6.246z"/> </svg>
        <span>Login with Twitter</span>
      </a>
      <a class="cursor-pointer bg-orange-600 hover:bg-orange-500 text-orange-100 py-2 px-4 rounded inline-flex items-center">
        <svg class="fill-current w-4 h-4 mr-2" version="1.1" id="Open_book" xmlns="http://www.w3.org/2000/svg"
             xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 20 20"
             enable-background="new 0 0 20 20" xml:space="preserve"> <path
            d="M10.595,5.196l0.446,1.371c0.369-0.316,0.835-0.599,1.441-0.795c0.59-0.192,1.111-0.3,1.582-0.362l-0.43-1.323 c-0.476,0.069-1.001,0.18-1.58,0.368C11.476,4.643,10.999,4.905,10.595,5.196z M11.522,8.051l0.446,1.371 c0.369-0.316,0.835-0.599,1.441-0.795c0.59-0.192,1.111-0.3,1.582-0.362l-0.43-1.323c-0.476,0.069-1.001,0.18-1.58,0.368 C12.403,7.497,11.927,7.759,11.522,8.051z M12.45,10.905l0.446,1.371c0.369-0.316,0.835-0.599,1.441-0.795 c0.59-0.192,1.111-0.3,1.582-0.362l-0.43-1.323c-0.476,0.069-1.001,0.18-1.58,0.368C13.33,10.351,12.854,10.614,12.45,10.905z M5.388,13.077l0.43,1.323c0.417-0.226,0.902-0.445,1.492-0.636c0.606-0.197,1.149-0.242,1.633-0.203l-0.446-1.371 c-0.499,0.002-1.038,0.07-1.615,0.257C6.303,12.635,5.813,12.853,5.388,13.077z M3.533,7.368l0.43,1.323 C4.38,8.465,4.865,8.247,5.455,8.055c0.606-0.197,1.149-0.242,1.633-0.203L6.643,6.48C6.144,6.483,5.605,6.55,5.027,6.738 C4.448,6.926,3.958,7.144,3.533,7.368z M4.46,10.223l0.43,1.323c0.417-0.226,0.902-0.445,1.492-0.636 c0.606-0.197,1.149-0.242,1.633-0.203L7.57,9.335c-0.499,0.002-1.038,0.07-1.615,0.257C5.376,9.78,4.885,9.999,4.46,10.223z M11.064,1.41C9.341,1.97,8.441,3.162,8.011,3.969c-0.822-0.4-2.25-0.835-3.973-0.275c-2.523,0.82-3.969,2.627-3.969,2.627 l4.095,12.587c0.126,0.387,0.646,0.477,0.878,0.143c0.499-0.719,1.46-1.658,3.257-2.242c1.718-0.558,2.969,0.054,3.655,0.578 c0.272,0.208,0.662,0.06,0.762-0.268c0.252-0.827,0.907-2.04,2.61-2.593c1.799-0.585,3.129-0.389,3.956-0.1 c0.385,0.134,0.75-0.242,0.625-0.629L15.819,1.203C15.819,1.203,13.587,0.591,11.064,1.41z M10.951,15.256 c-0.819-0.244-1.901-0.358-3.141,0.044c-1.251,0.406-2.127,0.949-2.699,1.404L1.866,6.722C2.224,6.364,3.053,5.68,4.528,5.201 c1.389-0.451,2.528-0.065,3.279,0.378L10.951,15.256z M17.845,12.567c-0.731-0.032-1.759,0.044-3.01,0.451 c-1.24,0.403-2.048,1.132-2.567,1.81L9.124,5.151c0.346-0.8,1.04-1.782,2.43-2.233c1.474-0.479,2.547-0.413,3.047-0.334 L17.845,12.567z"/> </svg>
        <span>Booktime</span>
      </a>
    </div>
    <div>
      <button class="bg-blue-500 text-white font-semibold py-2 px-4 rounded opacity-50 cursor-not-allowed">
        Primary
      </button>
      <button class="bg-orange-500 text-white font-semibold py-2 px-4 rounded opacity-50 cursor-not-allowed">
        Warning
      </button>
      <button class="bg-red-500 text-white font-semibold py-2 px-4 rounded opacity-50 cursor-not-allowed">
        Danger
      </button>
    </div>

  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <!-- component -->
    <div class="flex items-center justify-center">
      <div class="m-3">
        <button
            class="bg-white text-gray-800 font-bold rounded border-b-2 border-green-500 hover:border-green-600 hover:bg-green-500 hover:text-white shadow-md py-2 px-6 inline-flex items-center">
          <span class="mr-2">Send</span>
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="currentcolor" d="M2.01 21L23 12 2.01 3 2 10l15 2-15 2z"></path>
          </svg>
        </button>
      </div>

      <div class="m-3">
        <button
            class="bg-white text-gray-800 font-bold rounded border-b-2 border-red-500 hover:border-red-600 hover:bg-red-500 hover:text-white shadow-md py-2 px-6 inline-flex items-center">
          <span class="mr-2">Close</span>
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="currentcolor"
                  d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12 19 6.41z"/>
          </svg>
        </button>
      </div>

      <div class="m-3">
        <button
            class="bg-white text-gray-800 font-bold rounded border-b-2 border-yellow-500 hover:border-yellow-600 hover:bg-yellow-500 hover:text-white shadow-md py-2 px-6 inline-flex items-center">
          <span class="mr-2">Wait</span>
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="currentcolor"
                  d="M6 2v6h.01L6 8.01 10 12l-4 4 .01.01H6V22h12v-5.99h-.01L18 16l-4-4 4-3.99-.01-.01H18V2H6zm10 14.5V20H8v-3.5l4-4 4 4zm-4-5l-4-4V4h8v3.5l-4 4z"></path>
          </svg>
        </button>
      </div>
    </div>

  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <section class="mt-8 container mx-auto flex items-center justify-around">
      <div>
        <div class="flex rounded border-b-2 border-grey-dark overflow-hidden">
          <button
              class="block text-white text-sm shadow-border bg-blue-500 dark:hover:bg-blue-600 text-sm py-3 px-4 font-sans tracking-wide uppercase font-bold">
            contact us
          </button>
          <div class="bg-blue-300 shadow-border p-3">
            <div class="w-4 h-4">
              <svg class="fill-current text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M1664 1504v-768q-32 36-69 66-268 206-426 338-51 43-83 67t-86.5 48.5-102.5 24.5h-2q-48 0-102.5-24.5t-86.5-48.5-83-67q-158-132-426-338-37-30-69-66v768q0 13 9.5 22.5t22.5 9.5h1472q13 0 22.5-9.5t9.5-22.5zm0-1051v-24.5l-.5-13-3-12.5-5.5-9-9-7.5-14-2.5h-1472q-13 0-22.5 9.5t-9.5 22.5q0 168 147 284 193 152 401 317 6 5 35 29.5t46 37.5 44.5 31.5 50.5 27.5 43 9h2q20 0 43-9t50.5-27.5 44.5-31.5 46-37.5 35-29.5q208-165 401-317 54-43 100.5-115.5t46.5-131.5zm128-37v1088q0 66-47 113t-113 47h-1472q-66 0-113-47t-47-113v-1088q0-66 47-113t113-47h1472q66 0 113 47t47 113z"/>
              </svg>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="flex rounded border-b-2 dark:border-gray-500 overflow-hidden">
          <button
              class="block text-white text-sm shadow-border bg-green-500 dark:hover:bg-green-500 text-sm py-3 px-4 font-sans tracking-wide uppercase font-bold">
            schedule a demo
          </button>
          <div class="bg-green-300 shadow-border p-3">
            <div class="w-4 h-4">
              <svg class="fill-current text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M1024 544v448q0 14-9 23t-23 9h-320q-14 0-23-9t-9-23v-64q0-14 9-23t23-9h224v-352q0-14 9-23t23-9h64q14 0 23 9t9 23zm416 352q0-148-73-273t-198-198-273-73-273 73-198 198-73 273 73 273 198 198 273 73 273-73 198-198 73-273zm224 0q0 209-103 385.5t-279.5 279.5-385.5 103-385.5-103-279.5-279.5-103-385.5 103-385.5 279.5-279.5 385.5-103 385.5 103 279.5 279.5 103 385.5z"/>
              </svg>
            </div>
          </div>
        </div>
      </div>
    </section>

  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <section class="container mx-auto px-6 my-1 flex flex-wrap -m-4">
      <div class="p-2 md:w-40 ">
        <a href="#"
           class="flex items-center p-4 bg-blue-200 rounded-lg shadow-xs cursor-pointer hover:bg-blue-500 hover:text-gray-100">

          <svg class="h-6 fill-current hover:text-gray-100 " viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <title>PHP icon</title>
            <path
                d="M7.01 10.207h-.944l-.515 2.648h.838c.556 0 .97-.105 1.242-.314.272-.21.455-.559.55-1.049.092-.47.05-.802-.124-.995-.175-.193-.523-.29-1.047-.29zM12 5.688C5.373 5.688 0 8.514 0 12s5.373 6.313 12 6.313S24 15.486 24 12c0-3.486-5.373-6.312-12-6.312zm-3.26 7.451c-.261.25-.575.438-.917.551-.336.108-.765.164-1.285.164H5.357l-.327 1.681H3.652l1.23-6.326h2.65c.797 0 1.378.209 1.744.628.366.418.476 1.002.33 1.752a2.836 2.836 0 0 1-.305.847c-.143.255-.33.49-.561.703zm4.024.715l.543-2.799c.063-.318.039-.536-.068-.651-.107-.116-.336-.174-.687-.174H11.46l-.704 3.625H9.388l1.23-6.327h1.367l-.327 1.682h1.218c.767 0 1.295.134 1.586.401s.378.7.263 1.299l-.572 2.944h-1.389zm7.597-2.265a2.782 2.782 0 0 1-.305.847c-.143.255-.33.49-.561.703a2.44 2.44 0 0 1-.917.551c-.336.108-.765.164-1.286.164h-1.18l-.327 1.682h-1.378l1.23-6.326h2.649c.797 0 1.378.209 1.744.628.366.417.477 1.001.331 1.751zM17.766 10.207h-.943l-.516 2.648h.838c.557 0 .971-.105 1.242-.314.272-.21.455-.559.551-1.049.092-.47.049-.802-.125-.995s-.524-.29-1.047-.29z"/>
          </svg>
          <div>
            <p class=" text-xs font-medium ml-2 ">
              PHP
            </p>

          </div>
        </a>
      </div>

      <div class="p-2 md:w-40 ">
        <div
            class="flex items-center p-4 bg-gray-200 rounded-lg shadow-xs cursor-pointer hover:bg-gray-500 hover:text-gray-100">

          <svg class="h-6 fill-current hover:text-gray-100" role="img" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg"><title>Symfony icon</title>
            <path
                d="M24 12c0 6.628-5.372 12-12 12S0 18.628 0 12 5.372 0 12 0s12 5.372 12 12zm-6.753-7.561c-1.22.042-2.283.715-3.075 1.644-.878 1.02-1.461 2.229-1.881 3.461-.753-.614-1.332-1.414-2.539-1.761-.966-.297-2.015-.105-2.813.514-.41.319-.71.757-.861 1.254-.36 1.176.381 2.225.719 2.6l.737.79c.15.154.519.56.339 1.138-.193.631-.951 1.037-1.732.799-.348-.106-.848-.366-.734-.73.045-.15.152-.263.21-.391.052-.11.077-.194.095-.242.141-.465-.053-1.07-.551-1.223-.465-.143-.939-.03-1.125.566-.209.68.117 1.913 1.86 2.449 2.04.628 3.765-.484 4.009-1.932.153-.907-.255-1.582-1.006-2.447l-.612-.677c-.371-.37-.497-1.002-.114-1.485.324-.409.785-.584 1.539-.379 1.103.3 1.594 1.063 2.412 1.68-.338 1.11-.56 2.223-.759 3.222l-.123.746c-.585 3.07-1.033 4.757-2.194 5.726-.234.166-.57.416-1.073.434-.266.005-.352-.176-.355-.257-.006-.184.15-.271.255-.353.154-.083.39-.224.372-.674-.016-.532-.456-.994-1.094-.973-.477.017-1.203.465-1.176 1.286.028.85.819 1.485 2.012 1.444.638-.021 2.062-.281 3.464-1.949 1.633-1.911 2.09-4.101 2.434-5.706l.383-2.116c.213.024.441.042.69.048 2.032.044 3.049-1.01 3.064-1.776.01-.464-.304-.921-.744-.91-.386.009-.718.278-.806.654-.094.428.646.813.068 1.189-.41.266-1.146.452-2.184.3l.188-1.042c.386-1.976.859-4.407 2.661-4.467.132-.007.612.006.623.323.003.105-.022.134-.147.375-.115.155-.174.345-.168.537.017.504.4.836.957.816.743-.023.955-.748.945-1.119-.032-.874-.952-1.424-2.17-1.386z"/>
          </svg>
          <div>
            <p class="text-xs font-medium ml-2 ">
              SYMFONY
            </p>

          </div>
        </div>
      </div>
      <div class="p-2 md:w-40 ">
        <div
            class="flex items-center p-4 bg-orange-200 rounded-lg shadow-xs cursor-pointer hover:bg-orange-500 hover:text-gray-100">

          <svg class="h-6 fill-current hover:text-gray-100" role="img" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg"><title>HTML5 icon</title>
            <path
                d="M1.5 0h21l-1.91 21.563L11.977 24l-8.564-2.438L1.5 0zm7.031 9.75l-.232-2.718 10.059.003.23-2.622L5.412 4.41l.698 8.01h9.126l-.326 3.426-2.91.804-2.955-.81-.188-2.11H6.248l.33 4.171L12 19.351l5.379-1.443.744-8.157H8.531z"/>
          </svg>
          <div>
            <p class=" text-xs font-medium ml-2 ">
              HTML
            </p>

          </div>
        </div>
      </div>

      <div class="p-2 md:w-40 ">
        <div
            class="flex items-center p-4 bg-green-200 rounded-lg shadow-xs cursor-pointer hover:bg-green-500 hover:text-gray-100">

          <svg class="h-6 fill-current hover:text-gray-100" role="img" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg"><title>Vue.js icon</title>
            <path d="M19.197 1.608l.003-.006h-4.425L12 6.4v.002l-2.772-4.8H4.803v.005H0l12 20.786L24 1.608"/>
          </svg>
          <div>
            <p class=" text-xs font-medium ml-2 ">
              VUE
            </p>

          </div>
        </div>
      </div>
      <div class="p-2 md:w-40 ">
        <div
            class="flex items-center p-4 bg-yellow-200 rounded-lg shadow-xs cursor-pointer hover:bg-yellow-500 hover:text-gray-100">

          <svg class="h-6 fill-current hover:text-gray-100" role="img" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg"><title>JavaScript icon</title>
            <path
                d="M0 0h24v24H0V0zm22.034 18.276c-.175-1.095-.888-2.015-3.003-2.873-.736-.345-1.554-.585-1.797-1.14-.091-.33-.105-.51-.046-.705.15-.646.915-.84 1.515-.66.39.12.75.42.976.9 1.034-.676 1.034-.676 1.755-1.125-.27-.42-.404-.601-.586-.78-.63-.705-1.469-1.065-2.834-1.034l-.705.089c-.676.165-1.32.525-1.71 1.005-1.14 1.291-.811 3.541.569 4.471 1.365 1.02 3.361 1.244 3.616 2.205.24 1.17-.87 1.545-1.966 1.41-.811-.18-1.26-.586-1.755-1.336l-1.83 1.051c.21.48.45.689.81 1.109 1.74 1.756 6.09 1.666 6.871-1.004.029-.09.24-.705.074-1.65l.046.067zm-8.983-7.245h-2.248c0 1.938-.009 3.864-.009 5.805 0 1.232.063 2.363-.138 2.711-.33.689-1.18.601-1.566.48-.396-.196-.597-.466-.83-.855-.063-.105-.11-.196-.127-.196l-1.825 1.125c.305.63.75 1.172 1.324 1.517.855.51 2.004.675 3.207.405.783-.226 1.458-.691 1.811-1.411.51-.93.402-2.07.397-3.346.012-2.054 0-4.109 0-6.179l.004-.056z"/>
          </svg>
          <div>
            <p class=" text-xs font-medium text-uppercase ml-2 ">
              javascript
            </p>

          </div>
        </div>
      </div>
      <div class="p-2 md:w-40 ">
        <div
            class="flex items-center p-4 bg-indigo-200 rounded-lg shadow-xs cursor-pointer hover:bg-indigo-500 hover:text-gray-100">

          <svg class="h-6 fill-current hover:text-gray-100" role="img" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg"><title>CSS3 icon</title>
            <path
                d="M1.5 0h21l-1.91 21.563L11.977 24l-8.565-2.438L1.5 0zm17.09 4.413L5.41 4.41l.213 2.622 10.125.002-.255 2.716h-6.64l.24 2.573h6.182l-.366 3.523-2.91.804-2.956-.81-.188-2.11h-2.61l.29 3.855L12 19.288l5.373-1.53L18.59 4.414z"/>
          </svg>
          <div>
            <p class=" text-xs font-medium ml-2 ">
              CSS
            </p>

          </div>
        </div>
      </div>
      <div class="p-2 md:w-40 ">
        <div
            class="flex items-center p-4 bg-red-200 rounded-lg shadow-xs cursor-pointer hover:bg-red-500 hover:text-gray-100">

          <svg class="h-6 fill-current hover:text-gray-100" role="img" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg"><title>Laravel icon</title>
            <path
                d="M23.644 5.43c.009.032.014.065.014.099v5.15c0 .135-.073.26-.189.326l-4.323 2.49v4.934c0 .135-.072.258-.188.326L9.931 23.95c-.021.012-.043.02-.066.027-.008.002-.016.008-.024.01-.063.018-.13.018-.192 0-.011-.002-.02-.008-.029-.012-.021-.008-.043-.014-.063-.025L.534 18.755c-.117-.068-.189-.191-.189-.326V2.974c0-.033.005-.066.014-.098.003-.012.01-.021.014-.032.006-.02.014-.04.023-.058.004-.013.015-.022.023-.033.012-.016.021-.031.033-.045.012-.01.025-.018.037-.027.014-.012.027-.024.041-.034h.001L5.044.05c.115-.067.259-.067.375 0l4.512 2.597h.002c.015.01.027.021.041.033.012.009.025.018.037.027.013.014.021.029.033.045.008.011.02.021.025.033.011.019.017.038.024.058.003.011.011.021.013.032.01.031.014.064.014.098v9.652l3.76-2.164V5.527c0-.033.005-.066.014-.098.003-.011.009-.021.013-.032.007-.02.014-.039.024-.059.007-.012.018-.021.025-.033.012-.015.021-.03.033-.043.012-.012.025-.02.037-.028.014-.011.026-.023.041-.032h.001l4.513-2.598c.116-.067.259-.067.375 0l4.513 2.598c.016.01.027.021.042.031.012.01.025.018.036.028.013.014.022.029.034.044.008.012.019.021.024.033.011.02.018.039.024.059.006.011.012.022.015.033zm-.74 5.032V6.179l-1.578.908-2.182 1.256v4.283l3.76-2.164zm-4.511 7.75v-4.287l-2.146 1.225-6.127 3.498v4.326l8.273-4.762zM1.095 3.624v14.588l8.273 4.762v-4.326l-4.322-2.445-.002-.003h-.002c-.014-.01-.025-.021-.04-.031-.011-.01-.024-.018-.035-.027l-.001-.002c-.013-.012-.021-.025-.031-.039-.01-.012-.021-.023-.028-.037h-.002c-.008-.014-.013-.031-.02-.047-.006-.016-.014-.027-.018-.043-.004-.018-.006-.037-.008-.057-.002-.014-.006-.027-.006-.041V5.789l-2.18-1.257-1.578-.908zM5.231.81l-3.76 2.164 3.76 2.164 3.758-2.164L5.231.81zm1.956 13.505l2.182-1.256V3.624l-1.58.909-2.182 1.256v9.435l1.58-.909zM18.769 3.364l-3.76 2.164 3.76 2.163 3.759-2.164-3.759-2.163zm-.376 4.979l-2.182-1.256-1.579-.908v4.283l2.182 1.256 1.579.908V8.343zm-8.65 9.654l5.514-3.148 2.756-1.572-3.757-2.163-4.324 2.489-3.941 2.27 3.752 2.124z"/>
          </svg>
          <div>
            <p class=" text-xs font-medium ml-2 ">
              LARAVEL
            </p>

          </div>
        </div>
      </div>


    </section>

  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <!-- component -->
    <div class="flex py-8">
      <!-- Icons Only -->
      <div class="flex flex-col">
        <button
            class="inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-white border-gray-300 text-gray-700"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-activity -mx-2 leading-5"
          >
            <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
          </svg>
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-blue-600 border-blue-600 text-gray-100 hover:bg-blue-500 hover:border-blue-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-airplay -mx-2 leading-5"
          >
            <path
                d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1"
            ></path>
            <polygon points="12 15 17 21 7 21 12 15"></polygon>
          </svg>
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-green-600 border-green-600 text-gray-100 hover:bg-green-500 hover:border-green-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-archive -mx-2 leading-5"
          >
            <polyline points="21 8 21 21 3 21 3 8"></polyline>
            <rect x="1" y="3" width="22" height="5"></rect>
            <line x1="10" y1="12" x2="14" y2="12"></line>
          </svg>
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-orange-600 border-orange-600 text-gray-100 hover:bg-orange-500 hover:border-orange-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-arrow-right -mx-2 leading-5"
          >
            <line x1="5" y1="12" x2="19" y2="12"></line>
            <polyline points="12 5 19 12 12 19"></polyline>
          </svg>
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-red-600 border-red-600 text-gray-100 hover:bg-red-500 hover:border-red-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-bell-off -mx-2 leading-5"
          >
            <path d="M13.73 21a2 2 0 0 1-3.46 0"></path>
            <path d="M18.63 13A17.89 17.89 0 0 1 18 8"></path>
            <path d="M6.26 6.26A5.86 5.86 0 0 0 6 8c0 7-3 9-3 9h14"></path>
            <path d="M18 8a6 6 0 0 0-9.33-5"></path>
            <line x1="1" y1="1" x2="23" y2="23"></line>
          </svg>
        </button>
      </div>

      <!-- Text Only -->
      <div class="flex flex-col ml-4">
        <button
            class="inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-white border-gray-300 text-gray-700"
        >
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-blue-600 border-blue-600 text-gray-100 hover:bg-blue-500 hover:border-blue-500 hover:text-gray-100"
        >
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-green-600 border-green-600 text-gray-100 hover:bg-green-500 hover:border-green-500 hover:text-gray-100"
        >
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-orange-600 border-orange-600 text-gray-100 hover:bg-orange-500 hover:border-orange-500 hover:text-gray-100"
        >
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-red-600 border-red-600 text-gray-100 hover:bg-red-500 hover:border-red-500 hover:text-gray-100"
        >
          Button
        </button>
      </div>

      <!-- With Icon -->
      <div class="flex flex-col ml-4">
        <button
            class="inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-white border-gray-300 text-gray-700"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-activity leading-5 mr-2"
          >
            <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
          </svg>
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-blue-600 border-blue-600 text-gray-100 hover:bg-blue-500 hover:border-blue-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-airplay leading-5 mr-2"
          >
            <path
                d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1"
            ></path>
            <polygon points="12 15 17 21 7 21 12 15"></polygon>
          </svg>
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-green-600 border-green-600 text-gray-100 hover:bg-green-500 hover:border-green-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-archive leading-5 mr-2"
          >
            <polyline points="21 8 21 21 3 21 3 8"></polyline>
            <rect x="1" y="3" width="22" height="5"></rect>
            <line x1="10" y1="12" x2="14" y2="12"></line>
          </svg>
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-orange-600 border-orange-600 text-gray-100 hover:bg-orange-500 hover:border-orange-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-arrow-right leading-5 mr-2"
          >
            <line x1="5" y1="12" x2="19" y2="12"></line>
            <polyline points="12 5 19 12 12 19"></polyline>
          </svg>
          Button
        </button>
        <button
            class="mt-4 inline-flex items-center justify-center px-4 py-2 text-base leading-5 rounded-md border font-medium shadow-sm transition ease-in-out duration-150 focus:outline-none focus:shadow-outline bg-red-600 border-red-600 text-gray-100 hover:bg-red-500 hover:border-red-500 hover:text-gray-100"
        >
          <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-bell-off leading-5 mr-2"
          >
            <path d="M13.73 21a2 2 0 0 1-3.46 0"></path>
            <path d="M18.63 13A17.89 17.89 0 0 1 18 8"></path>
            <path d="M6.26 6.26A5.86 5.86 0 0 0 6 8c0 7-3 9-3 9h14"></path>
            <path d="M18 8a6 6 0 0 0-9.33-5"></path>
            <line x1="1" y1="1" x2="23" y2="23"></line>
          </svg>
          Button
        </button>
      </div>
    </div>

  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <!-- component -->
    <div class="w-screen h-screen flex items-center justify-center bg-gray-100">
      <div class="w-full mx-auto py-16">
        <!-- Title -->
        <h1 class="text-3xl text-center font-bold mb-6">
          Button Component (Default)
        </h1>
        <!-- End Title -->

        <!-- Default -->
        <div
            class="bg-white px-6 py-4 my-3 w-3/4 mx-auto shadow rounded-md flex items-center"
        >
          <div class="w-full text-center mx-auto">
            <button
                type="button"
                class="border border-indigo-500 bg-indigo-500 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-indigo-600 focus:outline-none focus:shadow-outline"
            >
              Primary
            </button>
            <button
                type="button"
                class="border border-green-500 bg-green-500 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-green-600 focus:outline-none focus:shadow-outline"
            >
              Success
            </button>
            <button
                type="button"
                class="border border-red-500 bg-red-500 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-red-600 focus:outline-none focus:shadow-outline"
            >
              Error
            </button>
            <button
                type="button"
                class="border border-yellow-500 bg-yellow-500 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-yellow-600 focus:outline-none focus:shadow-outline"
            >
              Warning
            </button>
            <button
                type="button"
                class="border border-teal-500 bg-teal-500 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-teal-600 focus:outline-none focus:shadow-outline"
            >
              Info
            </button>
            <button
                type="button"
                class="border border-gray-700 bg-gray-700 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-gray-800 focus:outline-none focus:shadow-outline"
            >
              Dark
            </button>
            <button
                type="button"
                class="border border-gray-200 bg-gray-200 text-gray-700 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-gray-300 focus:outline-none focus:shadow-outline"
            >
              Light
            </button>
          </div>
        </div>
        <!-- End Default -->
      </div>
    </div>
  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <div class="w-screen h-screen flex items-center justify-center bg-gray-100">
      <div class="w-full mx-auto py-16">
        <!-- Title -->
        <h1 class="text-3xl text-center font-bold mb-6">
          Button Component (Outline)
        </h1>
        <!-- End Title -->

        <!-- Outline -->
        <div
            class="bg-white px-6 py-4 my-3 w-3/4 mx-auto shadow rounded-md flex items-center"
        >
          <div class="w-full text-center mx-auto">
            <button
                type="button"
                class="border border-indigo-500 text-indigo-500 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:text-white hover:bg-indigo-600 focus:outline-none focus:shadow-outline"
            >
              Primary
            </button>
            <button
                type="button"
                class="border border-green-500 text-green-500 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:text-white hover:bg-green-600 focus:outline-none focus:shadow-outline"
            >
              Success
            </button>
            <button
                type="button"
                class="border border-red-500 text-red-500 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:text-white hover:bg-red-600 focus:outline-none focus:shadow-outline"
            >
              Error
            </button>
            <button
                type="button"
                class="border border-yellow-500 text-yellow-500 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:text-white hover:bg-yellow-600 focus:outline-none focus:shadow-outline"
            >
              Warning
            </button>
            <button
                type="button"
                class="border border-teal-500 text-teal-500 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:text-white hover:bg-teal-600 focus:outline-none focus:shadow-outline"
            >
              Info
            </button>
            <button
                type="button"
                class="border border-gray-700 text-gray-700 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:text-white hover:bg-gray-800 focus:outline-none focus:shadow-outline"
            >
              Dark
            </button>
            <button
                type="button"
                class="border border-gray-300 text-gray-700 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-gray-300 focus:outline-none focus:shadow-outline"
            >
              Light
            </button>
          </div>
        </div>
        <!-- End Outline -->
      </div>
    </div>

  </div>

  <div class="inline-flex rounded shadow-sm my-2">
    <!-- component -->
    <div>
      <button class='relative bg-blue-500 text-white p-6 rounded text-2xl font-bold overflow-visible'>
        Example button
        <div class="absolute top-0 right-0 -mt-4 -mr-4 px-4 py-1 bg-red-500 rounded-full">1</div>
      </button>
      <br/><br/><br/>
      <button class='relative bg-blue-500 text-white p-6 rounded text-2xl font-bold overflow-visible'>
        Example button
        <div class="absolute top-0 right-0 -mt-4 -mr-4 px-4 py-1 bg-red-500 rounded-full">2000</div>
      </button>
    </div>

  </div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>

  <div class="inline-flex rounded shadow-sm my-2"></div>
</template>

<script>
import Button1 from "@/components/Button1";

export default {
  name: "Buttons1",
  components: {Button1},
  data() {
    return {};
  }
};
</script>

<style scoped lang="scss">
button {
  margin: 0.61rem;
  transition: all ease-in-out 0.2s;
}

.ribbon {
  position: absolute;
  top: 0;
  right: 0;
  width: 150px;
  height: 22px;
  margin-right: -50px;
  margin-top: 15px;
  -ms-transform: rotate(45deg); /* IE 9 */
  -webkit-transform: rotate(45deg); /* Safari prior 9.0 */
  transform: rotate(45deg); /* Standard syntax */
}
</style>
