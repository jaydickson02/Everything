![[h3l7yb6p.bmp]]

### Bayes' Theorem
$$
P(A|B) = {{P(B|A) P(A)} \over P(B)}
$$
Probability of A given B occurs is the probability of B given A occurs times the Probability of A occurring all divided by the probability of B occurring. The numerator in this case is just another way of writing the probability of A and B occurring.

Bayes' Theorem allows us to update the probability of something by taking into account new or extra information.

As an example:

A friend tells you that an acquaintance of theirs has breast cancer. You want to determine the chance that this individual is male. If you had not know they had breast cancer a fair assumption might be that it was a probability of 50%. But given the new information Bayes' theory can give us an updated probability.

$$
P(Male | \text{Breast Cancer}) = {{P(\text{Breast Cancer} | Male) \cdot P(Male)} \over P(\text{Breast Cancer})}
$$
Most of these values can be gathered from credible sources, like a countries bureau of statistics.

$$
P(Male)=0.5
$$
$$
P(\text{Breast Cancer}) = 0.063
$$
$$
P(\text{Breast Cancer} | Male) = 0.001
$$
So, given these values we can find the probability that the acquaintance is male given we know they have breast cancer.
$$
P(Male | \text{Breast Cancer}) = {{P(0.001) \cdot P(0.5)} \over P(0.063)}
$$
$$
P(Male | \text{Breast Cancer}) = {0.079} \text{ or 0.79\%}
$$
