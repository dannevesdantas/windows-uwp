---
title: Assign roles to account users
description: Learn how to assign standard roles when adding users to your Partner Center account.
ms.date: 11/09/2022
ms.topic: article
ms.localizationpriority: high
---

# Assign roles to account users

By default, a set of standard roles is presented for you to choose from when you add a user, group, or Azure AD application to your Partner Center account. Each role has a specific set of permissions in order to perform certain functions within the account.

Unless you opt to define [custom permissions](overview-of-custom-permissions-for-account-users.md) by selecting **Customize permissions**, each user, group, or Azure AD application that you add to an account must be assigned at least one of the following standard roles.

> [!NOTE]
> The **owner** of the account is the person who first created it with a Microsoft account (and not any user(s) added through Azure AD). This account owner is the only person with complete access to the account, including the ability to delete apps, create and edit all account users, and change all financial and account settings.

| Role                 | Description              |
|----------------------|--------------------------|
| Manager              | Has complete access to the account, except for changing tax and payout settings. This includes managing users in Partner Center, but note that the ability to create and delete users in the Azure AD tenant is dependent on the account's permission in Azure AD. That is, if a user is assigned the Manager role, but does not have global administrator permissions in the organization's Azure AD, they will not be able to create new users or delete users from the directory (though they can change a user's Partner Center role). **Note:** if the Partner Center account is associated with more than one Azure AD tenant, a Manager can’t see complete details for a user (including first name, last name, password recovery email, and whether they are an Azure AD global administrator) unless they are signed in to the same tenant as that user with an account that has global administrator permissions for that tenant. However, they can add and remove users in any tenant that is associated with the Partner Center account. |
| Developer            | Can upload packages and submit apps and add-ons, and can view the [Usage report](../usage-report.md) for telemetry details. Can access [Cross-Device Experiences](https://developer.microsoft.com/windows/project-rome) functionality. Can’t view financial info or account settings.   |
| Business Contributor | Can view [Health](../health-report.md) and [Usage](../usage-report.md) reports. Can't create or submit products, change account settings, or view financial info.   |
| Finance Contributor  | Can view [payout reports](/partner-center/payout-statement), financial info, and acquisition reports. Can’t make any changes to apps, add-ons, or account settings.    |
| Marketer             | Can [respond to customer reviews](../respond-to-customer-reviews.md) and view non-financial [analytic reports](../analytics.md). Can’t make any changes to apps, add-ons, or account settings.      |

The table below shows some of the specific features available to each of these roles (and to the account owner).

|                                                       |    Account owner                 |    Manager                       |    Developer                     |    Business Contributor    |    Finance Contributor    |    Marketer                      |
|-------------------------------------------------------|----------------------------------|----------------------------------|----------------------------------|----------------------------|---------------------------|----------------------------------|
|    **Acquisition report (including Near Real Time data)** |    Can view                      |    Can view                      |    No access                     |    No access               |    Can view               |    No access                     |
|    **Feedback report/responses**                          |    Can view and send feedback    |    Can view and send feedback    |    Can view and send feedback    |    No access               |    No access              |    Can view and send feedback    |
|    **Health report (including Near Real Time data)**      |    Can view                      |    Can view                      |    Can view                      |    Can view                |    No access              |    No access                     |
|    **Usage report**                                       |    Can view                      |    Can view                      |    Can view                      |    Can view                |    No access              |    No access                     |
|    **Payout account**                                     |    Can update                    |    No access                     |    No access                     |    No access               |    Can update             |    No access                     |
|    **Tax profile**                                        |    Can update                    |    No access                     |    No access                     |    No access               |    Can update             |    No access                     |
|    **Payout summary**                                     |    Can view                      |    No access                     |    No access                     |    No access               |    Can view               |    No access                     |

If none of the standard roles are appropriate, or you wish to limit access to specific apps and/or add-ons, you can grant custom permissions to the user by selecting **Customize permissions**, as described in the next page.
