---
description: A mathematical approach for the LCOE formula
---

# Mathematical Approach

The idea of LCOE as the 'price' component of a constant minimum return of the project (constant in real terms) for the purchaser translates to the simple net present value calculation presented in Eq. 4:

$$
N P V_{\text {of project }}=N P V_{\text {of lifetime cost }}+N P V_{\text {of lifetime revenue }} \quad \text { Eq. } 4
$$

This could be better explained by Eq. 5:

$$
N P V_{\text {of project }}=-\sum_{t=0}^{N} C_{t}(1+r)^{-t}+\sum_{t=0}^{N} \underline{p} M_{t}(1+r)^{-t} \quad \text { Eq. } 5
$$

{% hint style="info" %}
Where;

$$C_{t}$$ is the cost of the project

$$M_{t}$$ is the electricity generation

$$N$$ is the lifetime of the project

$$r$$ is the discount rate

$$\underline{p}$$ is the price of delivered electricity
{% endhint %}

Setting $$N P V=0$$ leads to the solution of $$\underline{p}$$ and the internal rate of return (IRR) equals the discount rate for the chosen calculation. With $$C_{t}$$ comprising initial investment cost, $$I_{0}$$ variable,  $$C_{t}^{v}$$ fixed operation, and maintenance OM costs $$C_{t}^{f}$$, with the simplifying assumptions of constant electricity generation $${M}_{\mathrm{t}}=\underline{M}$$ and constant variable and fixed OM cost $$C_{t}^{v}+C_{t}^{f}=\underline{C}$$, some simple mathematical transformations lead to the well-known $$LCOE$$ formula Eq. 6:

$$
\underline{p}=L C O E=\frac{I_{0}}{\underline{M} U P V}+\frac{\underline{\underline{M}}}{\underline{\underline{M}}} \quad \text { Eq. } 6
$$

The uniform present value factor (or CRF capital recovery factor shown in a previous approach) presented in Eq. 7 results from the general solution of a geometric series of a constant flow and is widely used in life cycle cost analysis.

$$
U P V=\frac{(1+r)^{N}-1}{r(1+r)^{N}} \quad \text { Eq. } 7
$$

According to the National Renewable Energy Laboratory, the Eq. 5 __ corresponds to the simple Levelized cost of energy indicator ($$sLCOE$$). It can be easily calculated that the higher the investment $$I_0$$ and OM cost $$\underline{C}$$, the higher the value of $$\underline{p}$$, and conversely, the higher electricity generation $$\underline{M}$$, the lower the value of $$\underline{p}$$:

$$
\frac{p}{I_{0}}=\frac{1}{\underline{M} \times U P V}>0 \quad \text { Eq. } 8
$$

$$
\frac{p}{\underline{C}}=\frac{1}{\underline{M}}>0 \quad \text { Eq. } 9
$$

$$
\frac{\underline{p}}{\underline{M}}=\frac{-\left(I_{0} \times U P V+\underline{C}\right)}{\left({\underline{M} \times U P V)^{2}}\right.}<0
\quad \text { Eq. } 10
$$

From an energy-economic perspective, based on the interpretation of $$LCOE$$ as the constant price (in real terms) guaranteeing a minimum revenue for the purchaser to justify an investment, it should be intuitively clear that this price is higher than just the technology cost, ignoring the time value of electricity generation. This mathematical approach demonstrates the credibility and usefulness of the $$LCOE$$ if used methodically correctly.

To summarize, the $$LCOE$$ is an indicator widely used to compare the economics of energy technologies. It is also widely accepted that using the $$LCOE$$ as an exclusive indicator for energy technologies is insufficient for a comprehensive assessment, let alone for an investment decision. Yet, it is accepted as an important indicator for energy technology assessment, enabling a transparent and easy-to-understand analysis used for academic purposes and by international institutions such as IRENA, IEA, and others.
