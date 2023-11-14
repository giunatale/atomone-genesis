# Preamble

This document is being edited live here:
https://docs.google.com/document/d/1UlZJ3Ud4M0uUeBtnEHofEVgj07Sq7n56jAN_DIiNzLU/edit?usp=sharing

# Declaration of Genesis

There comes a time when there is too much disagreement among community members
about how to move forward, that it makes the most sense to have an alternative
fork running on standby to prepare for all contingencies.

This seems like a natural and necessary way to split the community to enable a
diverse ecosystem of specialization and coopetition, without unnecessary
friction--for as long as contrarians can stay within their respective zones and
not disrupt others who wish to flee from you. Please respect the constitution.

TODO: add more in the spirit of the Declaration of Independence 1776.

For sake of bootstrapping we go straight into the plan, and segments of
specifications to show the intended end goal is.

# Objectives

See https://x.com/jaekwon/status/1719437899429761420?s=20

1. Define $ATOM: The staking token of the largest minimal ICS IBC Cosmos Hub
   that keeps 2/3 of ATOMs staked.
2. Hub minimalism, and most importantly without a complex VM implementation on
   the root shard, but rather forcing VMs to live on non-root shards. This is
   the only way to scale to billions of users.
3. Fix Validator incentives so that every validator is PAID to run ICS consumer
   chains and hub shards. Actually model the minimal economic model that
   describes physical reality sufficiently to be intuitive and adaptive to all
   scenarios. Every ICS pays supermajority to validators!
4. Fix governance. We already have proposals in the works on github
   decentralists DAO / governance. Contribute there so that Governance is fixed
   and we stop spending money like a flock of headless geese.
5. Fix "liquid staking". What we have isn't liquid staking, they are
   "partyhubs". What people want are liquid fungible tokens that aren't so
   inflationary, I get it. ICS scaling will fix the problem, but if you really
   want more, fix LS to delegate pro-rata, NOT have its own gov. Or, over time,
   possibly create a bicameral gov structure w/ exponentially inflating $ATOM
   stakers, and limit how $PHOTON reverts to $ATOM to prevent hostile takeover.
   VP(staked $ATOM) >= VP(all $PHOTON).
6. Adopt a Declaration of Independence and Constitution with cryptographic
   signatures.
7. Solve IBC1.5, or ICS1.5, where the validator sets are implicit, for fast
   inter-hub communication with implied IBC, WITHOUT sacrificing independent
   BFT consensus layers.
8. Create a permissioned and completely accountable and 100%
   predetermined-finite-time-delayed transparent security reporting system
   where ABSOLUTELY EVERYTHING within it eventually becomes public knowledge to
   help deal with zero day vulnerabilities and current attacks & fund it.
9. Create and support competing marketing, growth, infra, dapp subDAOs, and
   especially help them foster the best in class in Cosmos; from the user level
   down to the VM, every component should have a good selection of competition.
10. Create a team tasked with minimizing and simplifying code and reducing
    unnecessary dependencies, taking the best examples from various forks taken
    into consideration, so that all the best ideas from all forks can integrate
    into one where-ever possible. FINISH software.
11. Ossify the partyhub after it has become its own competing IBC/ICS hub.
    Allow others to likewise fork from you by enabling ICA partyhubs when there
    is disagreement. Multiply by meiosis and conquer the world.

## 1. Define $ATOM

## 2. Hub Minimalism

## 3. Validator Incentives

## 4. Governance

See
[github.com/decentralists/DAO](https://github.com/decentralists/DAO/tree/main/governance)

## 5. "Liquid Staking"

## 6. Declaration of Independence & Constitution

See https://github.com/tendermint/atom_one

## 7. IBC1.5

## 8. Transparent Security System

## 9. Fund SubDAOs

See https://gitub.com/gnolang/gno

## 10. Engineering Task Force

See https://github.com/gnolang/gno/tree/master/tm2 for Tendermint2

## 11. Enable Meiosis

See https://github.com/gnolang/gno/pull/1224 for prototype WIP 
 

It should be some distribution of the Cosmos Hub, with those who voted against
the spirit of this project removed.  Additionally, the Interchain Foundation
playing a key role in the evolution of the hub, should also be removed.  In
return, 10% of the ATOMs can go to DAOs to be managed on chain with specific
objective key results mandated.

# Plan

The AtomOne hub exists as a separate minimalist fork of Gaia. Both are separate
and distinct from gno.land, though gno.land and the GnoVM (as well as other
VMs) will play significant roles in completing the hub and maintaining its
upkeep.

The main goal is to fix what must be fixed in governance and the need for an
explicit constitution, before launching the full IBC and ICS functionality of
the chain.

First we describe the tokenomics of the atomone hub, followed by the main
milestones, with an emphasis on completion and even phase-out.

## Tokenomics

### ICS Fee Distribution

Every ICS zone should be paid for somehow. AtomOne owned ICS shards should be
paid for from the treasury of AtomOne.  Other ICS "consumer chains" can be paid
for by the the chain itself, and in emegencies anyone can step in and pay on
the zone's behalf. 

In short, every ICS zone should be profitable to every validator.

The DISTRIBUTION_FRACTION parameter is the fraction (between 0 and 1) of ICS
shard and consumer chain payments that are shared among the validators equally.
This is initially set to 0.8, giving the majority to the validators, and only
20% as royalty to be paid to ATOM1 stakers, with the COMMUNITY_TAX taking its
portion.

### Photon w/ AutoStaking

## AtomOne Governance

Ultimately this hub is owned by the $ATOM1 holders. 

We will prioritize all of these items:
[github.com/decentralists/DAO](https://github.com/decentralists/DAO/tree/main/governance)

## Milestones

There are largely four phases to this plan.

### AtomOne Phase 1: Pre-IBC

1. Define Constitution
2. Governance Fixes
3. Launch Governance-Only Chain
4. Implement IBC

### AtomOne Phase 2: Post-IBC

1. $PHOTON with Auto-Staking
2. Fix Validator Incentives
3. Implement ICS1.5
4. Prototypes with SubDAOs (including GNO)

### AtomOne Phase 3: ICS1.5 scaling

1. Migrate $PHOTON to ICS
2. Promote Smart Contract Use Cases
3. Develop Scalable Validator Infrastructure
4. Develop Recovery Preocedures

### AtomOne Phase 4: Maintenance

1. Create OnChain Education Curriculum
2. Promote Good Forks and Projects
3. Promote Other Common Goods
4. Finalize the Software

Finalization should not be seen as a thing to avoid, but rather a necessity for
preserving immutability and thus providing real security benefits.

Everyone who wants something different is given a way to create their own
variation to compete and cooperate with the atomone hub. We should all be
familiar with this concept, as it is how atomone itself was born--by exodus
from Gaia.

It is possible that what we arrive at is not sufficient in the long run, and
that is still OK; the ultimate goal is to be a standard reference, in the very
least in relation to an improved fork; a reference that will last a thousand
years or more.

In short, the goal is nothing more than to create timeless code, even knowing
that in the end even atomone will be phased out, but never forgotten; the
template will have split into a million different forks and conquered the
world.

AtomOne Eschatology will be well documented and planned, for a time when nobody
was around for these early beginnings.

# FAQ

## AtomOne vs Gaia

## AtomOne vs Gno.land

## AtomOne & AIB

## AtomOne & Tendermint2
