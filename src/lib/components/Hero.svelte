<script lang="ts">
  import { ArrowRight } from 'lucide-svelte';
</script>

<section class="relative bg-white py-40 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <div class="max-w-4xl mx-auto text-center">
      <div class="space-y-10">
        <div class="space-y-6">
          <h1 class="font-display font-bold text-6xl sm:text-7xl md:text-8xl text-gray-950 leading-[1.1]">
            See what's really<br/>driving your deals
          </h1>
          
          <p class="text-2xl sm:text-3xl text-gray-600 leading-relaxed max-w-3xl mx-auto font-light">
            Stop guessing. Start knowing.
          </p>
        </div>
        
        <div class="flex flex-col sm:flex-row gap-4 pt-6 justify-center">
          <button class="bg-primary-500 text-white px-10 py-5 rounded-xl font-semibold hover:bg-primary-600 transition-all duration-200 flex items-center justify-center gap-2 group text-lg">
            <span>Request early access</span>
            <ArrowRight size={20} class="group-hover:translate-x-1 transition-transform" />
          </button>
        </div>
      </div>
    </div>
  </div>
</section>
