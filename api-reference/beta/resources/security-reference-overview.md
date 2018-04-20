# Use the Microsoft Graph API for security threat detection and protection (preview)

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

The sophistication of security threats continues to escalate, affecting the global economy. Damage is often done long before organizations even discover it. You can use Microsoft Graph to build or extend security solutions that consolidate and correlate security alerts from multiple sources, detect threats that attempt to compromise user identity, unlock contextual data to inform investigations, and automate security operations for greater efficiency.

Microsoft Intelligent Security Graph brings together security intelligence from within Microsoft, security operations centers, and partners from around the world to form an ecosystem of integrated security solutions. Using machine learning, behavioral monitoring, and the scale of the cloud, the Intelligent Security Graph can better protect, detect, and respond to threats quickly and comprehensively. The [security API](security-api-overview.md) connects you to the [Intelligent Security Graph](https://www.microsoft.com/en-us/security/intelligence-security-api), empowering you with solutions that are actionable and holistic.

Most security breaches are the result of attackers stealing a user’s identity, and attackers have become terrifyingly effective in leveraging third party breaches, password spray attacks, sophisticated phishing attacks. This means you need to protect all your user accounts from these attacks and proactively prevent compromised identities from being abused.

Azure Active Directory uses adaptive machine learning algorithms and heuristics to detect anomalies that indicate potentially compromised accounts. Using this data, Identity Protection protects your users with risk-based conditional access policies and generates reports and alerts on its detections.

The [identity protection risk events API](identityprotection_root.md) gives easy access for Azure AD Premium P1 and P2 customers to query [risk detections made by Identity Protection](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-identityprotection-graph-getting-started) and use those events in SIEM systems and security applications.

## Next steps

- [Why use the security API and connect with Microsoft Intelligent Security Graph](../../../concepts/security-concept-overview.md#why-use-the-security-api-and-connect-with-microsoft-intelligent-security-graph)
- [Use the security API to integrate with Microsoft Intelligent Security Graph](security-api-overview.md)
- [Why use Azure Active Directory to protect identities in your organization](../../../concepts/security-concept-overview.md#why-use-azure-active-directory-to-protect-identities-in-your-organization)
- [Use the Azure AD identity protection API](identityprotection_root.md)