---
id: maintenance
title: Validator Node Maintenance
sidebar_label: Node Maintenance
---

## Updating a Validator Node

NEAR is an evolving protocol, with nodes software that will change over time. In a decentralized network we need coordination between end-users, the platforms they use, developers and validators. More specifically, a validator is responsible to create new blocks, so every update needs coordination with other validators to avoid any network stall.

Consider this document a constant work in progress, and use it for a better coordination with other validators and the network in general.

## Planned Updates

NEAR merges node updates for [nearcore](https://github.com/nearprotocol/nearcore) as follows:
- DevNet as needed, from `main` branch, with a features freeze on (Tuesday? at 00:00 UTC)
- BetaNet every Wednesday at 00:00 UTC (merging some or all DevNet new features) from `beta` branch
- TestNet every first Monday of the month at 00:00 UTC (merging BetaNet new features) from `stable` branch
- MainNet via voting (merging TestNet new features) from the previous `stable` branch

In case of critical issues, MainNet may need an emergency update via hard fork, with an accelerated schedule deploying any hotfix to DevNet and then MainNet. At the current stage, with MainNet under PoA, the process is handled entirely by NEAR, with a rotation of core developers 24/7.
The network will not transition to MainNet Restricted until an emergency update process has been defined with validators, and tested multiple times.

<blockquote class="warning">
<strong>heads up</strong><br><br>

Your best testing grounds are BetaNet, where we update and hard fork the network every week. Technically, we merge the new release of nearcore into beta branch every Tuesday at 00:00 UTC, we run it for 24 hours on DevNet, and then we deploy it on BetaNet, on Wednesday at 00:00 UTC.
In case critical issues emerge during DevNet testing, the Core team will rollback the release, but will hard fork BetaNet anyway.

</blockquote>


This document covers three main aspects of validating node maintenance:

1. Coordinate with the community
2. Deploying from source code
3. Backup and restore local data

## 1.Coordinate with the community

## 2.Deploying from source code

## 3.Backup and restore local data


