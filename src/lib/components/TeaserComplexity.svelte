<script lang="ts">
  import { UserX, FileText, HelpCircle, Monitor, DollarSign, Zap } from 'lucide-svelte';
  
  const complexities = [
    {
      icon: UserX,
      text: "Your champion could take another job",
      color: "bg-gray-900 border-gray-800",
      iconBg: "bg-gray-800/50",
      iconColor: "text-gray-300"
    },
    {
      icon: FileText,
      text: "Legal definitely has 47 red lines for you",
      color: "bg-gray-900 border-gray-800",
      iconBg: "bg-gray-800/50",
      iconColor: "text-gray-300"
    },
    {
      icon: HelpCircle,
      text: "The CFO who you've never met will have questions",
      color: "bg-gray-900 border-gray-800",
      iconBg: "bg-gray-800/50",
      iconColor: "text-gray-300"
    },
    {
      icon: Monitor,
      text: "Odds are IT security will need another demo",
      color: "bg-gray-900 border-gray-800",
      iconBg: "bg-gray-800/50",
      iconColor: "text-gray-300"
    },
    {
      icon: DollarSign,
      text: "Someone's budget will get frozen until Q3",
      color: "bg-gray-900 border-gray-800",
      iconBg: "bg-gray-800/50",
      iconColor: "text-gray-300"
    },
    {
      icon: Zap,
      text: "A competitor just offered half your price",
      color: "bg-gray-900 border-gray-800",
      iconBg: "bg-gray-800/50",
      iconColor: "text-gray-300"
    }
  ];
</script>

<section class="relative bg-gray-950 py-24 px-4 sm:px-6 lg:px-8 font-body overflow-hidden">
  <!-- Subtle background pattern -->
  <div class="absolute inset-0 opacity-5">
    <div class="absolute inset-0" style="background-image: radial-gradient(circle at 2px 2px, white 1px, transparent 0); background-size: 32px 32px;"></div>
  </div>
  
  <div class="max-w-5xl mx-auto relative">
    <div class="text-center space-y-12">
      <h2 class="font-display font-bold text-4xl sm:text-5xl text-white leading-tight">
        Because it's a miracle any deal closes at all
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5 pt-6">
        {#each complexities as complexity, i}
          <div 
            class={[
              'group relative p-6 rounded-xl border transition-all duration-300 hover:scale-105 hover:-translate-y-1',
              complexity.color
            ].join(' ')}
            style="animation-delay: {i * 100}ms;"
          >
            <!-- Icon container -->
            <div class={[
              'w-12 h-12 rounded-lg flex items-center justify-center mb-4 transition-all duration-300 group-hover:scale-110',
              complexity.iconBg
            ].join(' ')}>
              <svelte:component this={complexity.icon} size={24} class={complexity.iconColor} />
            </div>
            
            <!-- Text -->
            <p class="text-gray-200 text-base leading-relaxed font-medium">
              {complexity.text}
            </p>
            
            <!-- Subtle glow on hover -->
            <div class="absolute inset-0 rounded-xl opacity-0 group-hover:opacity-100 transition-opacity duration-300 pointer-events-none" 
                 style="background: radial-gradient(circle at 50% 0%, {complexity.iconColor.replace('text-', 'rgb(var(--color-')}20, transparent 70%);"></div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
