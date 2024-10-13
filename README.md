# Custom Common Vulnerability Scoring System, applicable to any environment required to run custom vulnerability evaluations - README.
## Overview

The Custom CVSS System is designed to address security vulnerabilities within a specific enterprise environment that are not yet identified by publicly known databases like CVE (Common Vulnerabilities and Exposures) or rated using CVSS (Common Vulnerability Scoring System). While public CVEs and their associated CVSS ratings provide a standardized approach for assessing the severity of well-known vulnerabilities, enterprises often encounter unique or environment-specific security risks that are not cataloged by global sources.

This system provides a customizable, scalable, and specific method to assess, score, and prioritize vulnerabilities based on their impact in your unique environment. By implementing your own Custom CVSS, you can develop a precise risk management framework, tailored to the assets, users, data, and configurations that are specific to your organization.

# Purpose

The Custom CVSS System serves the following main purposes:

1. Track Unique Vulnerabilities: Capture vulnerabilities specific to your organization that are not covered by public CVE repositories.
2. Tailored Risk Assessment: Customize vulnerability scoring by defining factors like access vector, privilege escalation impact, authentication requirements, user interaction, and confidentiality/integrity/availability impacts, based on your environment's needs.
3. Prioritize Based on Organizational Context: Assign higher or lower priorities to vulnerabilities based on their relevance and potential harm within your own infrastructure.
4. Enterprise-Specific Controls: Incorporate factors that are particularly relevant for your organization, such as internal network architecture, security controls, business impact, compliance requirements, and criticality of affected systems.
5. Refinement and Continuous Improvement: Continuously refine scoring criteria and adjust based on emerging threats, changes in infrastructure, or evolving security postures specific to your organization.

# Why Use a Custom CVSS System?

While publicly available CVEs and CVSS ratings are invaluable, they may not always reflect the specific risks an enterprise faces. Custom CVSS enables organizations to:

- Assess vulnerabilities that have not yet been identified or tracked in the public domain.
- Provide granular control over how vulnerabilities are rated and prioritized based on enterprise-specific contexts.
- Integrate business-critical factors that are not covered in standard CVSS scoring, such as financial impact, reputational damage, or operational disruptions.
- Empower internal teams to adopt a proactive approach by identifying vulnerabilities early and treating them according to their severity within the specific infrastructure.

# Goals of the Custom CVSS System

- Customization: Develop a CVSS scoring model that can be adapted to meet the specific requirements of your enterprise, whether by adding new criteria, adjusting impact weights, or refining assessment workflows.
- Scalability: Scale the vulnerability tracking system across different departments, assets, or regions, allowing for consistent risk scoring across a distributed enterprise environment.
- Accuracy: Provide a more accurate and relevant vulnerability risk assessment by focusing on specific system configurations, custom-built applications, and specialized hardware in use within the organization.
- Automation and Integration: Allow for automation of vulnerability assessments and integration with existing security systems, monitoring tools, and incident response platforms to streamline vulnerability tracking and mitigation efforts.
-  Continuous Improvement: Facilitate regular updates and refinements to the scoring model to reflect changing security landscapes, infrastructure updates, and new enterprise vulnerabilities.

By implementing a Custom CVSS System, you are equipped with the tools and flexibility to better manage the security risks specific to your environment, ensuring that vulnerabilities are identified, assessed, and remediated in a manner that aligns with your enterprise’s needs and priorities.
