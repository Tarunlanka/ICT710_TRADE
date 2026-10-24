# Fund Transfer Flow

## Usability problem
The baseline assessment identifies fund transfer as a high-priority task: 60% completion, 96 seconds mean time, and five errors in the simulated results. Ambiguous direction labels can make it difficult to understand which account is sending and which account is receiving funds.

## Proposed flow
1. Select **Add Money** or **Withdraw**.
2. Select the source account.
3. Select the destination account.
4. Enter the amount.
5. Review the source, destination, amount, fees, and estimated arrival.
6. Confirm the transfer.
7. Show a confirmation receipt with a reference number.

## Error prevention
- Use explicit labels: **From** and **To**.
- Repeat the direction in the review screen, e.g. “From Everyday Account → To Trading Account.”
- Prevent submission when required fields are missing.
- Explain validation errors next to the relevant field.
- Provide a clear cancel/back action before confirmation.

## Validation plan
This is a proposed design, not a proven improvement. Test with representative users and record completion, time on task, errors, and confidence. Compare results with the baseline only if the test conditions are comparable.
