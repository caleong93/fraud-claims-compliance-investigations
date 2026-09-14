# Week 1 — Day 2: Fraud Investigation Application Scenarios

## Objective

Apply the fraud investigation fundamentals from Day 1 to realistic scenarios involving transaction fraud, account takeover, application fraud, employee fraud, and first-party fraud.

Core principle:

> The investigator follows the evidence—not the suspicion.

---

## Scenario 1 — Transaction Fraud

### Facts

- 4-year-old account
- Normal monthly debit-card spending: $1,200–$1,800
- Six transactions totaling $9,400 in one day
- All six transactions occurred within 35 minutes
- Luxury retailers
- Approximately 300 miles from the customer's home
- Customer had never used these merchants before
- All transactions approved successfully
- Customer had not reported unauthorized activity

### Investigation Assessment

**Red flags identified:**
- Major spending increase compared with normal activity
- Six high-value transactions within 35 minutes
- Luxury/new merchants
- Geographic inconsistency with the customer's normal location

**Investigative questions:**
- Did the customer make or authorize the transactions?
- Was the customer traveling in the transaction area?
- What was purchased?
- Does the transaction history show similar spending or merchant activity?

**Evidence identified:**
- Transaction history
- Authentication/device/login information
- Customer statement/interview
- Location information where available
- Merchant records or transaction details

**Priority:** High, because of significant financial exposure and potential ongoing activity.

**Disposition at this stage:** Continue investigation and consider escalation to the appropriate fraud/security function.

### Challenge Lesson

A customer stating that they were in California and made the purchases does not automatically resolve the concern. The statement is evidence, but should be corroborated with transaction details, location, purchase information, and historical activity.

---

## Scenario 2 — Account Takeover

### Facts

- Password changed at 2:13 AM
- Email changed at 2:16 AM
- Phone number changed at 2:18 AM
- New device never previously associated with the account
- Ten minutes later, a new external bank account was added
- $7,500 transfer initiated
- Customer normally uses an iPhone
- New activity came from an unfamiliar Android device

### Investigation Assessment

**Red flags identified:**
- Multiple security changes within minutes
- New/unrecognized device
- Change from normal device profile
- New external bank account
- $7,500 transfer shortly after account changes
- Highly compressed sequence of events

**Investigative questions:**
- Did the customer authorize the account changes?
- Does the customer still control the original phone number and email?
- Did the customer use the Android device?
- Did the customer authorize the external account and transfer?
- Is the external account associated with the customer?

**Evidence identified:**
- Authentication logs
- Device information
- IP/location information where available
- Account-change audit logs
- External bank-account information
- Transfer details
- Customer statement

**Priority:** High.

**Immediate protective action:** Consider appropriate account restrictions, transfer holds, enhanced authentication, and escalation according to institutional procedures.

### Key Lesson

Account takeover investigations require attention to both **unauthorized access** and the sequence of security changes and financial activity that follows it.

---

## Scenario 3 — Application Fraud

### Facts

- $25,000 loan application
- Reported income: $125,000
- Employer: ABC Consulting
- Reported employment: 6 years
- Baltimore address
- Employer could not initially be verified
- Reported income significantly higher than available verification
- Phone number recently associated with another loan application
- Second application used a different name but the same mailing address

### Investigation Assessment

**Red flags identified:**
- Employment could not initially be verified
- Income discrepancy
- Shared phone number with another application
- Different applicant name using the same mailing address

**Competing hypotheses:**
1. The applicant may be providing fraudulent information to obtain credit.
2. The second applicant may be a legitimate person who shares the address or household.

**Investigative evidence:**
- Compare the two applications
- Verify applicant identity
- Verify employment and income
- Investigate the second application
- Investigate the phone number association
- Interview the applicant if necessary

**Recommended investigative sequence:**

1. Compare applications for common identifiers and inconsistencies.
2. Verify the identity of each applicant.
3. Verify employment and income.
4. Determine the relationship between applicants.
5. Investigate the shared phone number.
6. Conduct interviews if material questions remain.

### Challenge Lesson

A shared address and phone number do not automatically establish application fraud. In the challenge scenario, John and Jane Smith were married and lived together. John actually worked for ABC Consulting, and his verified income was $118,000 rather than $125,000. The income difference could be an error rather than fraud.

### Key Lesson

Red flags can be explained by legitimate circumstances. Evidence may resolve an indicator without establishing fraud.

---

## Scenario 4 — Employee Fraud

### Facts

- 18 high-value electronics missing
- Items were last recorded in inventory
- Employee A performed an inventory count
- Employee A had stockroom access
- Employee A worked several closing shifts
- Manual inventory adjustments were made using Employee A's credentials
- One portion of the stockroom had no CCTV coverage
- Employee A denied taking the merchandise
- Two other employees had stockroom access
- One other employee had inventory-system access but denied making adjustments

