# Harborboard reservation holds - technical SDN

*Fictional example. All names, checks, and links refer to the fictional brief in this repository.*

## 1. Summary

- **Done:** Staff can create a 30-minute room hold, see its status and expiry, and confirm or cancel it. View-only staff cannot take those actions. [Feature brief: completed behavior](fictional-brief.md#completed-behavior)
- **Checked:** The fictional create, confirm, cancel, and permission cases passed scripted checks. No production deployment is claimed. [Feature brief: completed behavior](fictional-brief.md#completed-behavior)
- **Left:** Reminder emails are planned; bulk cancellation is outside this release. [Feature brief: remaining work](fictional-brief.md#remaining-work)

## 2. Decisions needing answers

- **Can staff extend a hold once?** A one-time extension may help complex requests, but could block room availability longer. The product owner has not selected a policy. [Feature brief: open decision](fictional-brief.md#open-decision)

## 3. Next available steps

1. **Ready now:** Draft reminder email copy and delivery timing. [Feature brief: next available steps](fictional-brief.md#next-available-steps)
2. **Waiting on a decision:** Set the extension policy before adding an Extend button. [Feature brief: open decision](fictional-brief.md#open-decision)
3. **After reminder implementation:** Test delivery failures and the expiry boundary. [Feature brief: next available steps](fictional-brief.md#next-available-steps)
