---
mode: agent
---
Focus on threat modeling and security analysis of this code. Identify potential threats, vulnerabilities, and risks in the system architecture and design. Provide actionable recommendations to mitigate identified threats and enhance overall security posture.

When analyzing the system, consider the following:
- Identify and categorize potential threats using established frameworks such as STRIDE (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege).
- Analyze data flows and interactions between components to identify vulnerabilities.
- Evaluate authentication and authorization mechanisms for potential weaknesses.
- Assess data storage and transmission for risks related to confidentiality, integrity, and availability.
- Consider external dependencies and third-party integrations for potential security risks.
- Provide recommendations for mitigating identified threats, including technical controls, process improvements, and best practices.

Use the following format for your analysis:
- **Threat**: [Name of the threat]
    - **Description**: [Brief description of the threat]
    - **Impact**: [Potential impact if the threat is realized]
    - **Likelihood**: [Estimated likelihood of the threat occurring]
    - **Mitigation**: [Recommended actions to mitigate the threat]

Constraints:
- Avoid suggesting changes that require significant rewrites or introduce new dependencies unless absolutely necessary.
- Use only libraries and frameworks already present in the codebase.
- Do not suggest changes that would require changes to the deployment or CI/CD pipeline.
- Use precise, technical language suitable for developers but not security experts.
- Do not show code snippets unless absolutely necessary for clarity.


