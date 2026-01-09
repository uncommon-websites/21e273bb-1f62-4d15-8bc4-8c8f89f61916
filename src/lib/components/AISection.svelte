<script>
  import { GitBranch } from 'lucide-svelte';
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 font-body overflow-hidden">
  <div class="max-w-7xl mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 lg:gap-24 items-center">
      
      <!-- Text -->
      <div>
        <div class="flex items-center gap-2 mb-6">
            <div class="w-5 h-5 bg-black text-white flex items-center justify-center text-xs font-bold rounded-sm">→</div>
            <span class="text-xs font-bold tracking-widest uppercase text-gray-500">Causal Modeling</span>
        </div>

        <h2 class="font-display font-bold text-5xl sm:text-6xl uppercase leading-[0.9] mb-8 text-gray-900">
          Stop guessing. <br /> Start mapping <br /> what actually <br /> drives results.
        </h2>
        
        <p class="text-gray-600 text-lg leading-relaxed mb-8">
          Generic discovery captures what people say. Causal modeling reveals what actually happens. We build structured maps of drivers, second-order effects, and constraints—so you can test predictions instead of defending opinions.
        </p>
        
        <div class="mt-12">
            <h3 class="font-display font-bold text-xl mb-2">Testable, not theoretical</h3>
            <p class="text-gray-500 text-sm max-w-sm">Every model makes falsifiable predictions. If a driver doesn't move the outcome, the model fails. That's how you know it's real.</p>
            
            <!-- Simple progress bar graphic -->
            <div class="mt-6 flex items-center gap-2">
                <div class="h-1 w-12 bg-primary-500 rounded-full"></div>
                <div class="h-1 w-8 bg-gray-200 rounded-full"></div>
                <div class="h-1 w-20 bg-gray-200 rounded-full"></div>
            </div>
        </div>
      </div>

      <!-- Image/UI -->
      <div class="relative">
        <div class="bg-primary-500 rounded-lg p-6 sm:p-10 shadow-2xl transform rotate-1 hover:rotate-0 transition-transform duration-500">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <!-- Diagram Header -->
                <div class="bg-gray-50 border-b border-gray-100 p-4 flex items-center gap-3">
                    <div class="w-8 h-8 bg-primary-100 text-primary-600 rounded-full flex items-center justify-center">
                        <GitBranch size={16} />
                    </div>
                    <div>
                        <p class="text-sm font-bold text-gray-900">Revenue Growth Model</p>
                        <p class="text-xs text-gray-500">Key causal relationships</p>
                    </div>
                </div>
                
                <!-- Diagram Body -->
                <div class="p-6 space-y-6">
                    <div>
                        <p class="text-xs font-bold text-gray-900 mb-4">Primary Drivers:</p>
                        <div class="space-y-3">
                            <div class="flex items-center gap-2">
                                <div class="w-3 h-3 rounded-full bg-primary-500"></div>
                                <div class="h-px flex-1 bg-gray-200"></div>
                                <div class="text-xs text-gray-700">Customer retention rate</div>
                            </div>
                            <div class="flex items-center gap-2 ml-6">
                                <div class="w-2 h-2 rounded-full bg-primary-300"></div>
                                <div class="h-px flex-1 bg-gray-200"></div>
                                <div class="text-xs text-gray-600">Onboarding completion</div>
                            </div>
                            <div class="flex items-center gap-2 ml-6">
                                <div class="w-2 h-2 rounded-full bg-primary-300"></div>
                                <div class="h-px flex-1 bg-gray-200"></div>
                                <div class="text-xs text-gray-600">Feature adoption depth</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-gray-50 p-4 rounded border border-gray-100">
                        <p class="text-xs font-bold text-gray-900 mb-2">Counterintuitive insight:</p>
                        <p class="text-xs text-gray-600 leading-relaxed">
                          Increasing sales velocity by 20% actually <span class="font-bold text-gray-900">decreased</span> revenue by 8% due to poor onboarding capacity. The model predicted this—leadership didn't believe it until we tested.
                        </p>
                    </div>
                </div>
            </div>
        </div>
      </div>

    </div>
  </div>
</section>
