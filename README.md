# The Unknown Mean Problem
**Abstract**

In many areas of knowledge, we face the challenge of inferring a hidden truth from incomplete information.
Whether in statistics, machine learning, or decision-making, we often have only a partial sample of a larger,
unknown set.

This problem seeks to answer the following question: How to identify which new data should be incorporated
into a partial sample so that its mean approaches the true population mean – without previously knowing this mean?


## Formal Problem Definition
There is an unknown population set ($X$), composed of elements $\\{?_1 ,\ ?_2 ,\ ...,\ ?_n\\}$, whose real mean ($\mu$)
is is unknown:

$$
\mu \ =\ \frac{\sum X_{i}}{N}
$$

You have a **known partial sample** ($\ohm$) withdrawal of $X$ with known elements:

$$
\ohm\ =\ \\{1,\ 2,\ 3\\}
$$

The known sample mean is:

$$
\overline{x} \ =\ \frac{\sum \ohm_{i}}{|\ohm|}
$$

- You have **three possible new elements** that could be added to the sample,
 but you don't know which ones (or if any) belong to the original population. ($X$)
- The goal is to find a selection criterion that indicates which of the new elements, if any,
  should be added to bring $\overline{x}$ closer to the unknown mean $\mu$

## Core Question
Given an unknown population set
$X$, we want an explicit mathematical equation that, when given a known sample set
$\ohm$ and 2 or more possible new elements, determines which element should be chosen 
to move the sample mean towards the population mean $\mu$, without needing to know it directly.

## How to contribute
You can post your answer as an issue here in this repository and I will be looking at them all.
