# Memo: retention offers for the subscriber base

**To:** Board / VP of Growth · **From:** Belén Shell-Merier, Economic Analyst · **Date:** November 2026

## Recommendation
**Offer month-to-month customers an annual contract with one free month. Make no offer to customers who already have a contract, and do not give a blanket discount.** Start with a randomized pilot before rolling it out.

- **Value:** about +USD 48k of expected lifetime value for this plan. A 15% discount for every month-to-month customer would instead lose about USD 239k. Both figures are compared with doing nothing.
- **Who receives it:** the 3,875 month-to-month customers (segments 1-4). The 3,168 customers on contracts churn 3-11% a year, so an offer to them would mostly be paid to people who were not going to leave.
- **First year:** with the plan, monthly recurring revenue (MRR) is about USD 333k in month 12, against USD 321k without it, a difference of USD 11.8k per month. The free month costs about USD 64k, so the net gain in the first year is about USD 34k. Most of the value comes after year one.

## Why
- Two of six segments, month-to-month customers with high bills (new and tenured), are 29% of customers and 68% of the monthly revenue lost to churn.
- Month-to-month customers churn 42.7% a year, compared with 2.8% for customers on two-year contracts. In a logistic regression, a two-year contract is associated with 74% lower odds of churn (odds ratio 0.26). Customers choose their contracts, so this is an association, not proof that contracts cause retention.
- A discount for everyone pays the customers who would have stayed as well as those at risk, and the first group is the majority.

## Risks
- The plan pays off only if churn falls by about 23% among customers who accept the offer (22-29% depending on the segment). The working assumption is 40%. If the offer works at half that strength or less, it does not pay.
- The dataset marks churn without a time frame. I read it as annual; if it were monthly, all lifetime values would be much lower and the analysis would need to be redone.
- Take-up (25%), the effect on churn, the 60% margin, the 10% discount rate, the 5-year horizon and the USD 300 acquisition cost are assumptions, not measurements.

## How we will measure it
- **Design:** all 3,875 eligible customers, assigned at random: half receive the offer, half do not (control group).
- **Duration:** results are read at 12 months, because churn is measured over a year. Contract conversions and monthly churn are tracked every month as early signals.
- **What the pilot can detect:** with 25% take-up, a randomized test sees only about a quarter of the effect on the customers who accept. The pilot can confirm the 40% assumption, but confirming the 23% break-even would need 12,722 customers. At 50% take-up, about 1,600 customers per group would be enough, so improving take-up comes first.
- **Reading the result:** a significant result supports the rollout. A non-significant result means the effect is below about 40%, not that the offer fails, and calls for a larger or longer test.

*Data: IBM Telco Customer Churn sample (7,043 customers, one snapshot). Full analysis in the notebook.*
