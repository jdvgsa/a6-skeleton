<script>
import Header from "../lib/components/Header.svelte";
import SportCards from "../lib/components/SportCards.svelte";
import Footer from "../lib/components/Footer.svelte";
</script>

<Header />

<div class="text-center">
  <h1 class="pb-6 pt-3 text-6xl">Want to learn more about sports?</h1>
  <p class="pb-5 pt-3 max-w-prose mx-auto text-lg">
        Whether your heart beats for the electrifying pace of the NBA, the grace of the NHL, or the adrenaline of the NFL, dive into the exhilarating world of sports. Every game is a captivating saga of skill, strategy, and triumph, inviting you to explore the incredible stories woven within the fabric of athletic prowess and teamwork. You have the power to choose the sports narrative that resonates with your passion.</p>
</div>

<div>
	<SportCards />
</div>

<div>
  <Footer />
</div>