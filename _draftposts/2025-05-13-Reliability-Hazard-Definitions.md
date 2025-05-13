## Reliability Function and Hazard Rate

*This post will be the first in a series that aims to describe some of the fundamental theories of Reliability Engineering.*

*In this post I will give an introduction into two key terms of reliability engineering - the hazard rate and the reliability function.*

The reliability function and hazard rate are methods that, by using statistical distributions, can be used to predict failures of components and systems.

### Reliability Function

The reliability function, also known as the survivor function, is defined as:

*The probability of a device not failing prior to some time.*

If a component had a reliability function of $
0.8 $ at $100$ hours, there is an $80$% chance that it will still be functioning after 100 hours.

The reliability function is directly linked to the failure probability distribution, $f(t)$, in the following:

$$
F(t) = \int\limits_0^t f(t)dt
$$


