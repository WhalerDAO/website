---
title: An Update on TREE
---

Hey all,

We wanted to take a quick moment to explain what happened today and how to proceed going forward.  

### This Situation:
This morning the TREE and WhalerDAO team had planned to do a live launch of the TREE token and deploy farming contracts.  We started to notice several errors during our first attempt and quickly realized that we would need to take time to triage the problem.  We told the community they could drop, and we would provide an update once the pools were fixed and back up.

Several hours later, after amazing support from contributors and community members, we were able to deploy the original contracts.

### The Problem:
Once we deployed them, we, unfortunately, found an error - the LP rewards pool was misconfigured.  The impact of the error meant that no one was able to stake their LP tokens for the TREE rewards.  Additionally, as the TREE contract is designed to prohibit the contract owners from arbitrarily minting new TREE, minting new TREE and making a new pool was not an option.

Since LP staking is integral to the project’s success, we realized that we needed to fix this bug for us to proceed.  At this point, we concluded that the best way to accomplish this was to redeploy all staking contracts and the TREE contract.

### What Happened:
At this point, we asked anyone who had staked tokens in the original contracts to remove all liquidity.  Once we had confirmed that all liquidity was removed, we went ahead and redeployed the contracts.  At this point, the contracts went live for staking.

### Current State:
The contracts are now live, and you should be able to stake (including directly from our frontend).

### The Outcome
Looking back on how the events went down, we know we let the community down on the biggest pillar, communication.  We apologize for not providing more transparent communication on the project’s status and what you all should’ve expected.  

At WhalerDAO and TREE, our goal has always been to find a way to use DeFi to fund public goods and charitable causes.  That is a significant directive and one that asks for a lot of trust and support from the community.  

We apologize to all the community members who felt like they missed out on this opportunity due to the lack of communication.  We hope that we’re able to repair that trust with you all.

We will be posting more about what happened and what’s next for WhalerDAO and TREE in the coming days.  Going forward, we plan to increase communication from our end to ensure we keep everyone on the same page.  

Please don’t hesitate to reach out if you have any questions.

Thanks and have a great weekend,
WhalerDAO

P.S.  We want to give a massive **Thank You** to all our community members that spent their day helping us triage and triage the issues with TREE.  You all are the real MVPs.