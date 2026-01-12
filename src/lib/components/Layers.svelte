<script lang="ts">
  import { ArrowDown } from 'lucide-svelte';
</script>

<section class="bg-gray-50 py-32 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-6xl mx-auto">
    <h2 class="font-display font-bold text-4xl sm:text-6xl md:text-7xl text-center leading-tight mb-20 text-black">
      Three layers. One framework.
    </h2>
    
    <div class="space-y-16">
      <!-- Layer 1: Your GTM -->
      <div class="bg-white border border-gray-200 p-8 sm:p-12 rounded-sm">
        <div class="flex items-start gap-6 mb-6">
          <div class="flex-shrink-0 w-12 h-12 bg-black text-white rounded-full flex items-center justify-center font-bold text-xl">
            1
          </div>
          <div class="flex-1">
            <h3 class="font-display font-bold text-3xl sm:text-4xl mb-4 text-black">
              Your GTM
            </h3>
            <p class="text-lg sm:text-xl text-gray-700 leading-relaxed mb-4">
              We diagnose what's actually blocking your growth. Not best practices. Not frameworks borrowed from companies that aren't you.
            </p>
            <p class="text-lg sm:text-xl text-black leading-relaxed font-medium">
              The specific constraint governing YOUR outcome—mapped from goal to driver to the inputs that need to change.
            </p>
          </div>
        </div>
      </div>
      
      <!-- Arrow -->
      <div class="flex justify-center">
        <ArrowDown size={32} class="text-gray-400" />
      </div>
      
      <!-- Layer 2: Your Deals -->
      <div class="bg-white border border-gray-200 p-8 sm:p-12 rounded-sm">
        <div class="flex items-start gap-6 mb-6">
          <div class="flex-shrink-0 w-12 h-12 bg-black text-white rounded-full flex items-center justify-center font-bold text-xl">
            2
          </div>
          <div class="flex-1">
            <h3 class="font-display font-bold text-3xl sm:text-4xl mb-4 text-black">
              Your Deals
            </h3>
            <p class="text-lg sm:text-xl text-gray-700 leading-relaxed mb-4">
              The same clarity, extended to your pipeline. Your sellers stop pitching and start diagnosing.
            </p>
            <p class="text-lg sm:text-xl text-black leading-relaxed font-medium">
              Every prospect gets mapped. Deals close faster because the problem is clear. Bad fits surface early.
            </p>
          </div>
        </div>
      </div>
      
      <!-- Arrow -->
      <div class="flex justify-center">
        <ArrowDown size={32} class="text-gray-400" />
      </div>
      
      <!-- Layer 3: Your Customers -->
      <div class="bg-white border border-gray-200 p-8 sm:p-12 rounded-sm">
        <div class="flex items-start gap-6 mb-6">
          <div class="flex-shrink-0 w-12 h-12 bg-black text-white rounded-full flex items-center justify-center font-bold text-xl">
            3
          </div>
          <div class="flex-1">
            <h3 class="font-display font-bold text-3xl sm:text-4xl mb-4 text-black">
              Your Customers
            </h3>
            <p class="text-lg sm:text-xl text-gray-700 leading-relaxed mb-4">
              The loop completes. Your strategy connects to your deals connects to your customers' execution.
            </p>
            <p class="text-lg sm:text-xl text-black leading-relaxed font-medium">
              One framework from your boardroom to their front lines.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
