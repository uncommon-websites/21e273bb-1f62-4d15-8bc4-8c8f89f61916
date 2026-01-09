<script>
  import { ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-white pt-16 pb-24 px-4 sm:px-6 lg:px-8 flex flex-col items-center text-center font-body overflow-hidden">
  <h1 class="font-display font-bold text-5xl sm:text-7xl md:text-8xl tracking-tight uppercase leading-[0.9] max-w-5xl mx-auto mb-6 text-black">
    Unstall Your <br class="hidden sm:block" /> High-Stakes Deals.
  </h1>
  
  <p class="text-lg sm:text-xl text-gray-600 max-w-2xl mx-auto mb-10 text-balance leading-relaxed">
    Build shared, testable maps of how your most important outcomes are actually produced. Replace politics and assumptions with clarity your entire team can act on.
  </p>
  
  <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-16 w-full sm:w-auto">
    <button class="bg-black text-white px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-800 transition-colors w-full sm:w-auto group">
      Start a conversation <ArrowRight size={16} class="group-hover:translate-x-1 transition-transform" />
    </button>
    <button class="bg-white text-black border border-gray-200 px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-50 transition-colors w-full sm:w-auto">
      See our method
    </button>
  </div>
  
  <!-- Hero Image Container -->
  <div class="relative w-full max-w-6xl mx-auto rounded-xl overflow-hidden shadow-2xl bg-gray-100 aspect-video group">
    <!-- Placeholder Image Background -->
    <div class="absolute inset-0 bg-gray-200">
        <img src="/generated/image-business-executives-collaborating-around-1767917121945-0.webp" alt="Strategic workshop session" class="w-full h-full object-cover opacity-90" />
    </div>
    
    <!-- Overlay with causal diagram hint -->
    <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent"></div>
    
    <!-- Annotation -->
    <div class="absolute bottom-8 left-8 bg-white/90 backdrop-blur-md p-4 rounded-lg shadow-lg border border-white/20 max-w-sm text-left hidden md:block">
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 rounded-full bg-primary-100 flex items-center justify-center text-primary-600 shrink-0 font-bold text-sm">
          →
        </div>
        <div>
          <p class="text-sm font-bold text-gray-900">Shared model of account reality</p>
          <p class="text-xs text-gray-500 mt-0.5">Testable drivers, not opinions</p>
        </div>
      </div>
    </div>
  </div>
</section>
