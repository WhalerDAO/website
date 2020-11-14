---
title: "TREE 🌳 -- DeFi engine for charity funding"
date: 2020-11-13T20:01:01-07:00
draft: false
---

## What is TREE 🌳?

TREE intends to be a profitable engine for funding charitable ventures. We’re working to move value creation in DeFi to the most effective causes for doing good, inspired by [effective altruism](https://www.effectivealtruism.org/articles/introduction-to-effective-altruism/).

TREE is the first project from [WhalerDAO](https://whalerdao.org/). We're a DAO composed of people from [MetaCartel](https://www.metacartel.org/), [Govrn](https://www.govrn.io/), [Aragon](https://aragon.org/), [BrightID](https://www.brightid.org/), [Bacon Labs](https://baconlabs.dev/), [Status](https://status.im/), and other assorted projects.

## How does TREE 🌳 work?

TREE is an elastic supply token, meaning its supply will change based on its demand to maintain a roughly constant price. Existing examples include Ampleforth and Yam. During a positive rebase, additional tokens are minted, distributing rewards to the charity fund, the LP pool, and the reserve.

Every 12 hours, TREE will check its price against DAI. If it's higher than the peg (1 DAI), then additional TREE tokens are minted. 10% of the minted TREE will go to Uniswap liquidity providers, 10% will go to the charity fund, and 80% will be sold into DAI and sent to a reserve. These weights can be adjusted through governance.

![diagram of the Tree rebase process](https://i.imgur.com/LYCxv4H.jpg)

TREE tokens are also used as governance tokens to decide which charities the charity funds go to. We will be using an Aragon conviction voting DAO for decision-making.

Every TREE holder is also entitled to a share of the reserve. At any point, holders can burn their TREEs for a cut of the reserve proportional to the *square* of their current share of the total supply. This kind of quadratic burning incentivizes long-term holding and accumulation, because one person burning TREE makes everyone else's TREE worth more.

For example, say Alice and Bob both have 10 tokens, and the total supply is 100. Let's say the reserve has 500 DAI. If Alice burns first, she'll receive 1% of the 500 DAI reserve, which is 5 DAI. Now, if Bob burns next, Bob receives $\frac19^2 = \frac{1}{81} = 1.22\%$ of the remaining 495 DAI reserve, which is 6.05 DAI.

In this way, we hope to incentivize long-term participants in our ecosystem and provide an interesting "waiting game" dynamic for holders.

## How will TREE 🌳 be distributed?

TREE will have an initial supply of 12000, distributed across 10 yield-farming pools:

* The TREE-DAI Uniswap LP pool will be allocated 3000 TREEs.
* The following pools will be allocated 1000 TREEs each:
    1. PAN
    2. UNI
    3. YFI
    4. COMP
    5. WETH
    6. AAVE
    7. ANT
    8. BAL
    9. STAKE

The farming will begin at 12:00pm Pacific Time, November 20, 2020. It will last for 14 days.

## How to get updates on TREE 🌳?

Our [website](tree.finance) is where you'll be able to farm and burn TREEs.

You can follow us on [Twitter](https://twitter.com/tree_finance_) and join the conversation on the [WhalerDAO Discord](https://discord.gg/EE6ZveWDfV). A certain cheeky [Villager](https://twitter.com/trees4free) may also pique your interest...
