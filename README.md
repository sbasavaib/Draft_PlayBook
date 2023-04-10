
# PSIRT PLAYBOOK :green_book:
### Handling Exposed Secrets, Leaked Credentials, and Leaked API Keys.
---

This playbook outlines a clear and easy-to-understand set of steps that your Product Security Incident Response Team (PSIRT) should follow when handling exposed GitHub secrets, leaked credentials, or leaked API keys. The instructions are beginner-friendly and can be implemented by anyone with basic knowledge of security concepts.

### Step 1: Identify and Verify the Leak
1. Confirm the leak. Determine if the exposed secrets, credentials, or API keys are indeed sensitive and if they belong to your organization.
2. Identify the source. Determine the repository, file, or conversation where the leak occurred.
3. Record the details. Create a document with the key details of the incident, including the date and time the leak was discovered, the type of data exposed, and the person who discovered the leak.

### Step 2: Contain the Exposure
1. Remove the exposed data. If the leak is in a GitHub repository, use the [GitHub guide](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository) to remove the sensitive data from the repository's history.
2. Restrict access. Limit the access to the repository or file containing the exposed data while you investigate and remediate the issue.
3. Notify affected users. If the leak involves user credentials or API keys, notify the affected users and recommend they change their passwords and/or regenerate their API keys.

### Step 3: Investigate the Impact
1. Perform a risk assessment. Analyze the potential impact of the leaked information on your organization and users, considering factors like the type of data leaked, the number of users affected, and the potential for unauthorized access to sensitive resources.
2. Check for unauthorized access. Review logs and other data sources to determine if the exposed credentials or API keys were used by unauthorized parties.
3. Document your findings. Update the incident document with your findings, including any evidence of unauthorized access or potential impact on your organization and users.

### Step 4: Remediate and Recover
1. Revoke the exposed credentials or API keys. Ensure that the exposed data is no longer valid and cannot be used for unauthorized access.
2. Implement new credentials or API keys. Issue new credentials or API keys to affected users and update any internal systems or applications that relied on the exposed data.
3. Improve security practices. Evaluate and update your organization's security practices to prevent future incidents, such as implementing proper secret management solutions, conducting regular security audits, and providing security training to your team.

### Step 5: Communicate and Learn
1. Inform stakeholders. Communicate the incident and your response to all relevant stakeholders, including management, affected users, and any external parties (e.g., partners, vendors, or regulators) as required by your organization's policies or applicable legal requirements.
2. Conduct a post-mortem. After the incident is resolved, perform a post-mortem analysis to identify the root cause, lessons learned, and any additional improvements that can be made to your organization's security practices.
3. Update the playbook. Based on the findings from the post-mortem analysis, update this playbook to ensure that your team is better prepared to handle similar incidents in the future.


