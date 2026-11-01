# UI/UX Design Essentials Lab: SwiftPay Design Audit

A "Shift Left" review of the SwiftPay **Send Money** flow. The Figma mock-up was audited for UI, UX and accessibility (WCAG 2.1 AA) problems before any code is written.

## Deliverable

**[SwiftPay Design Audit Report](SwiftPay-Design-Audit-Report.md)** contains:

- the completed Design Audit Report table: **12 issues**, each with a description, a type and a justification that cites a module concept;
- annotated evidence for every issue;
- the measured contrast ratios behind each accessibility finding;
- a prioritised list of fixes.

## Repository layout

| Path | Contents |
|---|---|
| [`UX-Accessibility Design Audit.md`](UX-Accessibility%20Design%20Audit.md) | Lab brief, instructions and grading rubric |
| [`SwiftPay-Design-Audit-Report.md`](SwiftPay-Design-Audit-Report.md) | The audit report |
| [`SwiftPay-Design-Audit-Report.docx`](SwiftPay-Design-Audit-Report.docx) | The same report in the Word "Audit Report Template" format, for submission |
| [`evidence/`](evidence/) | One annotated image per issue (red boxes mark the problem) |
| [`screenshots/`](screenshots/) | Unmodified exports of the audited Figma frames |

## Issues at a glance

| # | Issue | Type |
|---|---|---|
| 1 | Balance amount is blue on blue (1.32:1) | Accessibility |
| 2 | "Continue" button switches from blue to green within the flow | UI |
| 3 | Processing overlay gives no feedback | UX |
| 4 | Form labels at 25 % opacity (1.34:1) | Accessibility |
| 5 | Back button at 15 % opacity, 20 × 20 px target | Accessibility |
| 6 | Grey beneficiary card, low-contrast tiny "Change" link | Accessibility |
| 7 | Uneven spacing, misalignment and "OR" divider on the method list | UI |
| 8 | Success screen omits the beneficiary name; text styled as links | UX |
| 9 | 8 px receipt text | Accessibility |
| 10 | Icon-only controls and logos have no accessible names | Accessibility |
| 11 | Balance formatted as `20,000,00.00` | UX |
| 12 | eNaira alias and transaction type differ between screens | UX |

## Author

Josephus Mupanda
