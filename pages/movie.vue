<template>
      <div class="w-full min-h-screen relative bg-black overflow-y-auto text-left text-white font-lato">
        
        <!-- Navbar Section -->
        <div class="fixed top-0 left-0 w-full h-[90px] bg-red-600 flex items-center justify-between z-50">
          <div class="container mx-auto flex items-center justify-between px-6">
            <div class="text-3xl font-extrabold flex items-center justify-center w-[170px] h-full">
              Flixera
            </div>
            <nav class="flex space-x-8 text-xl">
              <a href="#" class="hover:underline">Home</a>
              <a href="#" class="hover:underline">Event</a>
              <a href="#" class="hover:underline">Membership</a>
              <a href="#" class="hover:underline">Registration</a>
              <a href="#" class="hover:underline">Login</a>
            </nav>
          </div>
        </div>
    
      <!-- Background Image Section -->
      <div class="mt-[90px] w-full max-w-[1440px] mx-auto h-[766px] relative">
      <!-- Background Image -->
      <img class="w-full h-full object-cover" alt="Background Image" src="assets/media/image 78.png" />
      
      <!-- Play Button Section -->
      <div class="absolute inset-0 flex flex-col justify-center items-center z-20">
      <button class="bg-transparent border-4 border-white rounded-full shadow-lg hover:bg-gray-700 transition duration-300 flex items-center justify-center w-16 h-16 z-10">
      <div class="bg-red-500 w-full h-full rounded-full flex items-center justify-center">
            <!-- Play SVG Icon -->
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-8 h-8 text-white" viewBox="0 0 16 16">
            <path d="M6.271 4.055a.5.5 0 0 0-.5.867l4.5 2.5a.5.5 0 0 0 0-.866l-4.5-2.5z"/>
            <path d="M6 3.05c-.793 0-1.427.647-1.437 1.44l-.001 7.04c-.01.795.635 1.441 1.437 1.441.803 0 1.438-.646 1.439-1.441v-7.04c.001-.793-.636-1.44-1.439-1.44z"/>
            </svg>
      </div>
      </button>
      <!-- Watch Movies Text -->
            <div class="absolute inset-0 flex flex-col justify-center items-center mt-24 z-20">
                  <p class="mt-6 text-2xl font-bold text-white">Watch Movies</p>
            </div>
      </div>
      </div>

        
        <!-- Movie Details Section -->
        <div class="w-full max-w-[1171px] mx-auto px-6 py-12 text-2xl">
          <div class="relative w-full h-auto">
            <h1 class="text-5xl tracking-tight font-semibold text-white drop-shadow-lg">
              Fast & Furious 7
            </h1>
            <div class="flex space-x-6 mt-6">
              <span class="font-semibold text-xl border border-white px-2 py-1">18+</span>
              <span class="font-semibold text-xl">2hr 10min</span>
              <span class="font-semibold text-xl">2015</span>
              <span class="font-semibold text-xl">Action</span>
            </div>
            <p class="mt-4 text-lg text-gray-400">
              Deckard Shaw berusaha membalas dendam atas kematian adiknya terhadap Dominic Toretto dan keluarganya. 
              Dominic dan seluruh kru berada dalam bahaya, sekali lagi.
            </p>
          </div>
        </div>
    
        <!-- Trailer & Extra Section -->
        <div class="w-full max-w-[1171px] mx-auto px-6 py-12">
          <h2 class="text-3xl font-medium capitalize mb-4">Trailer & Ekstra</h2>
          <img class="w-full max-w-md h-auto object-cover" alt="Trailer Thumbnail" src="/assets/media/trailer.png" />
        </div>
    
        <!-- Recommendations Section -->
        <div class="w-full max-w-[1165px] mx-auto px-6 py-12 text-center">
          <h2 class="text-3xl font-medium capitalize mb-8">Rekomendasi Untukmu</h2>
          <div class="grid grid-cols-3 gap-8">
            <img class="w-full h-auto object-cover" alt="Mencuri Raden Saleh" src="assets/media/image 79.png" />
            <img class="w-full h-auto object-cover" alt="Trap" src="assets/media/image 80.png" />
            <img class="w-full h-auto object-cover" alt="13 Bom Jakarta" src="assets/media/image 81.png" />
            <img class="w-full h-auto object-cover" alt="Movie Poster 4" src="assets/media/image 88.png" />
            <img class="w-full h-auto object-cover" alt="Movie Poster 5" src="assets/media/image 83.png" />
            <img class="w-full h-auto object-cover" alt="Movie Poster 6" src="assets/media/image 84.png" />
            <img class="w-full h-auto object-cover" alt="Movie Poster 7" src="assets/media/image 85.png" />
            <img class="w-full h-auto object-cover" alt="Movie Poster 8" src="assets/media/image 86.png" />
            <img class="w-full h-auto object-cover" alt="Movie Poster 9" src="assets/media/image 87.png" />
          </div>
        </div>  
      </div>
    </template>
    