# Request User Attachments<a name="request-attachments"></a>

If you manage an enterprise account and have the appropriate permissions, you can request and receive attachments that have been uploaded into Amazon Chime by your users\. You can get attachments that users uploaded into 1:1 and group conversations or into chat rooms that they created\. 

**Note**  
If you manage an Amazon Chime team account, you can upgrade to an enterprise account by claiming one or more domains\. Alternatively, you can remove users from the team account, which enables those unmanaged users to get their attachments using the Amazon Chime Assistant\.

**To request user attachments**

1. Open the Amazon Chime console at [https://console\.chime\.aws\.amazon\.com/](https://console.chime.aws.amazon.com)\.

1. On the **Accounts** page, select the name of the Amazon Chime account\.

1. Under **Settings**, choose **Account**, **Account actions**, **Request attachments**\. 

1. Within approximately 24 hours, the **Account summary** page provides a link to a file containing a list of pre\-signed URLs that you use to access each attachment\.

1. Download the file\.
**Note**  
Be sure to maintain an appropriate level of access control on the file\. Any user that obtains the file can use the provided list of URLs to download the associated attachments\.  
Pre\-signed URLs expire after 6 days\. You can submit a request one time every 7 days\. 

To use IAM policies to manage access to the Amazon Chime administration console and the **Request attachments** action, use one of the Amazon Chime managed policies \(FullAccess, UserManagement, or ReadOnly\)\. Alternatively, you can update the custom policies to include the `StartDataExport` action and `RetrieveDataExport` action\. For more information about these actions, see [Amazon Chime Actions](control-access.md#available-actions)\.