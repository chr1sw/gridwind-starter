<template>
  <Layout>
    <div class="bg-cover bg-center w-full h-96 flex flex-col justify-center items-center hero">
      <div class="md:text-5xl text-2xl text-black font-bold mb-8 px-8">This is some bold marketing copy</div>
      <button
        class="focus:outline-none hover:bg-black hover:text-white bg-white font-bold text-xl text-black px-4 py-2 shadow rounded">
        <g-link to="/contact">
          Call To Action</g-link>
      </button>
    </div>
    <div class="container mx-auto max-w-3xl leading-relaxed px-8 mt-16 flex-grow">
      <h1 class="font-bold text-3xl mb-4">Hello, world!</h1>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus quam, provident, odit harum officiis id
        sed
        iste doloribus corrupti vel similique quas nihil! Placeat consequuntur harum ducimus ipsam quae quam?
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quae in sit, rerum officiis, amet voluptatum sint
        quia
        omnis sed facilis, modi nam qui eveniet ipsum aliquam nisi commodi repellendus?
      </p>
      <g-image class="my-10 object-cover object-top h-64" src="../assets/images/hero2.jpg" />
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus quam, provident, odit harum officiis id
        sed
        iste doloribus corrupti vel similique quas nihil! Placeat consequuntur harum ducimus ipsam quae quam?
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quae in sit, rerum officiis, amet voluptatum sint
        quia
        omnis sed facilis, modi nam qui eveniet ipsum aliquam nisi commodi repellendus?
      </p>
      <g-image class="my-10 object-cover h-64" src="../assets/images/hero4.jpg" />
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus quam, provident, odit harum officiis id
        sed
        iste doloribus corrupti vel similique quas nihil! Placeat consequuntur harum ducimus ipsam quae quam?
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quae in sit, rerum officiis, amet voluptatum sint
        quia
        omnis sed facilis, modi nam qui eveniet ipsum aliquam nisi commodi repellendus?
      </p>
      <g-image class="my-10 object-cover h-64" src="../assets/images/hero5.jpg" />
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus quam, provident, odit harum officiis id
        sed
        iste doloribus corrupti vel similique quas nihil! Placeat consequuntur harum ducimus ipsam quae quam?
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quae in sit, rerum officiis, amet voluptatum sint
        quia
        omnis sed facilis, modi nam qui eveniet ipsum aliquam nisi commodi repellendus?
      </p>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>

<style>
.hero {
  background-image: url(../assets/images/hero3.jpg);
}
</style>

