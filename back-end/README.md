<h1 align="center">Authentication and Authorisation with Expressjs Bounty</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/alibaba0010/authentication-and-authorisation-with-expressjs/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

<h3 align="center"> The Concepts of Authentication and Authorisation</h3>

```
Authentication and authorization are both fundamental and core concepts in security that are often used interchangeably but have distinct meanings. Authentication is the 'who,' and authorization is the 'what.' Together, they form the cornerstone of secure systems
```
| Context |  Description  | 
|:-----|:--------:|
| Process   | Authentication is the process of verifying that a user is who they claim to be, often using techniques like passwords, fingerprints, or digital signatures or tokens. | 
| Process (following authentication)   |  Authorization is the process of granting or restricting a user's abilities within a system. It ensures that users can only access what they are allowed to based on their position, the user's roles, permissions, or privileges.  |  
| Relationship   | Authentication happens first, verifying the user's identity. Authorization follows, determining what actions the user can perform based on their verified identity. |    
| Analogy   | Authentication is like checking your ID at a club entrance. Authorization is like the bouncer deciding whether to let you in based on your ID and dress code. |   
| Security   | Both authentication and authorization are crucial for system security. Authentication ensures only authorized users can access the system, while authorization controls what they can do within the system. |   


### Why is Authentication a good Idea for Deleting Users in this quest?
```
- Data Loss: Unauthorized deletion of user accounts can lead to significant data loss, which can lead to Unavailability(one of the CIA triad) of data when needed.

- Security Breaches: Unrestricted access to user accounts poses a security risk, as malicious actors could exploit vulnerabilities to gain unauthorized access to sensitive data.

- Compromised Data Integrity: Ensuring that only authorized individuals can delete user accounts helps maintain the integrity of the system's data, preventing accidental or malicious modifications.

- Accountability: Authentication provides a clear audit trail, allowing for tracking who deleted a user account and when. This is essential for legal compliance, investigations, and accountability purposes.

- Enhanced User Experience: Requiring authentication for user account deletion fosters a sense of security and control among users, as they can be confident that their data is protected from unauthorized access or deletion.
```

### Summary

```
Implementing authentication before deleting users is a fundamental security practice that helps prevent unauthorized access to sensitive data and ensures that only authenticated individuals can perform actions with significant consequences.

Authentication verifies the identity of a user, confirming that they are who they claim to be. This is typically achieved through methods such as passwords, biometrics, or tokens. Authorization, on the other hand, determines what a user is permitted to do once their identity has been verified. It involves granting or denying access to specific resources or actions based on the user's roles, permissions, or privileges.

By requiring authentication before user deletion, systems can significantly reduce the risk of accidental or malicious actions that could result in data loss, privacy breaches, or disruption of services. This is particularly important in contexts where user data is sensitive or critical to operations.
```
