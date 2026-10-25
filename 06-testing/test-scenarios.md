
# Test Scenarios: Kudu Bucks Self-Service Top-Up

## Purpose
These test scenarios describe how the proposed self-service top-up solution could be checked to determine whether it meets the documented business and user requirements.

This is a conceptual portfolio project. The scenarios have not been executed against a real system.

## Test Scenarios

| Test ID | Scenario | Expected Result | Related Requirement |
|---|---|---|---|
| TS01 | Student accesses the top-up service and authenticates successfully. | The student is authenticated and the correct Kudu Bucks account is identified. | FR01, FR07 |
| TS02 | Student enters a valid top-up amount. | The system accepts the amount and displays the details for review. | FR02 |
| TS03 | Student completes a digital payment successfully. | The system confirms the payment and updates the Kudu Bucks balance accordingly. | FR03, FR04, FR05 |
| TS04 | A digital payment fails. | The system displays a failure message and provides appropriate next steps. The balance is not increased for the failed payment. | FR04, FR06 |
| TS05 | A payment is still processing and its outcome is unknown. | The system communicates the pending status and avoids initiating a duplicate payment while the original transaction is being checked. | FR04, NFR01 |

## Assumptions and Limitations

- The test scenarios are proposed and have not been executed.
- The actual payment provider and Kudu Bucks integration have not been confirmed.
- These scenarios would need to be reviewed and expanded with relevant stakeholders before real system testing.


## Detailed Test Cases

| Test ID | Test Data / Action | Expected Result | Priority |
|---|---|---|---|
| TC01 | Attempt to access the service without authenticating. | The system prevents access to account-specific information and prompts the student to authenticate. | High |
| TC02 | Enter a valid positive top-up amount within the supported limits. | The system accepts the amount and displays it for review before payment. | High |
| TC03 | Enter an amount of R0. | The system rejects the amount and explains that a valid amount is required. | High |
| TC04 | Enter a negative top-up amount. | The system rejects the amount and does not initiate payment. | High |
| TC05 | Complete a payment successfully. | The system confirms the transaction and updates the correct Kudu Bucks account balance once. | High |
| TC06 | Simulate a failed payment. | The system displays an appropriate failure message and does not increase the balance for the failed transaction. | High |
| TC07 | Simulate a payment with an unknown or pending outcome. | The system displays the pending status and checks the original transaction before allowing another payment attempt. | High |
| TC08 | Attempt to continue after authentication fails. | The system prevents access to the protected top-up process and displays an appropriate message. | High |


## Testing Notes

- These are proposed test cases, not executed tests.
- Supported top-up limits, authentication rules and payment-status handling must be confirmed with stakeholders.
- Actual execution would require an appropriate test environment and test payment integration.
