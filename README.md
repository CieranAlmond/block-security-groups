# block-security-groups

Policy as Code lab provided by Ashley Pearce - www.linkedin.com/in/ashley-thornhill

Overview
In this lab, you'll write a policy that blocks open security group rules. Like allowing the entire internet (0.0.0.0/0) to access sensitive ports such as SSH (22) or RDP (3389). These are among the most common and dangerous misconfigurations in cloud environments and are frequently exploited in attacks. You’ll write a policy using Rego, test it with Conftest, and run everything inside GitHub Codespaces with no local setup required. This lab is beginner-friendly and perfect for GRC professionals who want to see how policy as code can enforce real security requirements.

By the end, you’ll:
Understand why open security group rules are dangerous
Write a Rego policy to block them
Use Conftest to test your policy
Run it all inside GitHub Codespaces
