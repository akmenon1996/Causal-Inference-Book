---
description: Randomized Control Trial (RCT)
---

# Randomization

Randomized experiments were developed predominantly focusing on medical and agriculture. [Randomized controlled](https://en.wikipedia.org/wiki/Randomized_controlled_trial) trials are best to date, as we believe and agree that randomization is not biased. In this process, we randomly divide units into treatment and control groups before the action or intervention takes place, in an attempt to make these units comparable. Both the groups \(treatment and control\) are given different treatments. Randomization makes these groups comparable, after which the outcome is observed. If we believe that data is separated without any bias, this is a very good method for quick conclusions.

1. Randomized Experiments:
2. A/B testing

![](../../../.gitbook/assets/image%20%2820%29.png)

## **Why Randomization?**

If a person knows that they are getting a placebo or an active drug, they might stop taking the drug which hence would introduce bias. If this study is not randomized then the causal difference might be due to how the patients reacted, which is actually the true causal effect. Thus the allocation should be randomized. Randomization removes the worry about the treatment being correlated with other missing values. The extreme version of this correlation is confounding. **Example**: Understanding the causal effect of medication to cure a disease, can be tested through randomized control trial\(RCT\), where some people are randomly given the treatment and some placebo\(Control group\). The outcome of this can be considered as a causal effect because the treatment is randomly assigned and all possible confounders are removed through this process of randomization.

**Note**: Randomization removes the back door path from the treatment to the outcome!!

A **randomized experiment holds the following true \(Assumptions\):**

1. **Non-Deterministic**, Every unit has a small and equal chance of being given treatment/control
2. **Individualistic**, Treatment assignment probability doesn't depend on the potential outcome of other covariates of other units
3. **Unconfoudned**, It is unconfounded treatment assignment probability is independent of the potential outcome.

**Note: Unconfoundedness** is very crucial in randomized experiments, as randomization does not remove confoundedness. **Example**: Examining the causal effect of college on a good job, wherein there might be a confounding effect. Randomization is not possible here and not the solution. As we can't make sure if the students were already smart or college made them smarter for getting good-paying jobs. There is a confounding effect here that needs to be controlled.

* **Covariate Balance**: In randomization, when we randomly assign the people from the population of interest, then there is an equal distribution of covariates in both the treatment and control group. This balance of covariates in both groups is known as covariate balance.

## **Types**

**There are 4 types of Randomized experiments:**

1. **Bernoulli trials**: Every unit is assigned treatment with the same probability \(p = 1/2\). Treatment for each unit is determined by the flip of a coin.
2. **Completely randomized experiments:** Random sample, is taken and assigned to treatment. Sample size for treatment and control is the same \(N/2 each\). Example: **A/B testing** 
3. **Stratified randomized experiment**: Subgroups based on covariates, X,  are partitioned and given completely randomized experiments within each of these strata.
4. **Paired Randomized experiments**: Special case of stratified randomized experiments with 2 similar samples are matched into pairs. It is also called Matched pair experiments.

## **Resource**:

[https://kojinoshiba.com/causal%20inference/what-are-experiments/](https://kojinoshiba.com/causal%20inference/what-are-experiments/)

