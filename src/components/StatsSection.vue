<template>
    <section class="w-full py-12 bg-white">
      <div class="max-w-5xl mx-auto px-6">
        <div class="grid grid-cols-1 md:grid-cols-3 divide-y md:divide-y-0 md:divide-x divide-gray-200">
  
          <!-- Sales Growth -->
          <div class="flex items-center gap-4 px-8 py-6">
            <div class="flex-shrink-0 w-14 h-14 rounded-2xl bg-orange-50 flex items-center justify-center">
              <!-- Bar chart icon -->
              <svg class="w-7 h-7 text-orange-400" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
                <rect x="3" y="12" width="4" height="8" rx="1"/>
                <rect x="10" y="7" width="4" height="13" rx="1"/>
                <rect x="17" y="3" width="4" height="17" rx="1"/>
              </svg>
            </div>
            <div>
              <p class="text-sm text-gray-500 font-medium">Sales Growth</p>
              <p class="text-3xl font-bold text-orange-500 mt-0.5">
                <span ref="salesCount">99</span>%
              </p>
            </div>
          </div>
  
          <!-- Active Users -->
          <div class="flex items-center gap-4 px-8 py-6">
            <div class="flex-shrink-0 w-14 h-14 rounded-2xl bg-pink-50 flex items-center justify-center">
              <!-- User icon -->
              <svg class="w-7 h-7 text-pink-400" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
                <circle cx="12" cy="8" r="4"/>
                <path d="M4 20c0-4 3.6-7 8-7s8 3 8 7"/>
              </svg>
            </div>
            <div>
              <p class="text-sm text-gray-500 font-medium">Active Users</p>
              <p class="text-3xl font-bold text-pink-500 mt-0.5">
                <span ref="usersCount">1000</span>+
              </p>
            </div>
          </div>
  
          <!-- Happy Clients -->
          <div class="flex items-center gap-4 px-8 py-6">
            <div class="flex-shrink-0 w-14 h-14 rounded-2xl bg-blue-50 flex items-center justify-center">
              <!-- People/group icon -->
              <svg class="w-7 h-7 text-blue-400" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
                <circle cx="9" cy="8" r="3"/>
                <path d="M2 20c0-3.3 3.1-6 7-6s7 2.7 7 6"/>
                <circle cx="17" cy="8" r="3"/>
                <path d="M22 20c0-3.3-2.1-6-5-6"/>
              </svg>
            </div>
            <div>
              <p class="text-sm text-gray-500 font-medium">Happy Clients</p>
              <p class="text-3xl font-bold text-blue-500 mt-0.5">
                <span ref="clientsCount">2000</span>+
              </p>
            </div>
          </div>
  
        </div>
      </div>
    </section>
  </template>
  
  