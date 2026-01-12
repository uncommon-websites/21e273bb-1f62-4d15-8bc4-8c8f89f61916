<script lang="ts">
  import { ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-white py-32 px-4 sm:px-6 lg:px-8 font-body" id="contact">
  <div class="max-w-4xl mx-auto text-center">
    <div class="space-y-10">
      <div class="space-y-6">
        <h2 class="font-display font-bold text-5xl sm:text-6xl md:text-7xl text-gray-950 leading-tight">
          Ready to see the full picture?
        </h2>
        
        <p class="text-xl sm:text-2xl text-gray-600 leading-relaxed max-w-2xl mx-auto font-light">
          Join the waitlist. Limited spots for early access.
        </p>
      </div>
      
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4 pt-4">
        <button class="bg-primary-500 text-white px-10 py-5 rounded-xl font-semibold hover:bg-primary-600 transition-all duration-200 flex items-center justify-center gap-2 group text-lg">
          <span>Request access</span>
          <ArrowRight size={20} class="group-hover:translate-x-1 transition-transform" />
        </button>
      </div>
    </div>
  </div>
</section>
