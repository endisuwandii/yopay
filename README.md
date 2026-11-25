# YoPay — Problem Statement

## 1. Problem Statement

Digital payment systems allow users to transfer and manage money conveniently. However, users may experience problems when transactions fail, are processed more than once, or result in inconsistent balance records.

These issues can reduce user trust, particularly when a transaction's status is unclear or the balance displayed does not accurately reflect the actual transaction history.

YoPay aims to address these challenges by providing a reliable simulated digital wallet system that prioritizes transaction integrity, consistency, and transparency.

The system will focus on ensuring that transactions are processed correctly, duplicate transactions are prevented, and wallet balances remain consistent with recorded transaction histories.

The project will simulate core wallet functionalities, including top-up and money transfer, while exploring backend mechanisms such as transaction lifecycle management, idempotency, ledger-based accounting, reconciliation, and failure handling.

## 2. Supporting Evidence and Engineering Approach

### Supporting Evidence

Based on research into official GoPay and DANA documentation, as well as educational materials from Bank Indonesia, there are documented scenarios involving failed or interrupted transactions, deducted balances, unclear transaction statuses, and refund processes that require additional time.

These findings indicate that transaction uncertainty and failure handling are relevant concerns in digital payment systems. However, the available sources do not establish how frequently these problems occur.

### Engineering Approach

No single mechanism can absolutely guarantee that transaction failures will never occur. Therefore, digital payment systems need to combine several engineering mechanisms to maintain transaction integrity and handle unexpected conditions.

The mechanisms YoPay will explore include:

- **Idempotency:** Prevents duplicate transaction processing when the same request is submitted repeatedly.
- **Atomic Transactions:** Maintains consistency across related database operations, particularly balance updates.
- **Concurrency Control:** Handles simultaneous transactions safely to prevent conflicting balance updates.
- **Transaction State Management:** Tracks transaction progress and handles uncertain transaction statuses.
- **Ledger and Transaction History:** Maintains traceable records of balance movements.

The effectiveness of these mechanisms will be evaluated through testing involving transaction failures, duplicate requests, and concurrent transactions.