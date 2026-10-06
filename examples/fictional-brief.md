# Fictional example: Harborboard reservation holds

This brief and every associated image are fictional. They exist only to demonstrate the skill's output shapes.

## Feature boundary

Harborboard is an imaginary scheduling product. Its new reservation hold flow lets a staff member reserve a room temporarily before confirming a booking. The fictional product uses navy `#183047`, teal `#117D87`, warm amber `#EAA34A`, and a clean sans-serif type style.

## Completed behavior

- Staff can create a 30-minute hold from the room calendar. The form shows room, date, time, and requester.
- The calendar and hold list show a teal **On hold** state and the expiry time.
- Confirming a hold turns it into a booking; cancelling frees the room. Both actions ask for confirmation.
- Staff without booking permission can view holds but cannot confirm or cancel them.
- In this fictional scenario, the create, confirm, cancel, and permission cases passed their scripted checks.

## Remaining work

- Reminder emails before expiry are planned but are not implemented.
- Bulk cancellation is outside this release.

## Open decision

- Should staff be able to extend a hold once? A one-time extension may help with complex requests, but could block room availability longer. The product owner has not selected a policy.

## Next available steps

1. Draft reminder email copy and delivery timing; this work can start now.
2. Resolve the extension policy before implementing an Extend button.
3. After the reminder work is built, test delivery failures and the expiry boundary.

## Example capture

The accompanying `fictional-calendar.png` is an illustration of this imaginary product, not evidence of a real implementation.
