---
title: Cloud Enablement - VPN solutions Service Scope | UKCloud Ltd
description: Outlines important details regarding Cloud Enablement for VPN solutions
services: enablement
author: Steve Hall
reviewer:
lastreviewed: 23/07/2018 11:55:40
toc_rootlink: Service Scope
toc_sub1: 
toc_sub2:
toc_sub3:
toc_sub4:
toc_title: Cloud Enablement - VPN solutions Service Scope
toc_fullpath: Service Scope/enbl-sco-vpn.md
toc_mdlink: enbl-sco-vpn.md
---

# Cloud Enablement - VPN solutions Service Scope

## About this document

This document describes the Cloud Enablement services available for VPN solutions. For information regarding CPA-approved (or equivalent standard) VPN solutions, see the relevant service scope.

## About Cloud Enablement

The Cloud Enablement service provides basic facilities for your own hardware installed in our data centre for the purpose of utilising our cloud.

The table provides an overview of the Cloud Enablement services available for VPN solutions. If the usage scenario you need isn't shown in the table, contact us to discuss your requirements.

&nbsp; | &nbsp;
-------|-------
**Use case** | You don't want to use the vCNS Edge VPN capability and want to  install your own
**Service type** | Connectivity
**Security level** | Assured OFFICIAL
**Hosted device** | VPN
**Typical device size** | 1U / 2U
**Service level (default)** | Single data centre, no automatic failover
**Cloud Enablement requirement<br>(one bay = 10U, 1kW per month)** | One bay in one UKCloud data centre
**Cost** | £2,000 setup fee plus £500 per month
**Resilience available?** | We don't provide a resiliently connected environment. You can provision devices to both of our data centres to create a  self-managed resilient solution (in which case the resilience options below are required).
**Failover responsibility** | Customer
**Resilience requirement<br>(1 bay = 10U, 1kw per month)** | One bay in our Farnborough data centre<br>One bay in our Corsham data centre
**Resilience cost** | £4,000 setup fee plus £1,000 per month
**Notes** | Devices must be hosted in the same region as your compute environment. We cannot stretch connectivity from local Cloud Enablement into other regions (eg Cloud Enablement in region 5 cannot be stretched to region 6)
**Next steps** | Raise a service request via the [My Calls](https://portal.skyscapecloud.com/support/ivanti) section of the UKCloud Portal

## What connectivity does the VPN service provide?

The VPN service provides up to two ports:

- Cloud Enablement in regions 1, 2, 7 & 8 offers fibre-only connectivity

- Cloud Enablement in regions 5 & 6 offers connectivity via SFP, so customers can use fibre or copper

- The connection is into a shared switch.

## What is the port speed of connection?

- In regions 1, 2, 7 & 8, the port speed is up to 1 Gbps

- In regions 5 & 6, the port speed can be either 1Gbps (copper or fibre) or 10 Gbps (fibre only)

## Who manages the switch?

We manage the shared switch - the initial logical configuration is included in the setup fee. Additional configuration (of your devices to your solution) is a chargeable service.

## Is there any switch redundancy within a rack?

We don't currently offer switch redundancy.

## What's included in the setup fee?

### The setup fee covers

- Escorting you for the physical installation of your hosted device(s) for up to four hours during the standard working week (Monday to Friday, 0900 - 1700)

- Logical configuration between our cloud and the hosted device(s)

- One VLAN

- Cabling from the rack to our cloud

### The setup fee doesn't cover

- Installing your device(s)

- Configuring your device(s)

- Non-standard design of your solution

- Peripheral consumables such as brackets, cable ties, cage nuts, power cords and intra-rack cabling

- Tools for installing your device(s)

## What's included in the monthly fee?

### The monthly fee covers

- Physical hosting of your device(s), including power and connectivity

- Four escorted visits a year by you for scheduled maintenance to your hosted device(s)

### The monthly fee doesn't cover

- Maintenance of your device(s)

- Support and management of your device(s)

- Unscheduled maintenance access

- Installation and configuration of additional device(s) in your solution (this is a chargeable service)

## What happens in the event of a power failure?

If, in the unlikely event of a power failure, you would like your hardware restarted, provide **laminated** worked instructions (totalling no more than a double-sided A4 page) that you can place within your Cloud Enablement rack space.

## Feedback

If you find an issue with this article, click **Improve this Doc** to suggest a change. If you have an idea for how we could improve any of our services, visit the [Ideas](https://community.ukcloud.com/ideas) section of the [UKCloud Community](https://community.ukcloud.com).
