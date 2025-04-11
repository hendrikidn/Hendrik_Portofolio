# Collection Analytics
## Overview

!!! abstract "Project Brief"

    === "Pain Points"

        * {++Low recovery rates++} due to untargeted collection efforts.
        * {++High operational costs++} from visit, external fees, and legal processes.

        `Scope:`
        : 
        - Non Performing Loan (NPL)
        - Write-Off (WO) Buckets

    === "Goals"

        | Key Objective                 | Description                                               |
        | ----------------------------- | --------------------------------------------------------- |
        | Increase Recovery Rates       | Prioritize accounts with the highest likelihood of repayment.                                                                                  |
        | Reduce Collection Costs       | Automate segmentation and optimize resource allocation.   |

    === "Solution"

        A machine learning-powered collection system that:
        
        1. {++Predicts probability to collect (PtC)++} using historical data.
        2. {++Recommends optimal collection channel++} (Tele Collection, Field, External Collector).

    === "Approach"

        1. Data Element:
            1. Payment history, interaction logs, debt, risk scoring, agreement, asset, and customer demography
            2. Integrate external indicators (e.g., External Collector Capacity, Pefindo).

        2. Machine Learning Models:
            * Classification: 
                1. Probability to Collect → predict "Will Pay" vs. "Will not".
                2. Channel Recommendation → [One-Vs-Rest] predict "Tele Col." | "Field" | "External".
        
        3. Strategy Optimization (overlay rules):
            1. Next-Best-Action (NBA): Recommends the best outreach method.
            2. Back, Shadow (Live Labs), and A/B Testing: Validates model effectiveness.

        4. Monitoring:
            1. Dashboard
            2. Periodically model retraining with new data or revamp.

    === "Expected Outcomes"

        | Metric                        | Improvement Target            |
        | ----------------------------- | ----------------------------- |
        | Recovery Rate                 | :arrow_up_small: 5 - 20%      |
        | Operational Cost Reduction    | :arrow_down_small: 10 - 30%   |
        | Compliance Violations	        | Near-zero                     |

## Result

<div class="nav-buttons" style="display: flex; justify-content: space-between; margin: 2em 0;">
    <a href="../" class="md-button md-button--primary" style="color: white;">← Playbook</a>
    <a href="../2_customer/" class="md-button md-button--primary" style="color: white;">Customer Analytics →</a>
</div>