<template>
  <div class="font-sans">
    <header class="flex items-center justify-between px-10 py-4 shadow-sm">
      <div class="flex items-center space-x-2">
        <img src="file:///C:/Users/User/Downloads/socier.svg" />
      </div>

      <nav class="hidden md:flex space-x-8 text-gray-700 font-medium">
        <a href="#" class="hover:text-blue-600">Home</a>

        <div class="relative group">
          <div class="flex items-center gap-1 cursor-pointer">
            <span class="hover:text-blue-600">Modules</span>
            <span
              class="transition-transform duration-300 group-hover:rotate-180"
              >▼</span
            >
          </div>

          <div
            class="absolute left-0 top-full pt-6 z-50 opacity-0 invisible scale-95 translate-y-2 origin-top-left transition-all duration-200 group-hover:opacity-100 group-hover:visible group-hover:scale-100 group-hover:translate-y-0"
          >
            <div
              class="opacity-0 invisible group-hover:opacity-100 group-hover:visible transition duration-200 w-[700px] bg-white shadow-xl rounded-xl p-6"
            >
              <h2 class="text-xl font-semibold mb-4">Modules</h2>

              <div class="grid grid-cols-3 gap-4">
                <div class="p-4 border rounded-lg hover:shadow-md transition">
                  <h3 class="font-semibold">Social Media</h3>
                  <p class="text-sm text-gray-500">
                    Manage all social platforms
                  </p>
                </div>

                <div class="p-4 border rounded-lg hover:shadow-md transition">
                  <h3 class="font-semibold">E-Commerce</h3>
                  <p class="text-sm text-gray-500">Manage store & orders</p>
                </div>

                <div class="p-4 border rounded-lg hover:shadow-md transition">
                  <h3 class="font-semibold">Calls</h3>
                  <p class="text-sm text-gray-500">Track and manage calls</p>
                </div>

                <div class="p-4 border rounded-lg hover:shadow-md transition">
                  <h3 class="font-semibold">Chats</h3>
                  <p class="text-sm text-gray-500">Chat system for users</p>
                </div>

                <div class="p-4 border rounded-lg hover:shadow-md transition">
                  <h3 class="font-semibold">Tickets</h3>
                  <p class="text-sm text-gray-500">Support ticket system</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <a href="#" class="hover:text-blue-600">About Us</a>
        <a href="#" class="hover:text-blue-600">Blogs</a>
        <a href="#" class="hover:text-blue-600">Contact Us</a>
      </nav>

      <div class="flex space-x-4">
        <button class="px-5 py-2 rounded-full bg-gray-200 text-gray-700">
          Login
        </button>
        <button class="px-5 py-2 rounded-full bg-blue-600 text-white">
          Register
        </button>
      </div>
    </header>

    <section
      class="grid md:grid-cols-2 gap-10 items-center px-10 py-16 bg-gray-50"
    >
      <div>
        <h1 class="text-5xl font-bold leading-tight">
          <span class="text-blue-600">Super</span>
          <span class="text-pink-500">App</span><br />
          <span class="text-gray-800">For Your Businesses</span>
        </h1>

        <p class="mt-6 text-gray-600 text-lg">
          Easily manage orders, track deliveries, handle payments, connect with
          delivery partners and grow your business all in one place.
        </p>

        <button
          class="mt-8 px-6 py-3 bg-blue-600 text-white rounded-full shadow-md hover:bg-blue-700"
        >
          Book a free trial
        </button>
      </div>

      <div class="flex justify-center">
        <img
          src="https://sociair.com/_nuxt/homeHero.B74nfndD.png"
          alt="dashboard"
          class="rounded-xl shadow-lg"
        />
      </div>
    </section>
    <StatsSection />
    <SocialHero   />
  </div> 
</template>

<script setup>
import StatsSection from './components/StatsSection.vue'
import SocialHero from './components/SocialHero.vue'
</script>