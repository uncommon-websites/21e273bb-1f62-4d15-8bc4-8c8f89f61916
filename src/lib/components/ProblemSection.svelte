<script>
  import { ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-gray-950 text-white py-24 px-4 sm:px-6 lg:px-8 font-body relative overflow-hidden">
  <!-- Top Pattern -->
  <div class="absolute top-0 left-0 w-full h-24 opacity-20 pointer-events-none bg-[url('https://grainy-gradients.vercel.app/noise.svg')]"></div>
  <div class="absolute top-0 left-0 w-full h-12 opacity-20" 
       style="background-image: linear-gradient(90deg, rgba(255,255,255,0.5) 1px, transparent 1px), linear-gradient(rgba(255,255,255,0.5) 1px, transparent 1px); background-size: 4px 4px;">
  </div>
  <div class="absolute top-0 left-0 w-full h-12 bg-gradient-to-b from-gray-950/0 to-gray-950"></div>

  <!-- Bottom Pattern -->
   <div class="absolute bottom-0 left-0 w-full h-12 opacity-20" 
       style="background-image: linear-gradient(90deg, rgba(255,255,255,0.5) 1px, transparent 1px), linear-gradient(rgba(255,255,255,0.5) 1px, transparent 1px); background-size: 4px 4px;">
  </div>
  <div class="absolute bottom-0 left-0 w-full h-12 bg-gradient-to-t from-gray-950/0 to-gray-950"></div>

  <div class="max-w-7xl mx-auto relative z-10">
    <!-- Header -->
    <div class="mb-20">
      <div class="flex items-center gap-2 mb-6">
        <div class="w-5 h-5 bg-white text-black flex items-center justify-center text-xs font-bold rounded-sm">!</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-400">The Problem</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight">
        Your high-stakes deals stall, <span class="text-gray-500">not because your product is wrong, but because your stakeholders can't agree on what actually drives the outcome.</span>
      </h2>
      
      <p class="mt-8 text-sm font-bold text-gray-400 uppercase tracking-wider">Three forces that kill momentum:</p>
    </div>

    <!-- Cards Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Card 1 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="/generated/image-diverse-group-of-business-leaders-in-a-t-1767917124386-1.webp" alt="Political gridlock" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">Political gridlock</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Every stakeholder has their own narrative. Without a shared model, you're stuck mediating opinions instead of testing reality.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="/generated/image-business-professional-looking-confused-a-1767917126723-2.webp" alt="Untested assumptions" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">Untested assumptions</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Generic discovery decks capture symptoms, not causes. You're building on sand when you need bedrock.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="/generated/image-blurred-abstract-business-data-and-chart-1767917129647-3.webp" alt="Fuzzy drivers" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">Fuzzy drivers</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          "Improve efficiency" sounds good in a deck. But which lever actually moves the needle? Vague goals produce vague results.
        </p>
      </div>
    </div>
  </div>
</section>
