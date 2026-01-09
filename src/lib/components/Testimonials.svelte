<script>
  const testimonials = [
    {
      quote: "We had a $2M deal stuck for six months—everyone had opinions, nobody had proof. Drvrs built a causal model that got our exec team and the buyer's CFO on the same page in two weeks.",
      author: "Sarah K.",
      role: "VP Revenue, Enterprise SaaS",
      image: "/generated/image-confident-revenue-leader-presenting-to-a-1767917132285-4.webp"
    },
    {
      quote: "The model they built wasn't just for one deal—it became our playbook for the entire vertical. We're closing similar accounts 40% faster now because we finally understand what actually drives the outcome.",
      author: "Marcus T.",
      role: "CRO, B2B Platform",
      image: "/generated/image-professional-male-executive-in-business--1767917134518-5.webp"
    },
    {
      quote: "Drvrs doesn't give you generic discovery questions. They help you map the real drivers, test second-order effects, and build something your buyer can actually use to get internal buy-in. That's the difference.",
      author: "Jennifer L.",
      role: "Head of Sales, Healthcare Tech",
      image: "/generated/image-professional-woman-in-healthcare-or-tech-1767917136946-6.webp"
    }
  ];
</script>

<section class="bg-gray-50 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Header -->
    <div class="mb-20" id="results">
      <div class="flex items-center gap-2 mb-6">
        <div class="w-5 h-5 bg-black text-white flex items-center justify-center text-xs font-bold rounded-sm">✓</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">Results That Matter</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        From stalled to closed. <span class="text-gray-500">Revenue leaders choose Drvrs when the stakes are high and the path forward is unclear.</span>
      </h2>
    </div>

    <!-- Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      {#each testimonials as t}
        <div class="bg-white p-8 rounded-sm shadow-sm border border-gray-100 flex flex-col h-full">
          <div class="w-12 h-12 rounded-full overflow-hidden mb-6 bg-gray-200">
            <img src={t.image} alt={t.author} class="w-full h-full object-cover grayscale" />
          </div>
          <p class="text-gray-900 text-lg font-medium leading-relaxed mb-8 flex-grow">"{t.quote}"</p>
          <div class="border-t border-gray-100 pt-4 mt-auto">
            <p class="font-bold text-xs uppercase tracking-wider text-gray-900">{t.author}</p>
            <p class="text-[10px] font-bold uppercase tracking-wider text-gray-400 mt-1">{t.role}</p>
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
