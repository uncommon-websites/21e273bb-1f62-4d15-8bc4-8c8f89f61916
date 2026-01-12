<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import TeaserValue from '$lib/components/TeaserValue.svelte';
  import TeaserComplexity from '$lib/components/TeaserComplexity.svelte';
  import FooterCTA from '$lib/components/FooterCTA.svelte';
  import FooterSimple from '$lib/components/FooterSimple.svelte';
</script>

<div class="min-h-screen bg-white">
  <Header />
  <main>
    <Hero />
    <TeaserValue />
    <TeaserComplexity />
    <FooterCTA />
  </main>
  <FooterSimple />
</div>

