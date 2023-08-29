# Liability-Driven Investment problem

These notes are from [Section
2](https://www.soa.org/4964e1/globalassets/assets/files/resources/research-report/2021/liability-driven-investment.pdf).

Key drivers of liability risk are

-   `Discount rate` - Refers to discounting back expected future benefit
    payments. Often associated with interest rates.  
-   `Inflation` - Certain liability payments may be adjusted according
    to inflation, which affects the liability value  
-   `Claim rate` - The probability that an insurance claim or pension
    benefits will be paid  
-   `Policyholder behaviors` - Insurance products are generally
    long-term products that can be affected by a policyholder’s usage,
    financial situation, etc.  

Modeling the relationship between assets and liabilities is difficult in
extreme scenarios using traditional methods that rely on things like
correlation coefficients, since the level of dependency between assets
and liability usually increases. Some approaches also focus on the
current status of a liability portfolio but lack the ability to
incorporate its evolution.

Lastly, institutions will trade part of the security in investing in
certain assets for riskier ones with expected higher returns (hedging
ratio).

The goal of the research report is to then us AI techniques as a dynamic
optimization method that can include the evolution of the liability, the
nonlinear relationship between asset and liability, and an institution’s
`risk appetite`.
