# AppHealthReport

The module installs AppHealthReport components:
1) "Weekly App Health Report» report - the report collects error information for Reports, Imports, Modules, Rules, Notifications, and Trackor Mail, as well as their run times.
By default, the data is collected for the week, but the data sampling can be customized.

2) "Weekly App Health - run report" rule - the rule that runs the report.
For this report to run successfully, the AsyncRuleDefaultUser Program Parameter must be filled.

3) Rule "Weekly App Health - send a mail" - a rule that triggers after successful report execution and sends it to the specified email.
By default, it's noc-reports@onevizion.com, the mail gets there and then a Website Error Report is created on trackor.onevizion.com.