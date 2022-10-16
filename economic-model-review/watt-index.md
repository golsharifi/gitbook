# Watt Index

To measure and track the energy consumption and the value of the electricity price, the Watt Index can be represented by a Paasche Price Index following Eq. 19 as:

$$
\text { Watt Index }=\frac{\left[E_{i}(t) p_{i}(t)\right]}{\left[E_{i}(t) p_{i}(0)\right]} \times 100 \quad \text { Eq. } 19
$$

{% hint style="info" %}
Where:

$$E_i(t)$$acts as the quantity of energy traded at the observation period.

$$p_{i}(t)$$ is the price of electricity at the observation period.

$$p_{i}(0)$$ is the price of the electricity at the base period.
{% endhint %}

This type of index commonly uses a base year of 100, with periods of higher price levels shown by an index greater than 100 and periods of lower price levels by indexes lower than 100. The numerator of the Watt Index is the total expenditures of energy trading at the observation period using the observation period price and quantities. At the same time, the denominator is the total expenditures of energy traded using base period prices and observation period quantities. Therefore, the Watt Index considers consumption patterns using current quantities (current weightings).

![](<../.gitbook/assets/VOLT Flowchart (white).png>)

Given the scheme shown above and economic modeling assumptions described over this assessment, it is reasonable to summarize the stakeholders' roles, incentives, and formal equations that take place within the system as follows:

| **Stakeholder (Role)**                      | **Reward**                | **Formal Specification**                                                                        | **Additional information**                                                                                                                                                                      |
| ------------------------------------------- | ------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Consumer<br>(B<em>uyer)</em></p>         | kWh usage                 | __$$\frac{U S D}{k W h}=\frac{\text { Watt tokens }}{k W h}$$                                   | <p>Supply-demand mechanism<br></p>                                                                                                                                                              |
| <p>Supplier<br>(<em>Utility)</em></p>       | Energy Delivery           | $$\underline{p}=L C O E=\frac{I_{0}}{\underline{M} U P V}+\frac{\underline{C}}{\underline{M}}$$ | $$\begin{array}{ll} D_{m}(t) & =a-b \times p(t) ; \quad a, b>0 \\ S_{m}(t) & =-c+d \times p(t) ; \quad c, d>0 \\ p^{\prime}(t) & =\alpha\left[D_{m}(t)-S_{m}(t)\right] ; \alpha>0 \end{array}$$ |
| <p>Purchaser<br>(St<em>aking)</em></p>      | Watt tokens               | $$D_{i}(t)=\left[T_{i}(t) p_{i}(t)\right](1+r)^{t}$$                                            | Speculative behavior                                                                                                                                                                            |
| <p>Broker<br>(N<em>DB Hub)</em></p>         | Fixed fee per transaction | $$R_{i}(t)=\underline{c}\left[E_{i}(t) p_{i}(t)\right]$$                                        | Trading behavior                                                                                                                                                                                |
| <p>Government<br><em>(Policymaker)</em></p> | Market Growth             | $$\Delta\left[E_{i}(t) p_{i}(t)\right]$$                                                        | Potential tax policy                                                                                                                                                                            |

