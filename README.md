# Sweet
Overview

This repository contains winning-rfp.clar, a Clarity smart contract designed to manage fair and transparent RFP (Request for Proposal) processes on the Stacks blockchain.

The goal is to allow organizations, such as Google Web3 initiatives or any enterprise, to issue open RFPs and award contracts on-chain in a tamper-proof, auditable, and community-driven way.

This contract uses a commit–reveal scheme, community scoring, and automatic winner selection to guarantee fairness.

✨ Key Features

Commit–Reveal Bidding
Vendors submit proposal commitments (SHA-256 hashes) during the commit phase, then reveal full details later to prevent plagiarism or sniping.

Evaluator Voting
A client-approved panel of evaluators cast scores (0–100) for revealed proposals.

On-Chain Transparency
All commitments, reveals, and votes are recorded immutably on the Stacks blockchain.

Automatic Winner Selection
After evaluation, the contract calculates the highest-scoring vendor and stores the winner permanently.

Pluggable Deposits & Escrow
Supports vendor deposits and can be extended to handle real token/STX escrow and payouts.

Enterprise-Ready
Designed for Web3 contract awards (Google Clarity pilots, ecosystem grants, DAOs, NGOs, enterprises).
