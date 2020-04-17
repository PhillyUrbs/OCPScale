# Lab 1: Prerequisites

In the lab you will complete all the necessary prerequisites to build out a Windows Virtual Desktop environment.

*NOTE: If you already have an Office 365 subscription with an Enterprise Mobility + Security (EMS) E5 license environment, please complete only Exercise 1.*

If you do not have an Office 365 subscription with an Enterprise Mobility + Security (EMS) E5 license environment, please complete all exercises.

## Azure subscription

Your will need an Azure subscription to complete the Windows Virtual Desktop labs.  The following are ideal subscription types to utilize:

* Visual Studio Enterprise subscription
* IUR (Azure Use Rights) from your partner organization

**Microsoft does not recommend using any Azure subscription that has production workloads or services.  Use a subscription that is designated for testing purposes only.**

If you are using IUR, contact the subscription administrator at your partner organization.  The can provision your identity into the subscription and assign the appropriate rights.

## Rights assignments

Your identity within your subscription must have the following rights assignments:

* **Global administrator** permissions within the Azure Active Directory tenant.
  * This also applies to Cloud Solution Provider (CSP) organizations that are creating a Windows Virtual Desktop tenant. If you're in a CSP organization, you must be able to sign in as global administrator.
  * The administrator account must be sourced from the Azure Active Directory tenant in which you're trying to create the Windows Virtual Desktop tenant. This process doesn't support Azure Active Directory B2B (guest) accounts.
  * The administrator account must be a work or school account
* Ensure that the user who will provision & configure WVD must have at least **Contributor** rights to the Azure subscription.
  * Based on the operating model, some customers might not have this enabled so contact your CSP-Partner who can help with the same.

## Exercise 1 - Install Windows Virtual Desktop PowerShell Module

Complete these steps to install the Windows Virtual Desktop PowerShell module:

1. To quickly download and install the Windows Virtual Desktop PowerShell module, launch PowerShell as an administrator and run the following command:

    `Install-Module -Name Microsoft.RDInfra.RDPowershell`

    *Type **Y** when prompted for installing from an untrusted repository.*



### Return to [Prepare Phase Labs](prepare.md)
