---
layout: post
title: 'Firm low-carbon technologies'
date: 2021-05-20
description: My thoughts and summary of a great paper on the role of firm, low-carbon technologies in our future energy mix.
tags: [Climate tech, Power sector]
---
I read a great 2018 paper, [The Role of Firm Low-Carbon Electricity Resources in Deep Decarbonization of Power Generation](https://www.sciencedirect.com/science/article/pii/S2542435118303866), about the optimal energy mix in a world with a deeply decarbonized power sector. Here's my summary, along with some thoughts and comments.

### Summary
- Under all scenarios the authors modeled (including low and high scenarios for electrification, long duration energy storage, transmission), the presence of firm low-carbon resources lowered the cost of deeply decarbonizing the power sector.
	- Decarbonization without firm resources is more expensive because you need to greatly overbuild renewables and storage.
	- Firm resources can lower the cost of decarbonization **even if the firm resources have higher levelized cost than renewables**. This was the key takeaway for me. It's not just about the direct cost, but also the value the resource provides in terms of when and where the electricity is generated.
- We should maintain flexibility in R&D and policy, and avoid limiting ourselves to specific technologies, because the future is uncertain and the optimal energy mix varies based on different technology costs.
- Batteries and demand response are not a perfect substitute for firm low-carbon resources.
- Cheap enough long duration energy storage (on the order of days) could serve as a firm low-carbon resource. More research is needed.
	- The way they modeled hypothetical long duration energy storage, it didn't play a big role in the energy mix.

<img src="/img/firm_low_carbon_resources.jpg" width="450">
 
### Thoughts and comments
It's a breath of fresh air to read a nuanced and balanced take on this, rather than anti-nuclear sentiments or arguments about why we should use 100% wind and solar.

That said, I can't help but feel like a lot of the findings were quite intuitive. The more we constrain out options, the more expensive things get. The stricter we set our emissions limits, the more expensive things get. The fact that the results are robust to varying levels of transmission is helpful though.

#### **The limitation of cost projections**
My main qualm with this paper, which is more of a qualm with macro-level modeling in general, is that it's highly sensitive to assumptions and cost projections. And a big assumption in this paper is the cost of batteries.

The authors assumed long duration energy storage for 24 hours at $89-357/kWh, or 100 hours at $73.5-294/kWh. Given these inputs, they find that long duration storage doesn't play a big role in the energy mix, and has a negligible effect on total costs.

Granted, this was published in 2018. Three years later, Li-ion batteries are projected to reach $100/kWh or less, and the ARPA-E DAYS program, which funds R&D in long duration storage, is targeting costs far below that. If cheaper long duration storage were included in the model, I'm sure the optimal energy mix would change.

#### **What's the right narrative here?**
The authors state that because firm low-carbon resources would reduce the cost of decarbonization, we should consider them in our future energy mix, and also increase R&D and policy support. I'm all for this.

The challenge is that the majority of the firm low-carbon resources considered in the paper – specifically geothermal and various types of CCS – do not exist at commercial scale yet. The authors assume that we will get there someday, and I really hope we do, but it's not guaranteed. 

On the other hand, we already know how to build and deploy solar, wind, storage, and even transmission (permitting issues aside) at scale. Relying solely on these technologies becomes expensive as we hit the asymptote of zero emissions, but do we need to reach zero? We'll likely have other parts of the economy where it's really hard to reach zero emissions (e.g. aviation, industrial heat, etc.).

If we're willing to accept low levels of emissions in the power sector (e.g. 1-10 g CO2/kWh. For context, US power sector emissions intensity in 2017 was 436.6 g CO2/kWh) and combine that with direct air capture, then building a grid centered on renewables and storage, which we already know how to build at scale, suddenly makes more sense.

So what's the right narrative here? I don't think there's a clear answer. The same data can be used to tell a story of "we need firm low-carbon resources to get to zero emissions" or a story of "we don't yet have the firm low-carbon resources we need to get to zero emissions cost-effectively, but we can get pretty darn close using technologies we already have."
