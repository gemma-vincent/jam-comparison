<template>
  <Layout>
    <h1
      class="text-3xl md:text-5xl text-center heading font-bold uppercase lg:mb-2 md:mt-2 sm:mb-12"
    >HappyPlants</h1>
    <p
      class="text-xl sm:text-4xl lg:text-base text-center leading-snug mb-6 lg:mb-8 w-full lg:w-2/3 mx-auto"
    >
      We love having plants all around the house, we have so many now that we've found it difficult to remember exactly how best to look after each one.
      Here's a list of plants that we have, a description about them, how best to look after them and what will make each plant a happy plant.
    </p>

    <section>
      <div
        class="flex flex-wrap mb-6 lg:mb-6 sm:mb-12 bg-white shadow-xl rounded-lg overflow-hidden"
      >
        <div class="w-full sm:w-full lg:w-1/5 sm:h-full lg:h-64">
          <g-image src="~/assets/images/houseplant-unsplash.jpg" />
        </div>
        <div class="w-full sm:w-full lg:w-4/5 px-4 py-4 flex flex-col">
          <div class="md:flex mb-2">
            <div class="flex-grow sm:w-full">
              <h2
                class="heading text-2xl md:text-3xl font-bold leading-none md:pr-0 sm:pr-6"
              >Chinese Money Plant</h2>
              <p
                class="heading sm:text-4xl lg:text-lg pb-2 text-gray-600 font-light pr-0 sm:w-full"
              >Willynoculous Peekabum</p>
            </div>
            <div class="lg:text-xl sm:text-2xl text-gray-800">
              Age:
              <span class="font-bold w-full">89 days</span>
            </div>
          </div>
          <p
            class="text-gray-800 flex-grow text-base sm:text-3xl lg:text-base mb-6"
          >This plant is really high maintanence, make sure you keep an eye on it. Only water it once every 3.45 days.</p>
          <div class="icons flex flex-wrap -mx-2">
            <div class="rounded w-1/4 h-auto bg-white pr-2 pb-2">
              <g-image
                class="border p-1 mr-4"
                alt="This is an indoor plant"
                src="~/assets/images/icons/indoor-plants.svg"
              />
            </div>
            <div class="rounded w-1/4 h-auto bg-white pr-2 pb-2">
              <g-image
                class="border p-1"
                alt="Put in direct sunlight"
                src="~/assets/images/icons/sun.svg"
              />
            </div>
            <div class="rounded w-1/4 h-auto bg-white pr-2 pb-2 relative">
              <g-image
                class="border p-2"
                alt="Put in direct sunlight"
                src="~/assets/images/icons/watering-can.svg"
              />
              <span class="absolute icon-text font-bold sm:text-2xl">2x / wk</span>
            </div>

            <div class="rounded w-1/4 h-auto bg-white pr-2 pb-2">
              <g-image
                class="border p-1"
                alt="Don't eat this plant"
                src="~/assets/images/icons/dont-eat.svg"
              />
            </div>

            <div class="rounded w-1/4 h-auto bg-white pr-2 pb-2 relative">
              <g-image
                class="border p-2"
                alt="Feed with plant food"
                src="~/assets/images/icons/flower-food.svg"
              />
              <span class="absolute icon-text font-bold sm:text-2xl">2x / wk</span>
            </div>
            <div class="rounded w-1/4 h-auto bg-white pr-2 pb-2 relative">
              <g-image
                class="border p-1"
                alt="Temperature of the room the plant should be in"
                src="~/assets/images/icons/temperature.svg"
              />
              <span class="absolute font-bold temp-text">
                <p>15</p>
                <p>25</p>
              </span>
            </div>
            <div class="rounded w-1/4 h-auto bg-white pr-2 pb-2">
              <g-image
                class="border p-1"
                alt="Put in direct sunlight"
                src="~/assets/images/icons/air-purifier.svg"
              />
            </div>
          </div>
        </div>
      </div>

      <div class="pagination text-center py-4">
        <ul>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded"
              href="#"
            >&laquo;</a>
          </li>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded"
              href="#"
            >1</a>
          </li>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded bg-green-500 text-white"
              href="#"
            >2</a>
          </li>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded"
              href="#"
            >3</a>
          </li>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded"
              href="#"
            >4</a>
          </li>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded"
              href="#"
            >5</a>
          </li>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded"
              href="#"
            >6</a>
          </li>
          <li class="inline">
            <a
              class="text-base lg:text-base sm:text-4xl no-underline lg:py-2 lg:px-4 py-2 px-3 rounded"
              href="#"
            >&raquo;</a>
          </li>
        </ul>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!"
  }
};
</script>

<style>
.white-transparent {
  background-color: rgba(255, 255, 255, 0.9);
}

.icon-text {
  font-size: 8px !important;
  width: 100%;
  bottom: 8px;
  right: 12px;
  text-align: right;
}
.plant {
  height: 475px;
}

.temp-text {
  font-size: 7px;
  width: 100%;
  bottom: 23px;
  right: 12px;
  text-align: right;
}
.pagination a.active {
  background-color: green;
  color: white;
}

.pagination a:hover:not(.active) {
  background-color: #ddd;
}
</style>
