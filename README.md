# Automatically Extract APG Goals from Quarterly Reports

Neil Miller (neil.miller@gsa.gov)

Each quarter, Federal agencies submit PDF reports to [performance.gov] with updates about their [Agency Priority Goals https://www.performance.gov/blog/2023-agency-priority-goals-overview/]. These reports contain updates on specific metrics.

This repository automates the extraction of metric updates from these quarterly reports.

In order to run _Extract_goal_targets_using_Claude.ipynb_, you should save your Claude API key as an environment variable entitled `ANTHROPIC_API_KEY`. Several APG reports are uploaded to the _FY2024 Q2 reports_ sub-directory; all of the reports in this folder will be processed by _Extract_goal_targets_using_Claude.ipynb_.

The output data from all FY2024 Q2 reports is in _APG_targets_FY2024_Q2.xlsx_. In total, this file contains 207 goals from 60 different PDF reports.
