# Financial Transaction Processor (Racket)

A robust data processing engine designed to manage banking transactions, update account balances, and generate detailed financial statements. This project leverages the power of functional programming to ensure data integrity and predictable state transitions.

## Engineering Highlights

* **Functional Logic Engine:** Implemented using Racket to demonstrate high-level computational thinking, using recursion and immutable data structures for financial accuracy.
* **Batch Data Processing:** Built to parse and process external data files (`ACCOUNTS.TXT` and `TRANSACTIONS.TXT`) representing real-world business inputs.
* **Transaction Validation:** Handles multiple payment modalities (Cash, Check, Credit, Debit) and validates them against current account balances.
* **Automated Reporting:** Generates a comprehensive `STATEMENTS.TXT` output featuring chronological transaction histories, total expenditures, and final balance summaries.

## Tech Stack

* **Language:** Racket
* **Paradigm:** Functional Programming
* **Input/Output:** File-based Stream Processing (TXT/CSV)



---

## Installation and Usage

1. **Install Racket**:
   Download and install the Racket environment from [racket-lang.org](https://racket-lang.org/).
2. **Setup Project**:
   Clone this repository and ensure `ACCOUNTS.TXT` and `TRANSACTIONS.TXT` are in the project root.
3. **Execute**:
   Open the main script in **DrRacket** and press **Run**, or execute via terminal:
   ```bash
   racket financial_processor.rkt
4. **View Results: The program will automatically generate or update STATEMENTS.TXT in the same directory.**
