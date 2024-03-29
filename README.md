Interest rates/ exchange rates This is a python file that replicates the carry trade strategy

We consider the strategy of a Norwegian firm that is exporting in the United States. This Norwegian company is producing a new mobile phone that is supposed to compete against the most famous US brand. The device is entirely produced in Norway and then exported in the United States.

You are the general manager of this Norwegian firm and your collaborators and engineers ensure that the quality of your product is superior to that of your US competitor. The new device that you are releasing on the market is characterized by more storage space, a much more powerful processor, more features and an innovative design. You devoted your energies, time and financial resources during the recent years in order to come up with a novel product that is supposed to be more appealing than the famous phone of your US competitor.

The strategy department of your company suggests you to stick to the following strategy: fix your price exactly equal to the price in USD of your US competitor, which charges 1,000 𝑈𝑆𝐷 for the latest version of its mobile phone. The rationale behind this choice is that your engineers are confident that your new device will be a breakthrough in the IT market thanks to its new innovative technology. In addition, your marketing department believes that the brand of your firm is already well reputed in the US, thanks to your high-quality products. You thus decide to compete on quality rather than on prices, and you set up your strategy in such a way that the USD price of your new phone sold in the US will be always equal to the USD price of your competitor’s device, in any market condition and in any year.

In order to produce the new device in Norway, your company faces a total cost equal to 7,000 𝑁𝑂𝐾 per phone. This total cost already includes variable costs and the amortization of fixed costs. Your strategy is to produce in Norway and sell in the US a total quantity of 10,000 phones. The spot exchange rate at time 𝑡, expressed in units of domestic currency per unit of foreign currency, is 𝑁𝑂𝐾 8⁄𝑈𝑆𝐷. Question A1: Compute your profit margin in year 𝑡, assuming that your firm is able to sell all the 10,000 mobile phones. Please start by reporting in your answer the values for the following variables: price per unit in USD, total revenues in USD, total revenues in NOK, total costs in NOK, total profit in NOK, and profit per unit in NOK. The profit margin is defined as the ratio between profit per unit and price per unit. Please use the values of the latter variables expressed in NOK to compute the profit margin.

You now plan your strategy for the following year 𝑡 + 1. The finance department of your company gives you a report listing the following monetary and financial data: • Inflation in Norway between year 𝑡 and 𝑡 + 1 is 1%. • Inflation in the United States between year 𝑡 and 𝑡 + 1 is 5%. • According to their estimates, the expected exchange rate in year 𝑡 + 1 will be approximately equal to 𝑁𝑂𝐾 7.6952⁄𝑈𝑆𝐷.

We assume that all prices and costs in each country, in this exercise, are impacted by the exact amount of inflation in that specific country, which is reported above. We also assume that the expectation of your finance department turns out to be ex post perfectly correct.

Question A2: What is the profit margin in year t+1, if your firm produces and sells the same number of phones as in year 𝑡? We assume that your firm decided not to hedge against exchange rate risk. Please do again the computations with all values in NOK, for the sake of consistency with Question A1.

Question A3: Comment on the results about the profit margins that you have computed in Questions A1 and A2. Why do we obtain such results? What is the economic explanation and what are the two effects driving this result?

Question A4: Why do you think that your finance department came up with such estimate of the exchange rate in year 𝑡 + 1? Link the results to theory and explain it in detail.

Imagine that, instead, the finance department had provided a different estimate for the exchange rate at year t + 1, that is 𝑁𝑂𝐾 6.00⁄𝑈𝑆𝐷. Everything else stays constant, including the inflation rates and the dollar price that your competitor is charging.

Question A5: Compute the profit margin with the new exchange rate. Explain your results and compare them to those obtained in Questions A1 and A2.

Question A6: As the top manager of your firm, you now decide to change your policy and you modify the price in USD that you will charge for your phone in the United States in year t + 1. Derive the price at which your profit margin are expected to be zero, and the condition under which your profit margin will be positive. Based on your computations, discuss why you have now decided to decrease, or increase, or keep constant your dollar price, even if the number of mobile phones sold remained the same. What does this imply for the international competitiveness of your firm?

Part B: we now move to implement a famous trading strategy based on exchange rates: carry trade.
