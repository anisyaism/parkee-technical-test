# parkee-technical-test
This repo created for Parkee Technical Test. 

> [!Tip]
> How to see test case directly You can click Example Test Case Title or **:link: [Click Here Test Case](https://docs.google.com/spreadsheets/d/1pC5mRWiIYH7dOAQQW8bb_XUxgLeCbAzmV4u9VlPFBAE/edit?usp=sharing)**
> <br>You can also download the Excel file in this Repository.

# :pushpin: [About Parkee](https://parkee.app/en/about-us)
PARKEE is a parking payment system solution (available on mobile and desktop) that utilizes digital technology to transform the parking industry in Indonesia. One of PARKEE's missions as a parking industry startup is to transform traditional
paper-based parking methods into paperless ones.

# :writing_hand: User Story
PARKEE has created a feature called 'Online Receipt', so parking service
users no longer need to keep parking payment receipts in paper form, but only need to scan
the barcode displayed on the parking machine at the exit gate, and you can view the details
of the parking transaction you just made.

# :fleur_de_lis: Feature Name
Online Parking Receipt

# :gear: Objective
Verify and validate the **Online Parking Receipt** is generated after a completed parking session, correct transaction parking details, entry/exit gate, entry/exit time, duration, amount of paid match with the user story or  acceptance criteria

#  :white_check_mark: Acceptance Criteria
1. **Online Receipt** is generated after successful payment
2. Parking detail information such as Entry/Exit Gate, Entry/Exit Time, Duration, Parking fee etc are appeared
3. Parking fee calculation correct based on the Duration and Location
4. No Duplicate Online Receipt Ticket Number / Receipt Number
5. Parking fee handle when the Duration time less than 1 hour or more the max of parking
6. Status of payment and payment method are appear correctly

# :test_tube: [Example Test Cases](https://docs.google.com/spreadsheets/d/1pC5mRWiIYH7dOAQQW8bb_XUxgLeCbAzmV4u9VlPFBAE/edit?usp=sharing)
| Test Case ID | Test Case Description     | Pre-Condition | Label  | Test Step(s)                    | Expected Result              | Actual Result     | Status | 
|:-------------|:--------------------------|:--------------|:-------|:--------------------------------|:------------------------------|:------------------|:-------|
| TCRCPT-001        | Verify that "Online Receipt" will be generate when user Scan QR Code in the Exit Gate and successfully PAID   | User already Login on the APP   | Positive Case  | 1. Click "QR" icon on the homepage<br>2. Scan the QR Code in the Exit Gate<br>3. Successfully Paid    | Successfully Generate the Online Receipt   | As expected       | ✅ Pass|

Thank you :pray:


