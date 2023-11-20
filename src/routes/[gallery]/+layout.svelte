<script>
  import Header from "../../lib/components/Header.svelte";
  import NbaTeams from "../../lib/components/NbaTeams.svelte";
  import Footer from "../../lib/components/Footer.svelte";
  </script>
  <Header />
  <h1 class="text-6xl font-bold text-center hover:text-blue-500 transition-colors duration-300 pt-5 pb-5 underline cursor-pointer">The current top NBA teams</h1>
  <NbaTeams />

  <Footer />

  <!-- <slot /> -->