The Samvera Community uses the following process to collect reports of vulnerabilities, verify them, create a patch to fix them, and release the patch to users of the affected software.

1. A vulnerability report is made to the Samvera Community via an email to [security@samvera.org](mailto:security@samvera.org). Messages to this email address are sent to the Community Manager, Technical Coordinator, platform Product Owners, and the Board. 

2. The Community Manager or Tech Coordinator acknowledges the report with the reporter and communicates a timeline for when the vulnerability will be reviewed and verified. 

3. The Community Manager works with the community maintainers who are most familiar with the software in order to verify the report. This could include the Tech Coordinator, Product Owners, or other community developers. 

4. If the report is validated, the Community Manager or the Tech Coordinator verifies the report and confirms with the reporter. If the report is not validated, the Community Manager or the Tech Coordinator shares that finding with the reporter. 

5. If a report is validated, the Tech Coordinator or another designated community developer creates a **draft** [Common Vulnerabilities and Exposures (CVE) report](https://www.cve.org/About/Overview) via the [GitHub Security Advisories process](https://docs.github.com/en/code-security/concepts/vulnerability-reporting-and-management/repository-security-advisories). This is a standardized format used to publicly disclose security vulnerabilities once a fix has been created, and to credit the reporter. This draft is not finalized and made public until the fix is released.

6. The Community Manager notifies the Samvera Partners via the Samvera Partners email list, and shares information about the reported vulnerability using information from the draft CVE. A special Partner security group in GitHub can also view the draft forms. 

7. The Tech Coordinator, in partnership with appropriate community developers and Product Owners, builds a solution on private branches and prepares releases.

8. Once a solution is ready to be released, the Tech Coordinator or their designee applies the CVE report for human review as part of the GitHub security advisory process.

9. The Community Manager sends a notification to Partners that the fixes are available, and the CVE is under review.

10. Once the CVE is accepted, the Community Manager sends a message to the whole community, via email lists and Slack, to share the releases and the vulnerabilities they address.  

11. The Community Manager follows up to verify with the reporter that the fixes address the report. Any disagreement restarts the process at the verification step. 
