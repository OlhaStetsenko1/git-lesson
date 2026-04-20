### Risk Description for "Authentication Risks"

**Title:** Authentication Risks

**Description:** There is a known issue with SSH authentication for GIT sources, which requires users to use HTTPS instead. This may cause inconvenience for users who are accustomed to using SSH keys for authentication, potentially leading to delays and frustration.

**Category:** Technology

**Trigger:** Infrastructure

**Likelihood:** Middle

**Impact:** Middle

**Responsible Person:** DevOps Manager

**Treatment/Maintenance Plan:**
1. Communicate the issue and alternative authentication method to all users.
2. Provide detailed documentation and support for switching to HTTPS.
3. Monitor the situation and gather user feedback.
4. Investigate and work on resolving the SSH authentication issue.

**Risk Strategy:** Mitigate

**Mitigation Plan Actions:**
1. Notify users about the issue and the need to switch to HTTPS.
2. Offer step-by-step guides and support for the transition.
3. Regularly update users on the progress of resolving the SSH issue.

**Contingency Plan Actions:**
1. If the issue persists, consider implementing additional security measures for HTTPS.
2. Explore alternative authentication methods if HTTPS also encounters issues.
3. Ensure continuous communication and support for users facing difficulties.