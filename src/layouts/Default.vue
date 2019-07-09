<template>
  <div class="flex flex-col min-h-screen">

<header class="w-full bg-white border-b border-gray-500 px-8 py-4 sticky top-0">
      <div class="container mx-auto max-w-5xl flex justify-between items-center ">
      <g-link class="font-bold" to="/">{{ $static.metaData.siteName }}</g-link>
      <nav>
        <g-link class="hover:underline" to="/about">About</g-link>
        <g-link class="ml-8 hover:underline" to="/contact">Contact</g-link>
      </nav>
      </div>
    </header>   
 
    <slot/>

    <footer class="w-full bg-white border-t border-gray-500 mt-16 px-8 py-4">
      <div class="container mx-auto max-w-5xl flex justify-between items-center ">
      <g-link class="font-bold" to="/">{{ $static.metaData.siteName }}</g-link>
      <div>
        <g-link class="hover:underline" to="/about">About</g-link>
        <g-link class="ml-8 hover:underline" to="/contact">Contact</g-link>
      </div>
      </div>
    </footer>

</div>
</template>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

