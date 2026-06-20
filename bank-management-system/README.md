# Bank Management System

A simple console-based bank management app in Python. Stores account records locally using `pickle`.

## Features
- Create a new account
- Deposit / withdraw amount
- Balance enquiry
- Close an account
- Modify an account

## Run

```bash
python bank_management.py
```

No external dependencies — just Python 3.

## Note
Data is stored in a local `accounts.data` file (created automatically, ignored by git). This was an early practice project, not built for production use — no input validation or error handling.
