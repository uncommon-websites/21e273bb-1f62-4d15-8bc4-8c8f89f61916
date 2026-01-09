<script>
  import { ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-white py-24 px-4 sm:px-6 lg:px-8 font-body text-center" id="contact">
  <div class="max-w-4xl mx-auto">
    <h2 class="font-display font-bold text-5xl sm:text-7xl uppercase leading-[0.9] mb-6 text-black">
      Stop defending opinions. <br /> Start testing reality.
    </h2>
    
    <p class="text-gray-600 text-lg mb-10">
      Partner with us to build shared causal models that unstall your highest-stakes deals.
    </p>
    
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 w-full sm:w-auto">
      <button class="bg-black text-white px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-800 transition-colors w-full sm:w-auto group">
        Start a conversation <ArrowRight size={16} class="group-hover:translate-x-1 transition-transform" />
      </button>
      <button class="bg-white text-black border border-gray-200 px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-50 transition-colors w-full sm:w-auto">
        See our method
      </button>
    </div>
  </div>
</section>
