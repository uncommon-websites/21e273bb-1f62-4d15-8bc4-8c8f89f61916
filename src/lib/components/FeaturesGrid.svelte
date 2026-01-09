<script>
  import { Target, GitBranch, Users, CheckCircle } from 'lucide-svelte';

  const methodology = [
    {
      title: "Discovery",
      icon: Target,
      color: "bg-primary-100 text-primary-600",
      items: [
        "Map key outcomes",
        "Identify stakeholders",
        "Surface assumptions",
        "Define success metrics"
      ]
    },
    {
      title: "Causal Mapping",
      icon: GitBranch,
      color: "bg-primary-100 text-primary-600",
      items: [
        "Model driver relationships",
        "Test second-order effects",
        "Map political constraints",
        "Validate with data"
      ]
    },
    {
      title: "Model Building",
      icon: Users,
      color: "bg-primary-100 text-primary-600",
      items: [
        "Construct shared view",
        "Make testable predictions",
        "Document counterintuitive insights",
        "Create reusable frameworks"
      ]
    },
    {
      title: "Activation",
      icon: CheckCircle,
      color: "bg-primary-100 text-primary-600",
      items: [
        "Align internal teams",
        "Enable buyer circulation",
        "Track leading indicators",
        "Iterate on feedback"
      ]
    }
  ];
</script>

<section class="bg-gray-50 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Header -->
    <div class="mb-20" id="method">
      <div class="flex items-center gap-2 mb-6">
        <div class="w-5 h-5 bg-black text-white flex items-center justify-center text-xs font-bold rounded-sm">→</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">Our Method</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        From stalled to moving. <span class="text-gray-500">We build structured causal models that replace fuzzy drivers with testable reality—so your team can act with confidence.</span>
      </h2>
    </div>

    <!-- Grid -->
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-x-8 gap-y-12">
      {#each methodology as phase}
        <div class="flex flex-col h-full">
          <div class="flex items-center gap-3 mb-6 pb-4 border-b border-gray-200">
            <div class={`w-8 h-8 rounded flex items-center justify-center shrink-0 ${phase.color}`}>
              <svelte:component this={phase.icon} size={16} />
            </div>
            <h3 class="font-bold text-lg">{phase.title}</h3>
          </div>
          
          <ul class="space-y-3 flex-grow">
            {#each phase.items as item}
              <li class="flex items-start gap-2 text-sm text-gray-700">
                <span class="w-1 h-1 rounded-full bg-primary-500 mt-2 shrink-0"></span>
                <span>{item}</span>
              </li>
            {/each}
          </ul>
        </div>
      {/each}
    </div>
  </div>
</section>
