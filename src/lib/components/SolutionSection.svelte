<script lang="ts">
  import { Target, Layers, Zap } from 'lucide-svelte';
</script>

<section class="bg-gray-50 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <div class="grid lg:grid-cols-2 gap-16 items-center">
      <!-- Left: Image -->
      <div class="overflow-hidden rounded-xl">
        <img 
          src="/generated/image-business-leader-reviewing-analytics-and--1767929577145-6.webp" 
          alt="Clear strategic insights"
          class="w-full h-auto rounded-xl transition-transform duration-500 hover:scale-105"
        />
      </div>

      <!-- Right: Content -->
      <div class="space-y-8">
        <div class="space-y-4">
          <h2 class="font-display font-bold text-4xl sm:text-5xl text-gray-950 leading-tight">
            One framework. Total clarity.
          </h2>
          <p class="text-xl text-gray-600 leading-relaxed">
            drvrs maps the forces that govern your outcomes—from your GTM strategy down to your customers' front lines.
          </p>
        </div>

        <!-- Benefits -->
        <div class="space-y-6">
          <div class="flex gap-4 group cursor-default">
            <div class="flex-shrink-0">
              <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center transition-all duration-300 group-hover:scale-110 group-hover:bg-primary-200">
                <Target class="text-primary-600 transition-colors duration-300 group-hover:text-primary-700" size={20} />
              </div>
            </div>
            <div>
              <h3 class="font-display font-semibold text-lg text-gray-950 mb-2 transition-colors duration-300 group-hover:text-primary-600">
                See what's really in the way
              </h3>
              <p class="text-gray-600 leading-relaxed">
                Our diagnostic framework reveals the hidden forces blocking your revenue—so you know exactly where to focus.
              </p>
            </div>
          </div>

          <div class="flex gap-4 group cursor-default">
            <div class="flex-shrink-0">
              <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center transition-all duration-300 group-hover:scale-110 group-hover:bg-primary-200">
                <Layers class="text-primary-600 transition-colors duration-300 group-hover:text-primary-700" size={20} />
              </div>
            </div>
            <div>
              <h3 class="font-display font-semibold text-lg text-gray-950 mb-2 transition-colors duration-300 group-hover:text-primary-600">
                Cascades through every level
              </h3>
              <p class="text-gray-600 leading-relaxed">
                One framework that works from boardroom to front line. Your entire team operates from the same playbook.
              </p>
            </div>
          </div>

          <div class="flex gap-4 group cursor-default">
            <div class="flex-shrink-0">
              <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center transition-all duration-300 group-hover:scale-110 group-hover:bg-primary-200">
                <Zap class="text-primary-600 transition-colors duration-300 group-hover:text-primary-700" size={20} />
              </div>
            </div>
            <div>
              <h3 class="font-display font-semibold text-lg text-gray-950 mb-2 transition-colors duration-300 group-hover:text-primary-600">
                Built for your reality
              </h3>
              <p class="text-gray-600 leading-relaxed">
                Not another generic methodology. We map your specific market, buyers, and constraints.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
