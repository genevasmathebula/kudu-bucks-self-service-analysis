
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
