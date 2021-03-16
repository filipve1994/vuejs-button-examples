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
            <path d="m27.082 79.168h45.832v8.332h-45.832z" />
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
          <path d="m27.082 79.168h45.832v8.332h-45.832z" />
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
          <path d="m27.082 79.168h45.832v8.332h-45.832z" />
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
          <path d="m27.082 79.168h45.832v8.332h-45.832z" />
        </g>
      </svg>

      Filled Icon Button
    </button>
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
  components: { Button1 },
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
</style>
