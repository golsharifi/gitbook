---
description: The LCOE approach
---

# Cost of Electricity

{% hint style="info" %}
The Levelized Cost of Electricity ($$LCOE$$, commonly expressed in $$USD/kWh$$) represents the average revenue per unit of electricity generated that would be required to recover the costs of building and to operate an energy source during an assumed financial life and duty cycle.
{% endhint %}

Key inputs to calculating the $$LCOE$$ include capital costs, fuel, or material costs, fixed and variable operations and maintenance (O\&M) costs, financing costs, and an assumed utilization rate for each plant type. The importance of each of these factors varies across technologies.

In this case, for now, all monetary values within the $$LCOE$$ are expressed in FIAT currencies, so it is needed to explore FIAT independence for those values.

According to the International Energy Agency (IEA), the $$LCOE$$ is the principal tool for comparing the plant-level unit costs of different baseload technologies over their operating lifetimes. The $$LCOE$$ indicates the economic costs of generic technology, not the financial costs of a specific project in a particular market. Due to the equality between discounted average costs and the stable remuneration over lifetime electricity production, which is at its heart, $$LCOE$$ is in spirit closer to the costs of electricity production in regulated electricity markets with stable tariffs, for which it was developed, than to the variable prices in deregulated markets. By adjusting the discount rate for the implicit cost of price volatility, the $$LCOE$$ concept can, in principle, also be applied in the context of deregulated markets.

The real discount rate, _r,_ used for discounting costs and benefits is stable, the same for all technologies, and does not vary during the project's lifetime under consideration. A 3% discount rate (corresponding approximately to the "social cost of capital"), a 7% discount rate (corresponding approximately to the cost of capital of a large utility in a deregulated or restructured market), and a 10% discount rate (corresponding approximately to cost of capital in an environment with relatively higher risks) can be used. Nominal discount rates would be higher, reflecting inflation. While in practice, the cost of capital, and hence the relevant discount rate, may vary between different technologies, assuming an identical cost of capital for all technologies allows comparing the costs across technologies and regions.

With annual discounting, the $$LCOE$$ calculation begins with the following equation expressing the equality between the present value of the sum of discounted revenues and the present value of the sum of discounted costs, including payments to capital providers. The subscript, _t,_ denotes the year the sale of production or the cost disbursement occurs. The summation extends from the start of construction preparation to the end of dismantling, which includes the discounted value at that time of future waste management costs. All variables are real, i.e., net of inflation. In the Eq. 1_,_ on the left-hand side, one finds the discounted sum of benefits and on the right-hand side the discounted sum of costs.

$$
P_{M W h}(1+r)^{-t}=(Capital_{t}+{O\&M}_{t}+{Fuel}_{t}+{Carbon}_{t}+D_{t})(1+r)^{-t} \quad \text {Eq.} 1
$$

{% hint style="info" %}
Where;

$$P_{M W h}$$ is the constant lifetime remuneration to the supplier for electricity

$$M W h$$ is the amount of electricity produced annually in $$M W h$$

$$(1+r)^{-t}$$ is the real discount rate corresponding to the cost of capital

$$Capital_{t}$$ is the total capital construction costs in year $$t$$

$$O \& M_{t}$$ is the operation and maintenance costs in year $$t$$

$$Fuel_{t}$$ is the Fuel costs in year $$t$$

$$Carbon_{t}$$ is the Carbon costs in year $$t$$

$$D_{t}$$ is the decommissioning and waste management costs in year $$t$$
{% endhint %}



Because $$P_{M W h}$$ is a constant over time, it can be brought out of the summation, and that equation can be transformed into Eq. 2:

$$
L C O E=\frac{\left(\text { Capital }_{t}+O \& M_{t}+\text { Fuel }_{t}+\text { Carbon }_{t}+D_{t}\right) *(1+r)^{-t}}{M W h(1+r)^{-t}} \quad \text { Eq. } 2
$$

