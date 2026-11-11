# Task 3 — fixed-window reliability review (replace four lines)
SLI: 98.8% (9,880 successful/10,000 total requests), below the agreed 99.0% SLO for the supplied window.
Allowed errors: 100 (10,000 * (1 - 99/100) = 100).
Remaining error budget: -20 (100 allowed - 120 actual errors).
Decision: Do not proceed with routine feature releases; prioritize reliability improvements because the error budget is exceeded by 20 errors.
