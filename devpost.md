# CowBet (Devpost archive)

Source: https://devpost.com/software/cowbet (saved 2026-11-03)

**Submitted to:** DeFi The Conventional
**Result:** Winner, Gaming Theme 1st Place
**Team:** Matthew Tran, Taha Jalili, Tate S
**Built with:** React, Rust

## Inspiration

People make easy bets all the time, but sometimes they don't follow through. With blockchain, no one can claim they "were only joking".

## What it does

Betting platforms exist on the blockchain, mostly as proof of concepts, but we wanted to add benefits to winners and losers in the form of farming rewards for the time that you have staked money in the bet (which is immutable). This gamifies the process, and since the stake is locked in, it increases liquidity in the fund and the more you put in, the more you farm, which is a guaranteed return no matter the outcome of your bet.

## How we built it

The front-end was meant to be coded in Terra.js and React and the backend used a template found on the InterWasm github for DAO voting, which we used to create the contract for 1) Receiving a bet during the deposit period (2-3 days), 2) Locking the users bet upon the completion of the Deposit period, and 2) Allowing users to claim their payout the winnings + Anchor rewards.

## Challenges we ran into

We had problems connecting wallets in React and working with Terra.js. We also ran into errors in the contract creation while trying to format the template to our needs.

## What's next for CowBet

We're hoping to be able to generalise the template so anyone can create a betting contract for events. This would allow users to have a portfolio of bets, allowing them to create net returns through farming and the mix of wins and losses while also benefiting the Terra environment by injecting liquidity.

Note: Didn't have time to upload a video, presenting live.
