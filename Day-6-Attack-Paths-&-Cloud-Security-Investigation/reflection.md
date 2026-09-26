# Week 5 Day 6 – Microsoft Defender for Cloud Attack Paths

## Objective
The goal of this lab was to learn how Microsoft Defender for Cloud uses Attack Paths to identify highrisk security issues and potential paths that attackers could use to reach important resources.
I also learned how to review affected resources, risk levels, recommendations, and the relationship between multiple security weaknesses.

## Lab Environment
- Microsoft Azure
- Microsoft Defender for Cloud
- Azure resources in HomelabRG
- Azure Portal

## Tasks Completed
During this lab, I:
- Reviewed the Attack Paths section in Microsoft Defender for Cloud.
- Reviewed the available attack path information.
- Examined affected resources.
- Reviewed risk levels.
- Reviewed active security recommendations.
- Learned how multiple security weaknesses can contribute to an exploitable attack path.
- Considered how recommendations can help reduce potential security risks.
- Learned why attack paths should be investigated before making security changes.

## Understanding Attack Paths

Attack Paths help identify highrisk security issues and potential paths that an attacker could use to move through an environment or reach an important resource.

This gives an administrator additional information about how different security weaknesses may be connected.

Attack Paths can help an administrator prioritize remediation efforts based on the potential risk associated with the path.

## Information Available in Attack Paths

When reviewing Attack Paths, information can include:
- Total attack paths
- Affected resources
- Active recommendations
- Risk levels
- Security issues contributing to the path

Risk levels can be categorized using levels such as:
- Critical
- High
- Medium
- Low
This information helps an administrator understand which potential attack paths require closer attention.

## Attack Paths vs Security Recommendations
Attack Paths and security recommendations have different purposes.

Attack Path:
Identifies a potential highrisk path created by connected security weaknesses.

Security Recommendation:
Provides guidance on how to address a security issue and improve the security posture of the affected resource.

A simple way I understand the difference is:

Attack Path = Shows a potential route an attacker could use.
Security Recommendation = Provides guidance on how to address the security weakness.

## Importance of Identifying the Entry Point
Identifying the entry point of an attack path helps an administrator understand where the potential path begins.

This can help determine which resources may be exposed and what precautions may be needed to reduce the potential for an attacker to move further through the environment.

## Identifying the Target Resource

Identifying the target resource is important because it helps the administrator understand what the potential attack path could lead to.

This can help the administrator focus remediation efforts on the appropriate resources and reduce the potential for an attacker to reach sensitive resources.

## Multiple Security Weaknesses

Multiple security weaknesses can be connected and create a potential exploitable path for an attacker.

Looking at security issues individually may not always show the full risk. Attack Paths help provide additional context by showing how different weaknesses can be connected.

## How Recommendations Can Reduce Risk

Security recommendations can help administrators identify security issues that should be addressed.

Even when reviewing an individual recommendation, addressing the underlying weakness may help reduce the potential risk associated with an attack path.

The administrator should review the recommendation and understand its potential impact before making changes.

## Investigating Before Making Changes

It is important to investigate an attack path before making changes.

Investigation helps the administrator:
- Understand the affected resources
- Identify the potential entry and target resources
- Understand the security weaknesses involved
- Determine the appropriate remediation
- Follow organizational change management policies

This helps reduce the possibility of making an incorrect change that could affect other resources.

## Risk of Ignoring an Attack Path
If a high risk attack path is ignored and the underlying security weaknesses remain unresolved, an attacker could potentially use those weaknesses to reach sensitive resources.

This could increase the risk of unauthorized access, data exposure, or other security incidents.

## What I Learned

Today's lab gave me a more in depth understanding of Attack Paths and how to analyze affected resources and their associated recommendations.

I learned that multiple security weaknesses can be connected and create a potential path that could increase security risk.

I also learned how Attack Paths can provide additional context that helps administrators understand which security issues may require attention.

## Challenges

I did not experience any issues during today's lab.

## Screenshots
1. Attack Paths overview
2. Attack Path details
3. Affected resources

## Key Takeaways
- Attack Paths show potential high risk paths involving connected security weaknesses.
- Attack Paths can help administrators prioritize security investigations.
- Affected resources provide important information about where risks exist.
- Entry and target resources help explain the potential path.
- Multiple security weaknesses can contribute to one attack path.
- Security recommendations provide guidance for addressing individual weaknesses.
- Administrators should investigate before making changes.
- Organizational change management policies should be considered when implementing remediations.
