<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Koblox
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Montserrat', sans-serif;
      background-color: white;
    }
    /* Custom scrollbar for game list */
    .games-scroll::-webkit-scrollbar {
      height: 8px;
    }
    .games-scroll::-webkit-scrollbar-thumb {
      background-color: #c00;
      border-radius: 4px;
    }
  </style>
 </head>
 <body class="flex flex-col min-h-screen">
  <!-- Navbar -->
  <nav class="bg-red-600 text-white flex items-center justify-between px-6 py-3 shadow-md">
   <div class="flex items-center space-x-3">
    <img alt="Roblox Logo" class="h-8 w-auto" src="https://media.tenor.com/HO1YAH0_iMcAAAAj/roblox-logo.gif"/>
    <span class="text-2xl font-extrabold tracking-wide">
       Koblox
    </span>
   </div>
   <div class="hidden md:flex space-x-6 font-semibold text-lg">
    <a class="hover:underline" href="#">
     Games
    </a>
    <a class="hover:underline" href="#">
     Avatar Shop
    </a>
    <a class="hover:underline" href="#">
     Create
    </a>
    <a class="hover:underline" href="#">
     Kobux
    </a>
   </div>
   <div class="flex items-center space-x-4">
    <input class="rounded px-3 py-1 text-black focus:outline-none" placeholder="Search" type="text"/>
    <button class="bg-white text-red-600 font-bold px-4 py-1 rounded hover:bg-gray-100 transition">
     Login
    </button>
    <button class="bg-white text-red-600 font-bold px-4 py-1 rounded hover:bg-gray-100 transition">
     Sign Up
    </button>
   </div>
  </nav>
  <!-- Hero Section -->
  <header class="bg-red-600 text-white py-20 px-6 text-center">
   <h1 class="text-5xl font-extrabold mb-4">
    Play, Create, and Share
   </h1>
   <p class="text-xl max-w-2xl mx-auto mb-8">
    Join millions of players and creators worldwide in the ultimate virtual universe.
   </p>
   <button class="bg-white text-red-600 font-bold px-8 py-3 rounded-lg hover:bg-gray-100 transition">
    Start Playing
   </button>
  </header>
  <!-- Games Section -->
  <section class="max-w-7xl mx-auto px-6 py-12">
   <h2 class="text-3xl font-extrabold mb-8 text-red-700">
    Popular Games
   </h2>
   <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8 games-scroll overflow-x-auto">
    <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-2xl transition cursor-pointer">
     <img alt="Game 1 thumbnail" class="w-full h-40 object-cover" height="225" src="https://media1.tenor.com/m/2tLubUSj6x8AAAAC/adopt-me-roblox.gif" width="400"/>
     <div class="p-4">
      <h3 class="font-bold text-lg text-red-700 mb-1">
       Adopt Me!
      </h3>
      <p class="text-gray-600 text-sm">
       Adopt pets, decorate your home, and explore a magical world.
      </p>
     </div>
    </div>
    <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-2xl transition cursor-pointer">
     <img alt="Game 2 thumbnail" class="w-full h-40 object-cover" height="225" src="https://media1.tenor.com/m/KG358b1gEd8AAAAC/vsv.gif" width="400"/>
     <div class="p-4">
      <h3 class="font-bold text-lg text-red-700 mb-1">
       Brookhaven 🏡RP
      </h3>
      <p class="text-gray-600 text-sm">
       Live your dream life in this role-playing game with friends.
      </p>
     </div>
    </div>
    <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-2xl transition cursor-pointer">
     <img alt="Game 3 thumbnail" class="w-full h-40 object-cover" height="225" src="https://media1.tenor.com/m/DLstRxhw3G8AAAAC/roblox-roblox-meme.gif" width="400"/>
     <div class="p-4">
      <h3 class="font-bold text-lg text-red-700 mb-1">
       Tower of Hell
      </h3>
      <p class="text-gray-600 text-sm">
       Race to the top of a challenging obby tower with no checkpoints.
      </p>
     </div>
    </div>
    <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-2xl transition cursor-pointer">
     <img alt="Game 4 thumbnail" class="w-full h-40 object-cover" height="225" src="https://media1.tenor.com/m/-ttowc7ufEoAAAAC/murder-mystery-logo-gif.gif" width="400"/>
     <div class="p-4">
      <h3 class="font-bold text-lg text-red-700 mb-1">
       Murder Mystery 2
      </h3>
      <p class="text-gray-600 text-sm">
       Solve the mystery or be the murderer in this thrilling game.
      </p>
     </div>
    </div>
   </div>
  </section>
  <!-- Footer -->
  <footer class="bg-red-700 text-red-100 py-6 mt-auto">
   <div class="max-w-7xl mx-auto px-6 text-center text-sm select-none">
    © 2025 Roblox Inspired. All rights reserved.
   </div>
  </footer>
 </body>
</html>
