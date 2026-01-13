<script lang="ts">
  import { AlertCircle, TrendingDown, Users } from 'lucide-svelte';
</script>

<section class="bg-white py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Section header -->
    <div class="max-w-3xl mx-auto text-center mb-20">
      <h2 class="font-display font-bold text-4xl sm:text-5xl md:text-6xl mb-6 leading-tight" style="color: #012c21;">
        You have data. You lack clarity.
      </h2>
      <p class="text-xl text-gray-600 leading-relaxed">
        Dashboards, playbooks, and opinions everywhere. But no clear answer to what's actually blocking revenue.
      </p>
    </div>

    <!-- Problem grid -->
    <div class="grid md:grid-cols-3 gap-8 lg:gap-12">
      <!-- Problem 1 -->
      <div class="space-y-4 group cursor-default">
        <div class="w-12 h-12 bg-gray-100 rounded-lg flex items-center justify-center transition-all duration-300 group-hover:bg-primary-100 group-hover:scale-110">
          <TrendingDown class="text-gray-700 transition-colors duration-300 group-hover:text-primary-600" size={24} />
        </div>
        <h3 class="font-display font-semibold text-xl text-gray-950 transition-colors duration-300 group-hover:text-primary-600">
          Too many metrics, no meaning
        </h3>
        <p class="text-gray-600 leading-relaxed">
          Your CRM is full of data points, but you're still guessing which lever to pull. Numbers without context are just noise.
        </p>
      </div>

      <!-- Problem 2 -->
      <div class="space-y-4 group cursor-default">
        <div class="w-12 h-12 bg-gray-100 rounded-lg flex items-center justify-center transition-all duration-300 group-hover:bg-primary-100 group-hover:scale-110">
          <Users class="text-gray-700 transition-colors duration-300 group-hover:text-primary-600" size={24} />
        </div>
        <h3 class="font-display font-semibold text-xl text-gray-950 transition-colors duration-300 group-hover:text-primary-600">
          Misaligned teams
        </h3>
        <p class="text-gray-600 leading-relaxed">
          Leadership has one view, sales has another, and customers experience something else entirely. The disconnect kills deals.
        </p>
      </div>

      <!-- Problem 3 -->
      <div class="space-y-4 group cursor-default">
        <div class="w-12 h-12 bg-gray-100 rounded-lg flex items-center justify-center transition-all duration-300 group-hover:bg-primary-100 group-hover:scale-110">
          <AlertCircle class="text-gray-700 transition-colors duration-300 group-hover:text-primary-600" size={24} />
        </div>
        <h3 class="font-display font-semibold text-xl transition-colors duration-300 group-hover:text-primary-600" style="color: #012c21;">
          Generic playbooks don't work
        </h3>
        <p class="text-gray-600 leading-relaxed">
          You've outgrown cookie-cutter methodologies. Your market is unique, your buyers are sophisticated, and you need precision.
        </p>
      </div>
    </div>

    <!-- Image -->
    <div class="mt-20 max-w-5xl mx-auto overflow-hidden rounded-xl">
      <img 
        src="/generated/image-business-team-collaborating-around-a-whi-1767929566065-1.webp" 
        alt="Team collaborating on strategy"
        class="w-full h-auto rounded-xl transition-transform duration-500 hover:scale-105"
      />
    </div>
  </div>
</section>
