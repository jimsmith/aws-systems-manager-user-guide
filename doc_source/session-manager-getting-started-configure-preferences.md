# Step 4: Configure Session Preferences<a name="session-manager-getting-started-configure-preferences"></a>

A system administrator can configure Session Manager to create and send session history logs to an Amazon Simple Storage Service \(Amazon S3\) bucket or an Amazon CloudWatch Logs log group\. The stored log data can then be used to audit or report on the session connections made to your instances and the commands run on them during the sessions\. The system administrator can also specify options for encrypting session data\.

Before a user can update Session Manager preferences, they must have been granted the specific permissions that will let them make these updates, if they do not possess them already\. Without these permissions, the user can't configure logging options or set other session preferences for your account\. For information about granting permissions to update Session Manager preferences, see [Grant or Deny a User Permissions to Update Session Manager Preferences](preference-setting-permissions.md)\.

**Topics**

For information about using the AWS CLI to update session preferences, see the following topics:
+ [Create Session Manager Preferences \(AWS CLI\)](getting-started-create-preferences-cli.md)
+ [Update Session Manager Preferences \(AWS CLI\)](getting-started-configure-preferences-cli.md)

For information about using the Systems Manager console to configure Session Manager preferences, see the following topics:
+ [Logging Session Data Using Amazon S3 \(Console\)](session-manager-logging-auditing.md#session-manager-logging-auditing-s3)
+ [Logging Session Data Using Amazon CloudWatch Logs \(Console\)](session-manager-logging-auditing.md#session-manager-logging-auditing-cloudwatch-logs)