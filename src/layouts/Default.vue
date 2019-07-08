<template>
  <div class="flex flex-col min-h-screen">
<header class="w-full bg-gray-100 mb-16 p-8">
      <div class="container mx-auto max-w-3xl flex justify-between items-center ">
      <g-link class="font-bold" to="/">{{ $static.metaData.siteName }}</g-link>
      <nav>
        <g-link class="hover:underline" to="/">Home</g-link>
        <g-link class="ml-8 hover:underline" to="/about">About</g-link>
      </nav>
      </div>
    </header>    
    <section class="container mx-auto max-w-3xl leading-normal px-8 flex-grow">
    <slot/>
    </section>
    <footer class="w-full bg-gray-100 mt-16 p-8">
      <div class="container mx-auto max-w-3xl flex justify-between items-center ">
      <g-link class="font-bold" to="/">{{ $static.metaData.siteName }}</g-link>
      <div>
        <g-link class="hover:underline" to="/">Home</g-link>
        <g-link class="ml-8 hover:underline" to="/about">About</g-link>
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

