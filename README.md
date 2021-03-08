# test-app-insights-event-action
![send-app-insights-event](https://github.com/syedhassaanahmed/test-app-insights-event-action/workflows/Send%20events%20to%20App%20Insights/badge.svg)

This GitHub workflow tests the GitHub Action [app-insights-event-action](https://github.com/syedhassaanahmed/app-insights-event-action). When executed, each event sent to Application Insights will have `customDimensions` that looks like the following;
```json
{
    "event_name": "push",
    "run_number": "1",
    "repository": "syedhassaanahmed/test-app-insights-event-action",
    "workflow": "Send events to App Insights",
    "actor": "syedhassaanahmed"
}
```
