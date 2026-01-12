<script lang="ts">
  import { Eye, Users, Target, Zap } from 'lucide-svelte';
</script>

<section class="bg-white py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Section header -->
    <div class="max-w-3xl mx-auto text-center mb-20">
      <h2 class="font-display font-bold text-4xl sm:text-5xl md:text-6xl text-gray-950 mb-6 leading-tight">
        Built for leaders who demand clarity
      </h2>
      <p class="text-xl text-gray-600 leading-relaxed">
        No more guessing. No more generic playbooks. Just precision.
      </p>
    </div>

    <!-- Features grid -->
    <div class="grid md:grid-cols-2 gap-12 lg:gap-16">
      <!-- Feature 1 -->
      <div class="space-y-6 group cursor-default">
        <div class="w-14 h-14 bg-primary-100 rounded-xl flex items-center justify-center transition-all duration-300 group-hover:scale-110 group-hover:bg-primary-200">
          <Eye class="text-primary-600 transition-colors duration-300 group-hover:text-primary-700" size={26} />
        </div>
        <div class="space-y-3">
          <h3 class="font-display font-bold text-2xl text-gray-950 transition-colors duration-300 group-hover:text-primary-600">
            See what's really in the way
          </h3>
          <p class="text-gray-600 leading-relaxed text-lg">
            Our diagnostic framework reveals the hidden forces blocking your revenue. You'll know exactly where to focus—and what to ignore.
          </p>
        </div>
      </div>

      <!-- Feature 2 -->
      <div class="space-y-6 group cursor-default">
        <div class="w-14 h-14 bg-primary-100 rounded-xl flex items-center justify-center transition-all duration-300 group-hover:scale-110 group-hover:bg-primary-200">
          <Users class="text-primary-600 transition-colors duration-300 group-hover:text-primary-700" size={26} />
        </div>
        <div class="space-y-3">
          <h3 class="font-display font-bold text-2xl text-gray-950 transition-colors duration-300 group-hover:text-primary-600">
            Align your entire team
          </h3>
          <p class="text-gray-600 leading-relaxed text-lg">
            One framework from boardroom to front line. No more misalignment between leadership, sales, and customers.
          </p>
        </div>
      </div>

      <!-- Feature 3 -->
      <div class="space-y-6 group cursor-default">
        <div class="w-14 h-14 bg-primary-100 rounded-xl flex items-center justify-center transition-all duration-300 group-hover:scale-110 group-hover:bg-primary-200">
          <Target class="text-primary-600 transition-colors duration-300 group-hover:text-primary-700" size={26} />
        </div>
        <div class="space-y-3">
          <h3 class="font-display font-bold text-2xl text-gray-950 transition-colors duration-300 group-hover:text-primary-600">
            Built for your reality
          </h3>
          <p class="text-gray-600 leading-relaxed text-lg">
            Not another cookie-cutter methodology. We map your specific market, buyers, and constraints.
          </p>
        </div>
      </div>

      <!-- Feature 4 -->
      <div class="space-y-6 group cursor-default">
        <div class="w-14 h-14 bg-primary-100 rounded-xl flex items-center justify-center transition-all duration-300 group-hover:scale-110 group-hover:bg-primary-200">
          <Zap class="text-primary-600 transition-colors duration-300 group-hover:text-primary-700" size={26} />
        </div>
        <div class="space-y-3">
          <h3 class="font-display font-bold text-2xl text-gray-950 transition-colors duration-300 group-hover:text-primary-600">
            Lasting impact
          </h3>
          <p class="text-gray-600 leading-relaxed text-lg">
            The framework lives on through our platform. Clarity that persists long after we're gone.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
