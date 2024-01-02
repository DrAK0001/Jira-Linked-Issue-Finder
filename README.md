Jira Linked Issue Finder
This Groovy script is designed to run within Jira's scripting environment to find linked issues based on matching custom field values.

Introduction
This script allows users to identify linked issues in Jira where a specific custom field value in the current issue matches the same custom field value in the linked issues.

Prerequisites
Jira Environment: Ensure this script is executed within Jira's built-in script console or a compatible scripting environment.
Script Permissions: Ensure the user running this script has appropriate permissions to access issues, custom fields, and issue links.
Usage
Setup: Copy the provided Groovy script content.
Execution:
Navigate to the Jira scripting console or a compatible environment.
Paste the script into the script editor.
Execute the script.
Script Details
The script retrieves the current issue within Jira based on the context where it's executed.
It accesses a specific custom field (customfield_14001) in the current issue and looks for linked issues.
Linked issues with matching custom field values are collected and returned as a list of issue keys.
Troubleshooting
If you encounter issues such as:

"Issue or custom field value not found" message: Verify the existence and accessibility of the specified custom field and its values.
No linked issues returned: Ensure there are linked issues with matching custom field values for the current issue.
Notes
This script might need adjustments based on the configuration and permissions within your Jira environment.
Always test the script in a safe environment before applying it to a production instance.
Disclaimer
This script is provided as-is without any warranties. Use it at your own risk.