### Investigation Assessment

**Red flags and investigative concerns:**
- High-value inventory loss
- Employee A performed inventory count
- Employee A had physical access
- Multiple closing shifts
- Manual adjustments using Employee A's credentials
- CCTV gap
- Multiple employees had relevant access

**Investigative scope:**
- Employee A
- Other employees with stockroom access
- Employees with inventory-system access
- Inventory system
- CCTV coverage
- Relevant receiving/shipping/transfer records

**Evidence identified:**
- CCTV footage
- Inventory adjustment logs
- System/credential logs
- Receiving records
- Shipping records
- Transfer records
- Inventory count records
- Employee interviews if necessary

**Competing hypotheses:**
1. Employee theft.
2. Administrative or inventory-record error without theft.
3. Receiving, shipping, transfer, or count error.
4. Another employee or unauthorized person used the relevant access.

**Disposition at this stage:** Continue investigation. Do not conclude that Employee A committed theft solely because A's credentials were used.

### Key Lesson

System credentials show that an account was used; they do not necessarily establish who physically performed the action. Access is not the same as responsibility.

---

## Scenario 5 — First-Party Fraud

### Facts

- Customer receives a credit card with a $15,000 limit
- Customer spends $14,700 within three weeks
- Purchases include electronics and jewelry
- Customer makes only minimum payments
- Customer then stops paying
- Customer claims unexpected financial hardship
- Internal records show a recent second credit application
- Second application contains substantially different income information
- Customer has not disputed the purchases

### Investigation Assessment

**Red flags identified:**
- Nearly maxed credit line within three weeks
- $14,700 in rapid spending
- Electronics and jewelry purchases
- Minimum payments followed by complete nonpayment
- Recent second credit application
- Substantially different income information
- No disputes regarding purchases

**Competing hypotheses:**

**Potential fraud hypothesis:**
The customer obtained credit with the intention of not repaying the resulting debt.

**Legitimate/innocent hypothesis:**
The customer experienced genuine financial hardship and used available credit before becoming unable to pay.

**Evidence identified:**
- Original credit application
- Second credit application
- Income verification
- Credit application history
- Credit history
- Payment history
- Purchase/merchant records
- Bank account statements
- Customer interview
- Account-opening and spending timeline

### Critical Intent Question

Before concluding first-party fraud, the investigator must establish evidence supporting **deception and intent**, rather than relying only on the fact that the account eventually defaulted.

The investigator should determine whether evidence shows that the customer:

- Knowingly provided false information to obtain credit
- Materially misrepresented income or employment
- Had a plan to obtain credit without repayment
- Had already decided not to repay when obtaining or using the credit
- Applied for multiple sources of credit as part of a deliberate strategy
- Concealed material financial information

At the same time, investigators should consider evidence supporting legitimate hardship, such as prior good payment behavior, documented income loss, or other circumstances inconsistent with an intentional nonpayment plan.

### Key Lesson

**High debt ≠ first-party fraud.**

**Default ≠ first-party fraud.**

**Financial hardship ≠ first-party fraud.**

The investigator must establish evidence of deception and intent rather than treating a negative financial outcome as proof of fraud.

---

# Day 2 Investigator Takeaways

## Skills Practiced

- Identifying fraud indicators
- Converting red flags into investigative questions
- Selecting relevant evidence
- Prioritizing investigations
- Developing competing hypotheses
- Sequencing investigative steps
- Distinguishing system activity from individual responsibility
- Testing innocent explanations
- Evaluating intent in first-party fraud
- Determining when escalation or continued investigation is appropriate

## Investigator Principles Reinforced

1. A red flag is an indicator, not proof.
2. A customer statement is evidence, not automatically the final answer.
3. Access does not equal responsibility.
4. Competing hypotheses reduce confirmation bias.
5. Evidence should be relevant to the investigative question.
6. Innocent explanations must be tested rather than dismissed.
7. Investigative sequencing matters.
8. Default or financial loss does not automatically establish fraud.
9. First-party fraud requires careful consideration of deception and intent.
10. The investigator follows the evidence—not the suspicion.

## Day 2 Completion

**Status:** Completed

**Scenarios completed:** 5/5

**Areas covered:**
- Transaction fraud
- Account takeover
- Application fraud
- Employee fraud
- First-party fraud

**Primary development area:** Continue improving investigative sequencing—determining which evidence should be examined first and why.

**Next:** Week 1 Day 3 — Case Lab: CASE 001 — Suspicious Transactions
