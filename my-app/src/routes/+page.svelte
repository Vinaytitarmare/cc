<script>
    import Navbar from "../routes/navbar/+page.svelte"
</script>
<Navbar/>
 <div class="bg-[#051016] text-white pt-40 space-y-4 w-screen  text-[[#76DEE1]]">
 
    
   <div class="max-w-md mx-auto bg-gray-800 text-white rounded-lg p-6 shadow-lg mx-4">
        <div class=" flex justify-between items-center w-[100%] mb-6">
          <h2 class="text-lg font-semibold">User Details</h2>
          <div class="bg-gray-700 p-2 rounded-full">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
              <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 9V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25V9m-6 0h18M4.5 9V19.5A2.25 2.25 0 006.75 21h10.5A2.25 2.25 0 0019.5 19.5V9M9 13.5h6m-6 3h6" />
            </svg>
          </div>
        </div>
        <div class="space-y-4 border-solid border-top-1 border-gray-800">
          <div class="flex items-center">
            <div class="w-6 h-6 bg-gray-700 rounded-full flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 11.25c-1.518 0-2.812.772-3.578 1.938a6.003 6.003 0 007.156 0A4.49 4.49 0 0012 11.25zM16.5 6a3.75 3.75 0 01-7.5 0 3.75 3.75 0 017.5 0z" />
              </svg>
            </div>
            <p class="ml-4">
              <span class="block font-medium">Name</span>
              <span class="text-gray-400">VINAY TITARMARE</span>
            </p>
          </div>
          <div class="flex items-center">
            <div class="w-6 h-6 bg-gray-700 rounded-full flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21 12c0 3.866-3.582 7-8 7s-8-3.134-8-7 3.582-7 8-7 8 3.134 8 7z" />
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 7v5.25l3.75 2.25" />
              </svg>
            </div>
            <p class="ml-4">
              <span class="block font-medium">Email</span>
              <span class="text-gray-400">vinaytitarmare420@gmail.com</span>
            </p>
          </div>
          <div class="flex items-center">
            <div class="w-6 h-6 bg-gray-700 rounded-full flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 2.25l19.5 19.5M4.5 7.5h6.75M9.75 3H6a2.25 2.25 0 00-2.25 2.25v14.25M15.75 16.5H9.75M15 12a3 3 0 01-3 3m3 3a3 3 0 01-3-3" />
              </svg>
            </div>
            <p class="ml-4">
              <span class="block font-medium">Phone</span>
              <span class="text-gray-400">Not provided</span>
            </p>
          </div>
          <div class="flex items-center">
            <div class="w-6 h-6 bg-gray-700 rounded-full flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 2.25a6.75 6.75 0 00-6.75 6.75v6a6.75 6.75 0 0013.5 0v-6A6.75 6.75 0 0012 2.25z" />
                <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 15l.75 2.25M15 15l-.75 2.25M12 6v5.25" />
              </svg>
            </div>
            <p class="ml-4">
              <span class="block font-medium">Address</span>
              <span class="text-gray-400">Not provided</span>
            </p>
          </div>
        </div>
        <div class="mt-6">
          <p class="text-sm text-gray-400">Joined on January 18, 2025</p>
        </div>
        <div class="mt-6 flex justify-evenly space-x-4">
          <button class="bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-4 rounded">Edit Profile</button>
          <button class="bg-red-600 hover:bg-red-700 text-white font-medium py-2 px-4 rounded">Sign Out</button>
        </div>
      </div> 

      <!-- component 2 -->
       <div class="max-w-md bg-gray-800 mx-2 text-white rounded-lg p-6 shadow-lg">
        <div class="flex justify-between items-center mb-6">
          <div>
            <h2 class="text-lg font-semibold">Carbon Credit Portfolio</h2>
            <p class="text-sm text-gray-400">Overview</p>
          </div>
          <div class="bg-gray-700 p-2 rounded-full">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
              <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 12.75l1.5 1.5m0 0l3-3m-3 3v7.5M12 6.75v-3a2.25 2.25 0 00-4.5 0v3m7.5-3.75H20.25m0 0V7.5M15 4.5v6m3.75 3.75h-3m0 0l-3 3m3-3v-7.5M9.75 15.75l-3-3" />
            </svg>
          </div>
        </div>
        <div class="text-center mb-6">
          <h1 class="text-4xl font-semibold">0</h1>
          <p class="text-gray-400 text-sm">Tons of CO₂ Equivalent 
            <span class="inline-block">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 inline-block">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 9.75V4.5m0 0a2.25 2.25 0 00-2.25 2.25M12 4.5a2.25 2.25 0 012.25 2.25M8.25 20.25h7.5m0 0a2.25 2.25 0 002.25-2.25M8.25 20.25a2.25 2.25 0 01-2.25-2.25" />
              </svg>
            </span>
          </p>
        </div>
        <div class="mb-6">
          <div class="flex justify-between items-center mb-1">
            <p class="text-sm font-medium text-gray-400">Portfolio Growth</p>
            <p class="text-sm text-blue-400">+15% YTD</p>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-2">
            <div class="bg-blue-500 h-2 rounded-full" style="width: 50%"></div>
          </div>
        </div>
        <div class="grid grid-cols-2 gap-4 mb-6">
          <div class="bg-gray-700 p-4 rounded-lg text-center">
            <p class="text-sm text-gray-400">Monthly Average</p>
            <p class="text-lg font-semibold">0</p>
          </div>
          <div class="bg-gray-700 p-4 rounded-lg text-center">
            <p class="text-sm text-gray-400">Target Achievement</p>
            <p class="text-lg font-semibold">0%</p>
          </div>
        </div>
        <div class="flex items-center mb-6">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 text-green-400">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.75v7.5m0 0L9 12.75m3 1.5L15 12m-6 4.5v2.25M6 6h12" />
          </svg>
          <p class="text-sm text-green-400 ml-2">15% Increase This Quarter</p>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 ml-auto text-gray-400">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 7.5v9m0-9a5.25 5.25 0 015.25 5.25m0 0H8.25m9-5.25A5.25 5.25 0 008.25 7.5m9 9H8.25m9 0a5.25 5.25 0 01-5.25 5.25" />
          </svg>
        </div>
        <div class="sm:flex sm:flex-row justify-between space-x-4">
          <button class="bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-4 rounded flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
            </svg>
            Purchase More Credits
          </button>
          <button class="bg-gray-700 hover:bg-gray-600 text-white font-medium py-2 px-4 rounded">View History</button>
          <button class="bg-gray-700 hover:bg-gray-600 text-white font-medium py-2 px-4 rounded flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
            </svg>
            Refresh
          </button>
        </div>
      </div> 

      <!-- component 3 -->
      <div class="max-w-lg mx-auto bg-gray-800 text-white rounded-lg p-6 shadow-lg">
        <div class="flex justify-between items-center mb-4">
          <div>
            <h2 class="text-lg font-semibold">EcoTech Solutions's Achievements</h2>
            <p class="text-sm text-gray-400">Celebrating sustainable development</p>
          </div>
          <div class="bg-blue-700 text-white text-sm py-1 px-2 rounded-full flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 mr-1">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
            </svg>
            Eco-Champion
          </div>
        </div>
      
        <div class="flex space-x-4 mb-6">
          <button class="bg-blue-700 text-white py-2 px-4 rounded-lg flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
            </svg>
            Green Pioneer
          </button>
          <button class="bg-gray-700 text-gray-400 py-2 px-4 rounded-lg flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
            </svg>
            Water Saver
          </button>
          <button class="bg-gray-700 text-gray-400 py-2 px-4 rounded-lg flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
            </svg>
            Energy Expert
          </button>
          <button class="bg-gray-700 text-gray-400 py-2 px-4 rounded-lg flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
            </svg>
            Air Champion
          </button>
        </div>
      
        <div class="bg-gray-700 p-4 rounded-lg mb-6">
          <div class="flex justify-between items-center mb-4">
            <div class="flex items-center space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 text-blue-400">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
              </svg>
              <h3 class="text-blue-400 font-medium">Green Pioneer</h3>
            </div>
            <div class="bg-gray-800 py-1 px-2 rounded-full text-yellow-400 text-sm flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 mr-1">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
              </svg>
              1250 pts
            </div>
          </div>
          <p class="text-sm text-gray-300 mb-4">
            Achieved significant reduction in carbon footprint. This award recognizes individuals or organizations that have made substantial efforts to minimize their carbon emissions through innovative practices and technologies.
          </p>
          <div class="mb-4">
            <p class="text-sm text-gray-400">Progress</p>
            <div class="w-full bg-gray-800 rounded-full h-2">
              <div class="bg-blue-500 h-2 rounded-full" style="width: 75%"></div>
            </div>
          </div>
          <p class="text-sm text-gray-400">Achieved on: 12/1/2023</p>
        </div>
      
        <div class="flex justify-end">
          <button class="bg-blue-700 text-white py-2 px-4 rounded-lg flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m9-9H3" />
            </svg>
            View All Achievements
          </button>
        </div>
      </div>
     
      
    
</div> 