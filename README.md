# Aergo Bug Bounty Program

Please carefully review these **rules**, as they will govern any report you submit.

## Reports

Please provide detailed reports with reproducible steps. If the report is not detailed enough to reproduce the issue, the report will not be eligible for a reward. Please consider (1) attack scenario / exploitability, and (2) security impact of the vulnerability.

Researchers may only submit one vulnerability per report, unless there is a need to chain vulnerabilities to provide impact.

When multiple researchers identify and report the same underlying issue, we will award any applicable bounty to the first eligible report that was received.

Vulnerabilities that we are aware of already will not be rewarded.

Reports that identify multiple vulnerabilities caused by one underlying issue will be awarded at most one bounty.

Issues identified by a reporter will be paid at most only once, even if the same issue can be exploited on multiple in-scope assets or on contracts deployed across multiple chains.

## Searching for Potential Vulnerabilities

Researchers may not impact production systems in a negative way for any testing.

All smart contract testing should be done either in a local network on on the public test network (testnet).

Social engineering (e.g. phishing, vishing, smishing) is prohibited.

Avoid privacy violations, destruction of data, and interruption or degradation of our service. Only interact with accounts you own or with explicit permission of the account holder.

Failure to adhere to any of the terms in this section will make you ineligible for a bug bounty reward.

## In scope vulnerabilities

Aergo Foundation is interested in vulnerabilities that affect the integrity of the Aergo blockchain and the Lua smart contract engine.

Currently, the following issues are considered in scope

Exploits that affect the Lua smart contract engine, in a way that:

- Allows an attacker to steal funds from an account or contract.
- Allows an attacker to interfere on how a smart contract is expected to work (functions, assertions, etc.).
- Allows an attacker to modify the state of a smart contract.
- Allows an attacker to freeze, disable or destroy a smart contract.

(the above obviously refers to smart contract that you do not own. You can deploy smart contracts to try to interfere with others)

Exploits that affect the Aergo blockchain, in a way that:

- Allows an attacker to steal funds from an account or contract.
- Makes the blockchain stop working with specially crafted transactions.

## Out of scope vulnerabilities

All the other assets that are not mentioned in the [In scope vulnerabilities](#in-scope-vulnerabilities) section are considered out of scope.

This includes DoS attacks, spamming, phishing, etc.

## Disclosure Policy

To ensure that any disclosure of vulnerabilities happens in a responsible manner, do not discuss any vulnerabilities (even resolved ones) outside of the program without express consent from the Aergo Foundation. Failure to adhere to the Disclosure Policy will result in the forfeiture of any eligible reward.

To report a vulnerability, please send an email to [tech@aergo.io](mailto:tech@aergo.io)

You can also chat with us about technical questions on [Discord](https://discord.com/invite/YuPCCeH)

## Rewards

The bounties are separated in 3 categories:

1. Exploits that can move, create or destroy funds (tokens) without authorization
2. Exploits that can make a smart contract or the network to stop working
3. Exploits that can interfere with the normal behavior of a smart contract

The rewards are:

| Vulnerability | Bounty |
| --- | --- |
| Critical | $5,000 |
| High | $3,000 |
| Medium | $1,000 |
| Low | $250 |

The Aergo Foundation will determine at its discretion whether a reward should be granted and the amount of the reward. Rewards may be reduced or denied if the submission is incomplete or inaccurate and does not allow us to quickly reproduce and validate the finding.

## Safe Harbor

Any activities conducted in a manner consistent with this policy will be considered authorized conduct and we will not initiate legal action against you for such authorized conduct.

Thank you for helping keep the Aergo blockchain and our community safe!
