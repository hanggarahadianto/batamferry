import Navbar from './components/shared/navbar.vue';
<template>
  <div class="">
    <SharedNavbar />

    <!-- MAIN BAR -->

    <div class="bg-white">
      <div class="px-32 py-12 flex justify-between">
        <div class="flex">
          <div
            class="bg-blue-600 h-20 w-20 justify-center justify-items-center rounded-full mr-5"
          >
            <h1 class="text-white font-bold text-5xl">1</h1>
          </div>
          <div>
            <h1 class="font-semibold">Select Schedule</h1>
            <div
              class="border-2 bg-blue-200 rounded-3xl px-4 py-2 content-center w-28"
            >
              <h1 class="text-xs font-semibold text-blue-700">In Progress</h1>
            </div>
          </div>
        </div>

        <div>
          <h1 class="font-semibold">Order Details</h1>
          <div
            class="border-2 bg-blue-200 rounded-3xl px-4 py-2 content-center w-28"
          >
            <h1 class="text-xs font-semibold text-blue-700">In Progress</h1>
          </div>
        </div>
        <div>
          <h1 class="font-semibold">Payment</h1>
          <div
            class="border-2 bg-blue-200 rounded-3xl px-4 py-2 content-center w-28"
          >
            <h1 class="text-xs font-semibold text-blue-700">In Progress</h1>
          </div>
        </div>
      </div>
    </div>

    <div class="bg-slate-100 mt-8 h-full">
      <div class="px-16 py-8">
        <!-- menu -->

        <div class="grid grid-cols-12 px-16 py-8 bg-white rounded-lg">
          <div class="col-span-8">
            <div class="flex">
              <img src="./static/images/icon.png" class="w-20" />
              <div class="ml-5 mt-2">
                <h1 class="font-semibold text-2xl">Select Departure Ferry</h1>

                <div class="flex gap-x-6">
                  <h1 class="text-sm">Batam Center</h1>
                  <h1 class="text-sm">HarbourFront</h1>
                  <h1 class="text-sm">Wed, 20 September 2023</h1>
                  <h1 class="text-sm">2 Passangers</h1>
                  <h1 class="text-sm">Economy</h1>
                </div>
              </div>
            </div>
          </div>
          <div class="flex col-span-2 py-8">
            <h1 class="text-sm">Return to Batam Center</h1>
          </div>
          <div class="col-span-2 py-4">
            <button
              class="rounded-2xl border-2 border-black px-4 py-2 bg-slate-100"
            >
              <h1 class="text-blue-900">Change Search</h1>
            </button>
          </div>
        </div>

        <!-- section FERRY NAME -->

        <div class="grid grid-cols-12 h-screen mt-10">
          <div class="col-span-4 mr-10">
            <!-- navigation -->

            <div class="py-4 flex justify-between">
              <h1 class="text-black text-4xl">Filter</h1>
              <h1 class="text-black text-2xl">Reset Filter</h1>
            </div>
            <div class="bg-white rounded-lg">
              <div
                class="bg-white px-12 py-8 rounded-md border-b-2 border-slate-200"
              >
                <h1 class="font-semibold text-2xl">Ferry Name</h1>
              </div>
              <div class="">
                <div class="px-8 py-4">
                  <div
                    class="bg-slate-200 px-8 py-4 grid rounded-lg hover:bg-slate-300 cursor-pointer"
                  >
                    <h1>Batam Fast Ferry</h1>
                  </div>
                </div>
              </div>

              <!-- section Departure -->
              <div>
                <div
                  class="bg-white px-12 py-8 rounded-md border-b-2 border-slate-200"
                >
                  <h1 class="font-semibold text-2xl mt-20">Departure</h1>
                </div>
                <div class="">
                  <div class="px-8 py-4">
                    <div
                      class="bg-slate-200 px-8 py-4 grid rounded-lg hover:bg-slate-300 cursor-pointer"
                    >
                      <h1>Night to Morning</h1>
                      <h1>00.00 - 06.00</h1>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="col-span-8">
            <div class="py-4">
              <h1>Showing 36 best ferry crossing with the best deal</h1>
            </div>

            <!-- TIcket List -->
            <div
              class="w-full px-8 py-4 bg-white mt-4 rounded-lg grid grid-cols-12"
            >
              <div class="col-span-5">
                <div class="flex">
                  <img
                    src="./static/images/logo.png"
                    class="w-14 h-10 object-contain"
                  />
                  <div class="ml-2">
                    <div class="flex">
                      <h1 class="mr-3">06.00</h1>
                      <h1>Batam Time</h1>
                    </div>
                    <div class="flex">
                      <h1>Batam Center</h1>
                      <h1>HarbourFront</h1>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-span-3 py-4">
                <h1>Batam Fast Ferry</h1>
              </div>
              <div class="col-span-3 py-4">
                <h1 class="text-orange-700 font-semibold">IDR 400.000/pax</h1>
              </div>
              <div
                class="col-span-1 bg-blue-900 px-4 py-2 flex justify-center rounded-xl w-20 h-12 mr-5"
              >
                <button>
                  <h1 class="text-white">Select</h1>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
