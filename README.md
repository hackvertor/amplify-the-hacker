# Amplify the hacker

## Offensive AI plugin development

This repository is to store materials and links for my [SteelCon](https://www.steelcon.info/) talk "Amplify the hacker"

![Hackvertor logo](https://github.com/hackvertor/amplify-the-hacker/blob/main/logos/hackvertor-logo.png)

### Hackvertor

Hackvertor is a tag based conversion tool written in Java implemented as a Burp Suite extension. Tags are constructed as follows:
`<@base64></@base64>` the @ symbol is used as an identifier that it's a Hackvertor tag followed by the name of the tag in this case base64.

[Hackvertor source code](https://github.com/hackvertor/hackvertor/)

![Shadow Repeater logo](https://github.com/hackvertor/amplify-the-hacker/blob/main/logos/shadow-repeater-logo.png)

### Shadow Repeater

Shadow Repeater enhances Burp Suite’s Repeater by automatically generating and testing variations of your payloads to uncover potential security weaknesses. Whether you're probing for path traversal, SQL injection, XSS, or other vulnerabilities, Shadow Repeater intelligently mutates your inputs and analyzes responses for anomalies, making it an essential tool for in-depth manual testing and fuzzing. Stay one step ahead by discovering bypasses and alternative attack vectors that might otherwise go unnoticed.

[Shadow Repeater source code](https://github.com/hackvertor/shadow-repeater/)

![Document My Pentest logo](https://github.com/hackvertor/amplify-the-hacker/blob/main/logos/document-my-pentest-logo.png)

### Document My Pentest

Document My Pentest creates a description of whatever you are trying to test. Whether you're probing for path traversal, SQL injection, XSS, or other vulnerabilities, Document My Pentest tries to understand what you are doing and documents it for you.

[Document My Pentest source code](https://github.com/hackvertor/document-my-pentest/)

![Repeater Strike logo](https://github.com/hackvertor/amplify-the-hacker/blob/main/logos/repeater-strike-logo.png)

### Repeater Strike

Repeater Strike is an AI-powered tool that helps uncover IDOR and other vulnerabilities by analyzing your Repeater requests. It automatically generates targeted regular expressions based on the requests and responses you're testing. Once a vulnerability is detected, these regexes are applied to your proxy history to rapidly identify similar issues across your entire traffic, helping you scale your findings and save time.

[Repeater Strike source code](https://github.com/hackvertor/repeat-strike/)