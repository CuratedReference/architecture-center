---
title: "Fusion: Understanding the Identity Baseline discipline within cloud governance"
description: Explanation of the concept Identity Baseline in relation to cloud governance
author: BrianBlanchard
ms.date: 1/4/2019
layout: LandingPage
ms.topic: landing-page
---

# Fusion: Identity Baseline discipline

Identity Baseline is one of the [Five Disciplines of Cloud Governance](../governance-disciplines.md) within the [Fusion Model to Cloud Governance](../overview.md). 

Identity is increasingly considered the primary security perimeter in the cloud, which is a shift from the traditional focus on network security. Identity services provide the core mechanisms supporting access control and organization within IT environments, and the Identity Baseline discipline complements the [Security Baseline discipline](../security-baseline/overview.md) by providing secure user authentication, controlling user access to cloud-based resources, and ensuring identity services work efficiently across your organization.

> [!NOTE]
> Identity Baseline governance does not replace the existing IT teams, processes, and procedures that allow your organization to manage and secure identity services. The primary purpose of this discipline is to identify potential identity-related business risks and provide risk-mitigation guidance to IT staff that are responsible for implementing, maintaining, and operating your identity management infrastructure. As you develop governance policies and processes make sure to  involve relevant IT teams in your planning and review processes.

This section of the Fusion guidance outlines the approach to developing an Identity Baseline discipline as part of your cloud governance strategy. The primary audience for this guidance is your organization's cloud architects and other members of your cloud governance team. However, the decisions, policies, and processes that emerge from this discipline should involve engagement and discussions with relevant members of the IT teams responsible for implementing and managing your organization's identity management solutions.

If your organization lacks in-house expertise in Identity Baseline and security, consider engaging with external consultants as a part of this discipline. Also consider engaging with [Microsoft Consulting Services](https://www.microsoft.com/en-us/enterprise/services?activetab=pillars%3aprimaryr13), the [Microsoft FastTrack](https://azure.microsoft.com/en-us/programs/azure-fasttrack/) cloud adoption service, or other external cloud adoption experts for discussion of Azure-specific concerns related to identity services.

## Policy statements

Actionable policy statements and the resulting architecture requirements serve as the foundation of an Identity Baseline discipline. To see policy statement samples, see the article on [Identity Baseline Policy Statements](./policy-statements.md). These samples can serve as a starting point for your organization's governance policies.

> [!CAUTION]
> The sample policies come from common customer experiences. To better align these policies to specific cloud governance needs, execute the following steps to create policy statements that meet your unique business needs.

## Developing Identity Baseline governance policy statements

The following six steps offer examples and potential options to consider when developing Identity Baseline governance. Use each step as a starting point for discussions within your cloud governance team and with affected business, and IT teams across your organization to establish the policies and processes needed to mitigate identity-related risks.

<ul  class="panelContent cardsE">
<li style="display: flex; flex-direction: column;">
    <a href="./template.md">
        <div class="cardSize">
            <div class="cardPadding" >
                <div class="card" >
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="../../_images/governance/process-template.png" class="x-hidden-focus"/>
                        </div>
                    </div>
                    <div class="cardText" style="padding-left:0px;">
                        <h3>Identity Baseline Template</h3>
                        <p class="x-hidden-focus">Download the template for documenting an Identity Baseline discipline</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li><li style="display: flex; flex-direction: column;">
    <a href="./business-risks.md">
        <div class="cardSize">
            <div class="cardPadding" >
                <div class="card" >
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="../../_images/governance/process-risks.png" class="x-hidden-focus"/>
                        </div>
                    </div>
                    <div class="cardText" style="padding-left:0px;">
                        <h3>Business Risks</h3>
                        <p class="x-hidden-focus">Understand the motives and risks commonly associated with the Identity Baseline discipline.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./metrics-tolerance.md">
        <div class="cardSize">
            <div class="cardPadding" >
                <div class="card" >
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="../../_images/governance/process-metrics.png" class="x-hidden-focus"/>
                        </div>
                    </div>
                    <div class="cardText" style="padding-left:0px;">
                        <h3>Indicators and Metrics</h3>
                        <p class="x-hidden-focus">Indicators to understand if it is the right time to invest in the Identity Baseline discipline.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./processes.md">
        <div class="cardSize">
            <div class="cardPadding" >
                <div class="card" >
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="../../_images/governance/process-enforce.png" class="x-hidden-focus"/>
                        </div>
                    </div>
                    <div class="cardText" style="padding-left:0px;">
                        <h3>Policy adherence processes</h3>
                        <p class="x-hidden-focus">Suggested processes for supporting policy compliance in the Identity Baseline discipline.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./maturity-adoption-alignment.md">
        <div class="cardSize">
            <div class="cardPadding" >
                <div class="card" >
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="../../_images/governance/process-maturity.png" class="x-hidden-focus"/>
                        </div>
                    </div>
                    <div class="cardText" style="padding-left:0px;">
                        <h3>Maturity</h3>
                        <p class="x-hidden-focus">Aligning Cloud Management maturity with phases of cloud adoption.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./toolchain.md">
        <div class="cardSize">
            <div class="cardPadding" >
                <div class="card" >
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="../../_images/governance/process-toolchain.png" class="x-hidden-focus"/>
                        </div>
                    </div>
                    <div class="cardText" style="padding-left:0px;">
                        <h3>Toolchain</h3>
                        <p class="x-hidden-focus">Azure services that can be implemented to support the Identity Baseline discipline.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
</ul>

## Next steps

Get started by evaluating [business risks](./business-risks.md) in a specific environment.

> [!div class="nextstepaction"]
> [Understand business risks](./business-risks.md)