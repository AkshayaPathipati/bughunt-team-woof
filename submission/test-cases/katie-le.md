# Test Cases: [Katie Le]

**Team number:** [woof]

<!--
HOW TO USE THIS FILE
1. Copy this file. Name the copy with your first name and last initial, like  maria-g.md
2. Leave TEMPLATE.md untouched for your teammates.
3. Write at least ONE failing test case. More is better.
4. Copy the block between the lines for each new test case.
5. Test IDs: use your initials plus a number, like  MG-01, MG-02. This keeps IDs unique across your team.
6. See docs/TESTING_FIELD_GUIDE.md for the sample test case TC-00.
-->

---

**Test ID:**
KL-01
**Written by:**
Katie Le
**Title:**
Password of length 4 characters accepted
**Traces to:**
REQ1
**Test type:** (Security)
**Preconditions:**
unique username
**Test data:**
Name: Kitty_Cat
Password: 1234
**Steps:**
1. Type in a unique username 
2. Type in a password 
3. Click create account

**Expected result:**
"Invalid username or password."
**Actual result:** 
"Account created! You can log in now."
**Status:** (Fail)
**Severity:** (Critical)
**V or V:** (Verification)

---

**Test ID:**
KL02
**Written by:**
Katie
**Title:**
Voting for the same costume
**Traces to:**
REQ11
**Test type:**
Acceptance ID
**Preconditions:**
created an account (username and password)
**Test data:**
Costumes exists (Zombie Barista)
Logged In
**Steps:**
1. Create an account
2. Log in
3. Go to votes page
4. click vote underneath costume

**Expected result:** 
Cannot vote for the same costume
**Actual result:**
allows them to vote for the same costume
**Status:**
Fail
**Severity:**
Major
**V or V:**
Verification
---
