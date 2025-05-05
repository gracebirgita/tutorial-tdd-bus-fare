# TDD Exercise: Bus Fare Calculator

This project is a tutorial exercise to learn Test-Driven Development (TDD) using Python.

## Case Description

You are building a function `bus_ticket_price()` that calculates the fare of a bus ride based on several rules:

- Children under 2 ride for free.
- Children under 18 and seniors over 65 pay **half fare**.
- Others pay the **full fare of $3**.
- On weekdays (Mon–Fri), between **7–9am** and **4–6pm**, add a **$1.5 peak surcharge**.
- On **weekends**, flat fare is **$2** (except for children under 2).
- **Short trips** under 5 minutes during **off-peak** are free (except on weekends).
- On **public holidays**, a special **$2 holiday surcharge** is added (overrides other rules).

---

## Tasks

### Step 1: Red Phase – Write the First Test
Go to `tests/test_bus_fare.py` and write a test for:
> A 1-year-old child on a weekday should ride for **free**.

### Step 2: Green Phase – Implement Minimum Code
Go to `src/bus_fare.py` and write the minimum code to make the test pass.

### Step 3: Refactor
After the test passes, clean up the code to make it more readable and modular.

### Step 4: Add More Tests
Complete the test cases for:
- Teenagers
- Adults
- Seniors
- Weekend pricing
- Public holiday surcharge
- Short trip logic

Follow the template code provided.

---

## Run the Tests

```bash
python -m unittest discover -s tests
```

