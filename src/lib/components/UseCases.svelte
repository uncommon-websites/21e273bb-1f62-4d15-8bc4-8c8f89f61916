<script lang="ts">
  import { Rocket, TrendingUp, RefreshCw } from 'lucide-svelte';
</script>

<section class="bg-gray-50 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Section header -->
    <div class="max-w-3xl mx-auto text-center mb-20">
      <h2 class="font-display font-bold text-4xl sm:text-5xl md:text-6xl text-gray-950 mb-6 leading-tight">
        Land. Expand. Retain.
      </h2>
      <p class="text-xl text-gray-600 leading-relaxed">
        One framework that grows with your relationship.
      </p>
    </div>

    <!-- Use cases grid -->
    <div class="space-y-16">
      <!-- Land -->
      <div class="grid lg:grid-cols-2 gap-12 items-center">
        <div class="space-y-6">
          <div class="flex items-center gap-4">
            <div class="w-14 h-14 bg-primary-500 rounded-xl flex items-center justify-center flex-shrink-0">
              <Rocket class="text-white" size={26} />
            </div>
            <h3 class="font-display font-bold text-3xl text-gray-950">
              Land with diagnostics
            </h3>
          </div>
          <p class="text-lg text-gray-600 leading-relaxed">
            Start with a strategic GTM diagnostic for leadership teams. We map the forces governing your outcomes and give you a clear view of what's working and what's not.
          </p>
          <p class="text-gray-600 leading-relaxed">
            No generic playbooks. No fluff. Just sharp insights your team can act on immediately.
          </p>
        </div>
        <div>
          <img 
            src="/generated/image-diverse-group-of-business-professionals--1767929570689-3.webp" 
            alt="Strategic planning session"
            class="w-full h-auto rounded-xl"
          />
        </div>
      </div>

      <!-- Expand -->
      <div class="grid lg:grid-cols-2 gap-12 items-center">
        <div class="order-2 lg:order-1">
          <img 
            src="/generated/image-professional-sales-leader-presenting-to--1767929568582-2.webp" 
            alt="Deal-level mapping"
            class="w-full h-auto rounded-xl"
          />
        </div>
        <div class="space-y-6 order-1 lg:order-2">
          <div class="flex items-center gap-4">
            <div class="w-14 h-14 bg-primary-500 rounded-xl flex items-center justify-center flex-shrink-0">
              <TrendingUp class="text-white" size={26} />
            </div>
            <h3 class="font-display font-bold text-3xl text-gray-950">
              Expand into deals
            </h3>
          </div>
          <p class="text-lg text-gray-600 leading-relaxed">
            Once aligned at the top, we cascade the same framework down to deal level. Your sales org gains pinpoint focus on what actually moves each opportunity forward.
          </p>
          <p class="text-gray-600 leading-relaxed">
            No more guessing. Your reps know exactly which lever to pull in every conversation.
          </p>
        </div>
      </div>

      <!-- Retain -->
      <div class="grid lg:grid-cols-2 gap-12 items-center">
        <div class="space-y-6">
          <div class="flex items-center gap-4">
            <div class="w-14 h-14 bg-primary-500 rounded-xl flex items-center justify-center flex-shrink-0">
              <RefreshCw class="text-white" size={26} />
            </div>
            <h3 class="font-display font-bold text-3xl text-gray-950">
              Retain through platform
            </h3>
          </div>
          <p class="text-lg text-gray-600 leading-relaxed">
            The framework doesn't disappear when we leave. Our platform embeds it into your daily workflow, keeping your strategy alive and actionable.
          </p>
          <p class="text-gray-600 leading-relaxed">
            Lasting impact that compounds over time, not consultant dependency.
          </p>
        </div>
        <div>
          <img 
            src="/generated/image-business-leader-reviewing-analytics-and--1767929577145-6.webp" 
            alt="Platform in action"
            class="w-full h-auto rounded-xl"
          />
        </div>
      </div>
    </div>
  </div>
</section>
