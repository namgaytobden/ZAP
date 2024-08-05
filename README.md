# ZAP Penetration Test GitHub Action

This custom GitHub Action leverages the ZAP (Zed Attack Proxy) tool to perform penetration testing on a specified website. The results of the test are then sent to a provided email address. ZAP is a popular open-source security tool maintained by the OWASP (Open Web Application Security Project) that helps identify vulnerabilities in web applications.

## Benefits of Using ZAP

- **Comprehensive Security Testing:** ZAP performs various types of security tests, including but not limited to cross-site scripting (XSS), SQL injection, and insecure server configurations.
- **Open Source and Extensible:** ZAP is open-source, which means it's free to use and can be extended with plugins to add additional functionality.
- **Active Community Support:** Being a part of the OWASP project, ZAP has a large and active community that continuously contributes to its development and maintenance.
- **Automated Scanning:** ZAP can automate the process of scanning for vulnerabilities, making it easier to integrate into CI/CD pipelines.

## Usage

To manually trigger this action, follow these steps:

1. **Navigate to the Actions tab** of this GitHub repository.
2. **Select the ZAP Penetration Test Action** from the list of available workflows.
3. **Provide the required inputs:**
    - **Email:** The email address where you want to receive the test results.
    - **Web URL:** The URL of the website you want to test.

4. **Trigger the Action** by clicking the `Run workflow` button.

Once triggered, the action will:

1. Run the ZAP penetration test on the specified website.
2. Summarize the findings in an email.
3. Send the email to the provided address with the test results.

![Looping Video](docs/loop.gif)

