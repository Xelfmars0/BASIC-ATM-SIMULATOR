
# README for ATM Simulator

```markdown
# ATM Simulator

A Python-based ATM machine simulator that mimics real banking operations with a user-friendly command-line interface.

## Features

- **Balance Inquiry**: Check current account balance
- **Cash Deposit**: Deposit money into account with validation
- **Cash Withdrawal**: Withdraw money with sufficient balance check
- **Input Validation**: Robust error handling for invalid inputs
- **Continuous Operation**: Loop until user chooses to exit
- **Formatted Display**: Professional currency formatting

## Menu Options

1. **Check Balance** - View current account balance
2. **Deposit Money** - Add funds to your account
3. **Withdraw Money** - Retrieve cash from your account
4. **Exit** - End the banking session

## Usage

### Starting the ATM
```python
from atm_simulator import atm_machine

# Start the ATM simulation
atm_machine()

Validation Features
Numeric Input Check: Prevents crashes from non-numeric inputs

Positive Amount Validation: Ensures deposits and withdrawals are positive

Sufficient Balance Check: Prevents overdrafts

Menu Option Validation: Only accepts valid menu choices (1-4)

Initial Setup
Starting balance: ₦2,000.00

Currency: Nigerian Naira (₦)

No transaction limits (within available balance)

Requirements
Python 3.6+

No external dependencies required
