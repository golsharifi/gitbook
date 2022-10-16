# Supply-Demand Mechanism

From a basic economic perspective, the price $$P(t)$$ and the quantity $$Q(t)$$ are derived from supply $$S(t)$$ and demand $$D(t)$$. With the efficient market assumption, the price can be set by relative strength between demand and supply (Eq. 11):

$$
P(t)=\frac{D_{m}(t)}{S_{m}(t)} \quad \text { Eq. } 11
$$

When demand is greater than supply, a higher price is expected and vice versa. This price model, despite being very simple, accurately captures this relationship. It can be further expanded to include momentum, user valuation, and other factors that will affect service price. Quantity of unit service traded on the network at time _t_ is the minimum between net new demand and supply. After all, no transactions will take place with unmet demand or supply. This can be more realistic with a slippage later since not all matching supply and demand can find each other in the market. Nonetheless, this has been taken care of by the efficient market assumption where supply always meets demand. As such, we can write the quantity in Eq. 12 as:

$$
Q(t)=\left[D_{m}(t), S_{m}(t)\right] \quad \text { Eq. } 12
$$

Regarding the target items mentioned in the background section, that ratio would be the given price for the consumers (the price of electricity), and a market signal to measure suppliers' revenue ($$P(t) \geq LCOE$$).

Overall, this ratio is a reasonable metric that can be improved by using well-known formulas for both demand and supply curves, building a dynamic model based on a demand excess given that we are developing a highly speculative token blockchain model in which the token purchasers will contribute to its scarcity by removing them from circulation.

The following equations could represent that market mechanism:

$$
\begin{array}{lll}
D_{m}(t)=a-b \times p(t) & a, b>0 & \text { Eq. } 13 \\
S_{m}(t)=-c+d \times p(t) & c, d>0 & \text { Eq. } 14 \\
p^{\prime}(t)=\alpha\left[D_{m}(t)-S_{m}(t)\right] & \alpha>0 & \text { Eq. } 15
\end{array}
$$

Eq. 13 tells us that at each instant, the quantity demanded decreases linearly with the price $$p=p(t)$$. Similarly, the opposite effect can be observed in the Eq. 14.

Eq. 15 states that the instantaneous price change, represented by the derivative $$p^{\prime}(t)$$, is directly proportional (where $$\alpha$$ is the constant of proportionality) to the excess demand. From Eq. 15, note that it must be:

> * If there is more demand than supply, that is, if $$D m(t)-\operatorname{Sm}(t)>0$$, as $$\alpha>0$$, the instantaneous price change will be positive: $$p^{\prime}(t)>0$$, which tells us, as is to be expected, prices will tend to grow.
> * If there is more supply than demand, that is, if $$\operatorname{Dm}(t)-\operatorname{Sm}(t)<0$$, as $$\alpha>0$$, the instantaneous price change will be negative: $$p^{\prime}(t)<0$$, which tells us, as is to be expected, prices will tend to decrease.
> * If supply meets demand, a dynamic equilibrium, that is, if $$D m(t)-S m(t)=0$$, the instantaneous price change will be zero: $$p^{\prime}(t)=0$$, which indicates that prices will remain constant and equal to the current value.
> * The coefficient $$\alpha$$, can be interpreted as the speed of the price adjustment depending on the excess demand or the supply scarcity. Thus, a large value of this constant indicates a greater instantaneous price variation, which translates into a faster price adjustment.
