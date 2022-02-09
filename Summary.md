
## Spot a Home - Technical exercise summary

We are running an A/B test for four weeks to try to find if we could increase the renting fees to increase revenues.

**Key findings:**

* We have some problems with the integrity of the data. All three assumptions we made when designing the experiment were broken. After proper discussion, **all suspicious data were dropped** in order to have an unbiased experiment. I suggest to check our ETLs as soon as possible to try to find an explanation.

* **Variant B have a smaller conversion rate**. We are 99% confident of this finding. The downlift was almost 27%.

* However, due to the higher fees, **revenues per website visitor are higher in variant B** even with the smaller CVR. We are 99% confident of this result. The uplift in revenues per user was 29%. Therefore, **we suggest to roll out the new variant B**.

* We found with a 95% confidence that the **variant A have 199.24 +- 3.48 average revenue** whereas the **variant B have 352.13 +- 5.33 average revenue** per booking request.

* **The percentage increase in fees is about 77%**. Our 90% confidence interval for the uplift is [45%,116%].