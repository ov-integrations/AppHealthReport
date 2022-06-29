# app-health-report

The Module contains AppHealthReport components
| Component | Description | Additional Information |
| --- | --- | --- |
| "Weekly App Health Report" report | The report collects error information for Reports, Imports, Modules, Rules, Notifications, and Trackor Mail, as well as their run times. | By default, the data is collected for the week, but the data sampling can be customized.
| "Weekly App Health - run report" rule | The rule that runs the "Weekly App Health Report" report. | For this rule to run successfully, the AsyncRuleDefaultUser Program Parameter must be filled.
| "Weekly App Health - send a mail" rule | The rule that triggers after successful "Weekly App Health Report" report execution and sends it to the specified email. | Trackor Mail is configured for the specified mail and this report goes to a special Trackor Type, which contains information about all the reports that come from different installations.