Where this constant is defined as the Levelized cost of electricity ($$L C O E$$).

Eq. 2 is the formula used to calculate average lifetime Levelized costs based on the costs for investment, operation and maintenance, fuel or material, carbon emissions, and decommissioning and dismantling provided by OECD countries and selected non-member countries.

Some confusion could arise if Eq. 2 were taken out of context.

In Eq. 2, it looks as if are being discounted. Because $$P_{M W h}$$ is a constant, it can be taken out of the summation of revenues over the energy source's lifetime, and both sides of the Eq. 1 can be divided by this summation. It is not the $$M W h$$ that are being discounted; it is the revenue from those $$M W h$$ that are discounted. Revenue today has more value to the purchaser/owner/operator than revenue tomorrow. It is not output per se that is discounted, but its economic value. This is standard procedure in cost-benefit accounting.

According to the Open Energy Information (OEI), another approach to deal with the LCOE formula is the following:

$$
\begin{gathered}
L C O E=\frac{\text { Capital Cost CRF }\left(1-T D_{P V}\right)}{8,760 \text { Capacity Factor }(1-T)}+\frac{\text { Fixed O\&M }}{8760 \text { Capacity Factor }} \\\\
+\frac{\text { Variable O\&M }}{10^{3} \frac{k W h}{M W h}}+\frac{\text { Fuel Price Heat Rate }}{10^{6} \frac{B T U}{\text { mmBTU }}}
\end{gathered} \quad \text { Eq. } 3
$$

{% hint style="info" %}
Where;

$$Capital\ Cost\ (USD/{kWh})$$ is the cost of the energy source

$$CRF$$ is the capital expenditure

$$T$$ is the tax rate paid (applied after depreciation credits)

$$D_{PV}$$ is the present value of depreciation

$$8,760$$ is the $$hours$$ in a $$year$$

$$Capacity\ Factor\ (\%)$$ is the yearly average percentage of power as a fraction of capacity

$$O \& M\ (U S D / k W h)$$ is the fixed operations and maintenance cost of the plant per capacity in $$U S D / k W h$$

$$O\&M\ (USD/MWh)$$ is the variable operations and maintenance cost of the source per capacity in $$U S D / k W$$

$$Fuel\ Price\ (USD /MMBtu)$$ is the fuel cost of the plant

$$Heat\ Rate\ (USD/MMBtu)$$ is the efficiency of the power plant in converting fuel into electricity
{% endhint %}

Having presented the two approaches above (Eq. 2 and Eq. 3), it is essential to mention some technical limitations around the$$LCOE$$.

The LCOE analysis cannot cover all considerations and losses due to its standardized nature. This means that since these projects operate over several decades, it is difficult to fully estimate the changes in variable costs such as the cost of fuel and the dramatic fluctuations in price. In less regulated markets with more dynamic pricing models, the $$LCOE$$ is not accurate. While maintenance costs are included, other considerations over the lifetime of an energy source can affect the stability of the price of the generated output.

Overall, the $$LCOE$$ is considered as static analysis to measure the average cost to produce electricity or, in other words, the minimum price that an entity has to set up to recover its initial investment; this is relevant for the suppliers targeted by our blockchain. In other words, the $$LCOE$$ does not account for externalities such as technological developments, raw materials/inputs, air pollution, and climate change. Therefore, the recommendation is to estimate conservative values for the $$LCOE$$ and develop periodic adjustments to improve the entity's production line performance over time. Commonly, that can be measured by frequently performing a "sensitive analysis" to deal with unexpected events that could affect the production line.

Assuming that an $$LCOE$$ formula could be used, however many authors support the use of the $$LCOE$$ because they consider that it also shows that recent radical criticisms of the $$LCOE$$ approach, denying credibility and usefulness, rely on assumptions concerning technology costs and interest rates, which are practically irrelevant, and from a methodical perspective, on a misconception of the time value of electricity generation.
