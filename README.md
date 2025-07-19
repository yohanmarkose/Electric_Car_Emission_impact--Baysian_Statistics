# Are Electric Cars truely green? Emission Impact Analysis

### Why I am Doing this

**Does The introduction of electric cars actually help reduce carbon emission?**

Electric cars are the rage these days. They’re sleek, modern, and, let’s admit it, kinda cool. Even better, they come with the promise of saving the environment—double win, right?

But wait! There’s a plot twist. While EVs shine in reducing tailpipe emissions, critics argue that their "eco-friendliness" might just be a well-marketed illusion. The skeptics say, “Sure, no fumes on the road, but have you seen the carbon cost of making those batteries and components? It’s a monster compared to combustion engines!”

So, who’s right? Are EVs truly the knights in shining armor for our planet, or is their green badge a little tarnished?

We’re rolling up our sleeves and diving into the data to uncover the truth. Using the power of data science, we’ll cut through the noise, and come to a conclusion—at least for ourselves.

Why argue when the data can do the talking?

### Analysis

[View Electric Vehicle Emission Analysis Notebook](./EV_Impact_Analysis.ipynb)

### What I did

* Developed a comprehensive Bayesian statistical model using Gamma and Student-T distributions to analyze the impact of electric vehicle adoption on China's transportation emissions from 2000-2035
* Implemented change-point detection algorithms to identify emission trend shifts, successfully pinpointing 2005-2009 as the initial EV introduction period and 2022 as the lithium production surge inflection point
* Built predictive models using linear regression and interpolation to forecast emissions based on China's EV market penetration targets (3% by 2020, 8% by 2025, 20% by 2030), revealing potential emission reductions of 188+ million tons by 2030
* Conducted multi-factor analysis incorporating automobile production and lithium mining data, uncovering that increased battery production could offset EV emission benefits, providing actionable insights for sustainable transportation policy
* Utilized advanced statistical techniques including Highest Density Intervals (HDI) and effect size calculations to quantify emission changes with 94% confidence, demonstrating significant environmental impact

### The Result

In searching for why the reason could be, we found that **China's lithium consumption for lithium-ion batteries increased sharply after 2015**, driven by the national new energy policy and market demand. This explains the sleight increase in emission after the year 2016. 

Moreover, **Lithium demand in china exceeded supply in both 2021 and 2022, despite a 180% increase in production since 2017**. This means that there was a much higher rate of production of lithium batteries between the years 2020 and 2023, and **our model seems to catch that change and reflect the same**

The model also seems to suggest that **if we continue the production of batteries in the same rate with the same extraction methods, China will find it difficult to reduce its carbon emission even if they are doing so to introduce more EV's into the road**. So it is not so easy to blindly conclude that introducing EV is the way to the reduce emissions.

Sure it definitely helps in the same, However, we see that it is as important to keep other factors in mind to reduce the emission. New methods and practices for Lithium mining have been slowly introduced, but it is not yet nearly significant.

Researchers across the globe are trying to design new manufacturing processes or new battery chemistries that can work with more readily available, environmentally-friendly materials, but these technologies aren’t yet available on a wide scale.

### **Possible Solutions**

- Use renewable energy: Use renewable energy sources for electricity
- Use direct lithium extraction: Use specialized filters to separate lithium from brine, which can reduce the footprint of traditional brine operations
- Recycle lithium batteries: Recycling lithium batteries can help reduce the demand for lithium. 

“If we don't change how we make materials, how we make chemicals, how we manufacture, everything will essentially stay the same,” `Shao-Horn`
