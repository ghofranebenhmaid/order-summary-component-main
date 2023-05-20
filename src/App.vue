

<template>
  <main
    class="h-screen w-full bg-[#E0E8FF] bg-[url('./assets/pattern-background-desktop.svg')] bg-no-repeat bg-contain flex items-center justify-center text-sm"
  >
    <div class="rounded-3xl md:shadow w-96 mx-6 overflow-hidden">
      <div>
        <a href="#">
          <img
            class="object-cover"
            src="./assets/illustration-hero.svg"
            alt="card 1"
          />
        </a>
      </div>

      <div class="px-7 py-4  text-center bg-white">
        <h1 class="font-bold text-2xl text-gray-900 mb-5 mt-7 truncate">
          Order Summary
        </h1>

        <div class="text-md text-gray-500 px-3">
          You can now listen to millions of songs, audiobooks, and podcasts on
          any device anywhere you like!
        </div>

        <div
          class="flex justify-between items-center  my-6 p-4 bg-gray-100 rounded-2xl"
        >
          <div class="flex">
            <img
              class="object-cover px-3"
              src="./assets/icon-music.svg"
              alt="card 2"
            />
            <div>
              <h4 class="font-bold text-ms">Annual Plan</h4>
              <p class="text-gray-500">$59.99/year</p>
            </div>
          </div>
          <div>
            <a
              href="#"
              class="py-2 text-indigo-500 hover:text-indigo-700 text-black font-medium text-sm hover:underline "
              >Change
            </a>
          </div>
        </div>
        <button
          class="rounded-xl bg-indigo-700 drop-shadow-xl hover:bg-indigo-500 hover:drop-shadow-2xl text-white text-sm w-full py-3 "
        >
          Proceed to Payment
        </button>

        <div class="mt-6 mb-7">
          <a
            href="#"
            class="py-2   text-black font-medium text-sm hover:underline"
            >Cancel Order
          </a>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped></style>
