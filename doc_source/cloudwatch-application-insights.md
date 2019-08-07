# Amazon CloudWatch Application Insights for \.NET and SQL Server<a name="cloudwatch-application-insights"></a>

Amazon CloudWatch Application Insights facilitates observability for \.NET and SQL Server applications\. It can help you set up the best monitors for your application resources to continuously analyze data for signs of problems with your applications\. Application Insights, which is powered by [Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/wahtis.html) and other AWS technologies, provides automated dashboards that show potential problems with monitored applications, helping you to quickly isolate ongoing issues with your applications and infrastructure\. The enhanced visibility into the health of your applications that Application Insights provides can help you reduce your mean time to repair \(MTTR\) so that you don't have to pull in multiple teams and experts to troubleshoot your application issues\.

When you add your applications to Amazon CloudWatch Application Insights for \.NET and SQL Server, it scans the resources in the applications and recommends and configures metrics and logs on [CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html) for application components\. Application components may include SQL Server backend databases and Microsoft IIS/Web tiers\. Application Insights analyzes metric patterns using historical data to detect anomalies, and continuously detects errors and exceptions from your application logs, including \.NET, SQL Server error log, and IIS\. It correlates these observations using a combination of classification algorithms and built\-in rules\. Then it automatically creates dashboards that show the relevant observations and problem severity information to help you prioritize your actions\. For common problems in \.NET and SQL application stacks, such as application latency, SQL Server failed backups, memory leaks, large HTTP requests, and aborted I/O operations, it provides additional insights that point to a possible root cause and steps for resolution\. Built\-in integration with AWS Systems Manager OpsCenter allows you to resolve issues by running the relevant Systems Manager Automation document\. 

**Topics**
+ [What Is Amazon CloudWatch Application Insights for \.NET and SQL Server?](appinsights-what-is.md)
+ [Getting Started with Amazon CloudWatch Application Insights for \.NET and SQL Server](appinsights-getting-started.md)
+ [View and Troubleshoot Problems Detected by Amazon CloudWatch Application Insights for \.NET and SQL Server](appinsights-troubleshooting.md)
+ [How Amazon CloudWatch Application Insights for \.NET and SQL Server Works](appinsights-how-works.md)
+ [Logs and Metrics Supported by Amazon CloudWatch Application Insights for \.NET and SQL Server](appinsights-logs-and-metrics.md)