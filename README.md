# My Audit Portfolio of All Valid Accepted Findings

## Table of Content

- [My Audit Portfolio of All Valid Accepted Findings](#my-audit-portfolio-of-all-valid-accepted-findings)
  - [Table of Content](#table-of-content)
    - [About Me (`alymurtazamemon`)](#about-me-alymurtazamemon)
  - [2023](#2023)
    - [Q3 Contests](#q3-contests)
      - [Allo V2](#allo-v2)
      - [Beedle - Oracle free perpetual lending](#beedle---oracle-free-perpetual-lending)
      - [Foundry DeFi Stablecoin](#foundry-defi-stablecoin)
      - [Amphora Protocol - A borrowing and lending protocol.](#amphora-protocol---a-borrowing-and-lending-protocol)
      - [PoolTogether - The permissionless protocol for saving and winning.](#pooltogether---the-permissionless-protocol-for-saving-and-winning)

### About Me (`alymurtazamemon`)

I am an Independent Smart Contracts Security Researcher at Code4rena and CodeHawks.

I started my auditing career in July 2023 from Code4rena contests.

Below you can find my all valid issues found during auditing contests to enhance your learning experience.

You can view my Profiles on:

-   [Code4rena](https://code4rena.com/@alymurtazamemon)
-   [CodeHawks](https://www.codehawks.com/profile/clk3q1mog0000jr082dc9tipk)

You can reach me out on:

-   [Twitter](https://twitter.com/alymurtazamemon)
-   [LinkedIn](https://www.linkedin.com/in/alymurtazamemon/)
-   [Discord](https://discord.com/users/alymurtazamemon#2063)

## 2023

### Q3 Contests

#### [Allo V2](https://audits.sherlock.xyz/contests/109)

- Contest Duration: 10 DAYS
- Dates: SEPT 11 2023 -> SEPT 21 2023
- Platform: [Sherlock](https://www.sherlock.xyz/)
- Findings:
  - [M-01: Incompatibility with deflationary / fee-on-transfer tokens](https://github.com/sherlock-audit/2023-09-Gitcoin-judging/issues/913)

#### [Beedle - Oracle free perpetual lending](https://www.codehawks.com/contests/clkbo1fa20009jr08nyyf9wbx)

- Contest Duration: 2 Weeks
- Dates: JUL 24 2023 -> AUG 07 2023
- Platform: [CodeHawks](https://www.codehawks.com/)
- Findings:
  - [H-01: Fee contract executes swap without slippage protection.](https://github.com/Cyfrin/2023-07-beedle/issues/677)
  - [M-01: Incompatability with deflationary / fee-on-transfer tokens.](https://github.com/Cyfrin/2023-07-beedle/issues/686)
  - [QA (Quality Assurance) Report](https://github.com/alymurtazamemon/audit-findings-storage/blob/main/codehawks/2023/beedle-july-23/beedle-july-23-quality-assurence-report.md)
  - [Gas Optimization Report](https://github.com/alymurtazamemon/audit-findings-storage/blob/main/codehawks/2023/beedle-july-23/beedle-july-23-gas-report.md)

#### [Foundry DeFi Stablecoin](https://www.codehawks.com/contests/cljx3b9390009liqwuedkn0m0)

- Contest Duration: 2 Weeks
- Dates: JUL 24 2023 -> AUG 05 2023
- Platform: [CodeHawks](https://www.codehawks.com/)
- Findings:
  - [H-01 (upgraded M -> H): We would not be able to incentivize the liquidators.](https://github.com/Cyfrin/2023-07-foundry-defi-stablecoin/issues/857)
  - [M-01 (downgraded H -> M): Broken getUsdValue function if considering all price feeds](https://github.com/Cyfrin/2023-07-foundry-defi-stablecoin/issues/390)
  - [M-02 (downgraded H -> M): DOS - Price feeds' Heartbeat is hardcoded](https://github.com/Cyfrin/2023-07-foundry-defi-stablecoin/issues/387)
  - [M-03: Users can mint more DSC than deposited collateral](https://github.com/Cyfrin/2023-07-foundry-defi-stablecoin/issues/793)
  - [M-04: Chainlink price staleness checks not complete](https://github.com/Cyfrin/2023-07-foundry-defi-stablecoin/issues/324)

#### [Amphora Protocol - A borrowing and lending protocol.](https://code4rena.com/reports/2023-07-amphora)

- Contest Duration: 1 Week
- Dates: JUL 22 2023 -> JUL 27 2023
- Platform: [Code4rena](https://code4rena.com/)
- Findings:
  - Grade-A - [QA (Quality Assurance) Report](https://github.com/code-423n4/2023-07-amphora-findings/issues/271)
  - Grade-B - [Gas Optimization Report](https://github.com/code-423n4/2023-07-amphora-findings/issues/412)

#### [PoolTogether - The permissionless protocol for saving and winning.](https://code4rena.com/reports/2023-07-pooltogether)

- Contest Duration: 1 Week
- Dates: JUL 08 2023 -> JUL 15 2023
- Platform: [Code4rena](https://code4rena.com/)
- Findings:
  - Grade-A - [QA (Quality Assurance) Report](https://github.com/code-423n4/2023-07-pooltogether-findings/issues/410)
  - Grade-A - [Gas Optimization Report](https://github.com/code-423n4/2023-07-pooltogether-findings/issues/401)