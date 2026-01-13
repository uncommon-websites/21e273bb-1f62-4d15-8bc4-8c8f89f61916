<script lang="ts">
  import { Search, Map, Repeat } from 'lucide-svelte';
</script>

<section class="bg-white py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Section header -->
    <div class="max-w-3xl mx-auto text-center mb-20">
      <h2 class="font-display font-bold text-4xl sm:text-5xl md:text-6xl text-gray-950 mb-6 leading-tight">
        How it works
      </h2>
      <p class="text-xl text-gray-600 leading-relaxed">
        Three steps to clarity across your entire revenue engine.
      </p>
    </div>

    <!-- Steps -->
    <div class="grid md:grid-cols-3 gap-12 lg:gap-16">
      <!-- Step 1 -->
      <div class="relative">
        <div class="space-y-6">
          <div class="w-16 h-16 bg-primary-500 rounded-xl flex items-center justify-center">
            <Search class="text-white" size={28} />
          </div>
          <div class="space-y-3">
            <div class="text-sm font-semibold text-primary-600 tracking-wide uppercase">
              Step 1
            </div>
            <h3 class="font-display font-bold text-2xl" style="color: #012c21;">
              Diagnose your GTM
            </h3>
            <p class="text-gray-600 leading-relaxed">
              We start with a strategic diagnostic that maps the forces governing your outcomes. No fluff, just clarity on what's working and what's not.
            </p>
          </div>
        </div>
        <!-- Connector line (hidden on mobile) -->
        <div class="hidden md:block absolute top-8 left-full w-full h-0.5 bg-gray-200 -translate-x-1/2"></div>
      </div>

      <!-- Step 2 -->
      <div class="relative">
        <div class="space-y-6">
          <div class="w-16 h-16 bg-primary-500 rounded-xl flex items-center justify-center">
            <Map class="text-white" size={28} />
          </div>
          <div class="space-y-3">
            <div class="text-sm font-semibold text-primary-600 tracking-wide uppercase">
              Step 2
            </div>
            <h3 class="font-display font-bold text-2xl text-gray-950">
              Map to your deals
            </h3>
            <p class="text-gray-600 leading-relaxed">
              The same framework cascades down to deal level. Your reps gain pinpoint focus on what actually moves each opportunity forward.
            </p>
          </div>
        </div>
        <!-- Connector line (hidden on mobile) -->
        <div class="hidden md:block absolute top-8 left-full w-full h-0.5 bg-gray-200 -translate-x-1/2"></div>
      </div>

      <!-- Step 3 -->
      <div class="space-y-6">
        <div class="w-16 h-16 bg-primary-500 rounded-xl flex items-center justify-center">
          <Repeat class="text-white" size={28} />
        </div>
        <div class="space-y-3">
          <div class="text-sm font-semibold text-primary-600 tracking-wide uppercase">
            Step 3
          </div>
          <h3 class="font-display font-bold text-2xl text-gray-950">
            Embed the system
          </h3>
          <p class="text-gray-600 leading-relaxed">
            Our platform keeps the framework alive in your daily workflow. The clarity persists long after we're gone.
          </p>
        </div>
      </div>
    </div>

    <!-- Image -->
    <div class="mt-20 max-w-5xl mx-auto">
      <img 
        src="/generated/image-professional-sales-leader-presenting-to--1767929568582-2.webp" 
        alt="Framework in action"
        class="w-full h-auto rounded-xl"
      />
    </div>
  </div>
</section>
