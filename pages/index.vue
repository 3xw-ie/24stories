<template>
  <main class="w-screen min-h-screen px-4 py-8 sm:px-4 sm:py-16 md:p-32  bg-red-lightest font-serif antialiased">
    <img src="/24-stories-logo.svg" alt="24 Stories Logo" class="w-32">
    <section class="mt-8 max-w-sm">
      <p class="my-4">A new community for marketing professionals, students &amp; businesses in Cork.</p>
      <p class="my-4">8 events, 4 workshops, 2 conferences.</p>
      <p class="my-4">First events announced 24th October 2018.</p>
    </section>
    <section class="mt-10">
      <h3>Interested in learning more? Enter your email.</h3>
      <form class="my-4 flex" action="https://formcarry.com/s/UAju9_Dbyfd" method="post">
        <input type="email" name="email" placeholder="hotshot@marketer.ie" class="rounded-l w-full max-w-xs py-3 px-3 sm:px-4 border-red-darker">
        <input type="hidden" name="_gotcha">
        <button type="submit" class="rounded-r py-3 px-4 bg-grey-dark text-white">Submit</button>
      </form>
    </section>
    <section class="mt-10">
      <h3>Spaces are limited. <nuxt-link to="/register" class="text-inherit">Register now and secure your spot.</nuxt-link></h3>
    </section>
  </main>
</template>

<script>
export default {
  components: {
    //
  }
}
</script>
