# Automatically Extract APG Goals from Quarterly Reports

Neil Miller (neil.miller@gsa.gov)

Each quarter, Federal agencies submit PDF reports to [performance.gov](performance.gov) with updates about their [Agency Priority Goals](https://www.performance.gov/blog/2023-agency-priority-goals-overview/). These reports contain updates on specific metrics.

This repository automates the extraction of metric updates from these quarterly reports.

In order to run [Extract_goal_targets_using_Claude.ipynb](Extract_goal_targets_using_Claude.ipynb), you should save your Claude API key as an environment variable entitled `ANTHROPIC_API_KEY`. Several APG reports are uploaded to the [_FY2024 Q2 reports_](https://github.com/GSA/extract_APG_goals/tree/main/FY2024%20Q2%20reports) sub-directory; all of the reports in this folder will be processed by [Extract_goal_targets_using_Claude.ipynb](Extract_goal_targets_using_Claude.ipynb).

The output data from all FY2024 Q2 reports is in [APG_targets_FY2024_Q2.xlsx](APG_targets_FY2024_Q2.xlsx). In total, this file contains 207 goals from 60 different PDF reports.
