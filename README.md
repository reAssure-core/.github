# The problem reAssure solves
## Problem:
There is no existing way to get compensated if your codebase breaks in production. Yes, there are audits like SOC and ISO to enforce safety standards and best practices, but none ensure after-the-fact compensation for such breakages.

## Problem Size:
This is especially surprising considering the fact that code is the most common part of intangible assets (that make up 80% of assets on the balance sheet of all S&P 500 companies). Even though insuring these assets should be worth at least $220bn (considering a 1% premium/coverage and 2018 asset value of $22Tn combined) no large US-based legacy insurer is offering this service. On digging deeper we found that it was because the costs of insurance ops for such a product make no sense for a single insurer.

## Solution:
So we built reAssure, a reinsurance marketplace where underwriters can come in and tokenize their insurance policy. These policy tokens are then traded in a marketplace and dynamically repriced as and when new claims are processed. And community members can create and vote on the acceptance of: risk mitigation strategies, claim processing vendors, and risk oracles.

Our core value props are:

Reinsurance: reAssure creates a transparent marketplace to reprice codebase risk in real-time and exchange risk amongst insurers with common object standards driving securitization.

Claim Processing: Our risk token holders can select from competing claim processing vendors using community Oracle data. This is cheaper than using centralized claim processing options that cost over $200k just for assessing damages.

Risk Modelling & Mitigation: As there is no established way of doing this for code, reinsurers benefit greatly from transparent & competing risk feeds and mitigation strategies.

## Challenges we ran into
### Main Glitch
While no one falls sick just because there is health insurance it is possible that people may leave intentional glitches in their codebases or one of its very nested dependencies in order to benefit from insurance payouts aka commit insurance fraud.
Solution: To resolve this we restricted our scope to only S&P 500 companies and pre-audited codebases only. This allows people to calculate risk much more predictably as both downtimes and business losses due to the same is much easier to understand for public companies with regulatory filings. Another way to do this might be via KYCed wallets but that introduces new issues too.

### Followup Issue
In an urgency to close a deal or meet quarterly targets, an insurer may include very lax terms for payouts and claim acceptance in the policy which will be unfair to token purchasers.

Solution: So this is basically about long-term horizons vs short-term horizons. An insurer that wants to stay in business and get policy renewals will have to favor the insuree ofc but in order to get oversubscription to his policy tokens he will need to be fair to the buyers as well, or else he will be left holding a risk policy on his books. In addition, we also allow users to vet underwriter credibility separately. For ex: I would be much less skeptical about buying a token made from a policy issued by Allianz vs Random Insurance CO.
