# Fictional & Co — Systems & SaaS Review

**Project:** SME Operations & Finance Improvement Case Study  
**Role:** Operations Transformation Manager

## Purpose

This review assesses Fictional & Co's current systems and identifies where existing tools should be retained, improved, integrated, automated or replaced.

The objective is not to introduce more technology for its own sake. The focus is on supporting stronger financial visibility, cost control, process consistency and scalability before Site 5.

---

## Review Principles

The systems review follows five principles:

1. **Keep what works** — do not replace stable systems without a clear business case.
2. **Fix the process first** — poor processes should not be automated without redesign.
3. **Reduce duplicate handling** — avoid entering or reconciling the same information repeatedly.
4. **Improve visibility** — systems should support timely management decisions.
5. **Scale proportionately** — solutions should fit a growing SME, not an enterprise operating model.

---

## Systems Assessment

| Area | Current Tool / Method | Assessment | Decision | Rationale |
|---|---|---|---|---|
| Accounting | Xero | Core accounting platform is suitable for the current business | Retain | Stable system; improvement is needed around surrounding workflows rather than accounting software replacement |
| POS / Sales | Cloud-based POS | Sales data is available but not connected efficiently to finance reporting | Improve / Integrate | Reduce manual exports and improve consistency between trading and financial reporting |
| Budgeting | Excel / Google Sheets | Flexible but manually maintained | Improve | Retain spreadsheet-based budgeting initially, but standardise templates, ownership and version control |
| Cash Flow Forecasting | Google Sheets | Useful but highly manual | Improve / Automate | Standardise inputs and explore automated feeds for recurring cash items |
| Supplier Invoices | Email + Xero | Fragmented intake and manual processing | Improve / Automate | Centralise invoice intake and consider invoice capture / approval workflow |
| Purchasing | Direct site ordering | Limited central visibility of commitments | Improve / Introduce Workflow | Add lightweight approval and PO / approved-spend controls |
| Supplier Management | Spreadsheet | Incomplete pricing, ownership and contract information | Improve | Create a structured supplier register before considering specialist software |
| Expenses | Email / receipts | Manual submission and approval process | Improve / Automate | Introduce structured expense capture and approval workflow |
| Payroll | External provider | Specialist processing already outsourced | Retain | No material system problem identified |
| Contracts | Google Drive + spreadsheet | Renewal tracking is inconsistent | Improve / Automate | Centralise contract register and introduce automated reminders |
| Documents | Google Drive | Suitable shared storage platform | Retain / Improve Governance | Improve folder structure, ownership and naming conventions |
| Communication | Email + WhatsApp | Useful operationally but poor for traceable decisions | Improve Governance | Define which decisions and approvals must be recorded in formal channels |
| CRM / Projects | Basic CRM | Limited role in current case study | Review | Retain if fit for purpose; clarify ownership and use before changing tools |
| Management Reporting | Xero + POS + spreadsheets | Manual and fragmented | Improve / Integrate | Standardise data inputs and build a repeatable dashboard process |

---

## Recommended Systems Direction

### Retain

The following systems should remain in place:

- Xero
- Existing POS platform
- External payroll provider
- Google Drive
- Spreadsheet-based budgeting in the short term

The business does not currently require a full systems replacement programme.

---

## Improve

The following areas need better structure before new technology is introduced:

### Supplier Register

Create a central supplier record containing:

- supplier owner,
- category,
- agreed pricing,
- payment terms,
- contract dates,
- renewal dates,
- notice periods,
- approved status.

### Contract Register

Create a structured contract register with clear ownership and reminder dates.

### Budgeting

Standardise:

- site templates,
- account categories,
- ownership,
- review cadence,
- version control.

### Management Reporting

Define:

- KPI ownership,
- data sources,
- reporting cadence,
- exception thresholds,
- action tracking.

---

## Integrate

### POS to Management Reporting

Sales data should feed the management reporting process more consistently.

The first phase does not need to be a complex technical integration.

Options could include:

- scheduled standard exports,
- structured data imports,
- API connection if supported and justified,
- or a reporting tool connecting both data sources.

The priority is reducing manual consolidation and improving consistency.

---

## Automate

Automation should focus first on repetitive, rules-based activity.

### 1. Invoice Capture

Potential automation:

- extract supplier,
- invoice date,
- invoice number,
- net / VAT / gross,
- site,
- nominal category,
- payment terms.

Human review should remain for exceptions and coding judgement.

### 2. Invoice Approval Routing

Invoices could be routed automatically based on:

- site,
- value,
- supplier,
- cost category,
- approval authority.

### 3. Contract Renewal Reminders

Automatic notifications at defined intervals before renewal or notice dates.

Example:

- 90 days,
- 60 days,
- 30 days.

### 4. Supplier Price Variance Alerts

Flag significant deviations from:

- agreed price,
- previous purchase price,
- expected monthly baseline.

### 5. Management Reporting Refresh

Where possible, reduce repeated manual imports and calculations through standardised data feeds and templates.

---

## AI Opportunities

AI should support administrative and analytical tasks rather than replace management judgement.

### Appropriate Uses

**Invoice classification support**

Suggest coding or cost categories based on previous patterns.

**Management commentary support**

Summarise material KPI movements for Finance or Operations review.

**Supplier document extraction**

Extract renewal dates, notice periods and commercial terms from contracts for human validation.

**Exception identification**

Help identify unusual cost movements or recurring operational patterns.

---

## Activities That Should Remain Human-Led

The following decisions require business judgement:

- supplier selection,
- contract negotiation,
- budget approval,
- unusual expense approval,
- staffing decisions,
- interpretation of performance,
- site investment decisions,
- final accounting review.

Automation should improve information and reduce repetitive administration, not remove accountability.

---

## Potential SaaS Requirements

Rather than selecting specific vendors immediately, Fictional & Co should define requirements first.

### Invoice / AP Workflow

Required capabilities could include:

- dedicated invoice intake,
- OCR / invoice capture,
- duplicate detection,
- approval routing,
- Xero integration,
- site / cost centre coding,
- audit trail.

### Purchasing Workflow

Required capabilities could include:

- purchase requests,
- approval thresholds,
- PO creation,
- committed spend visibility,
- supplier controls,
- budget reference.

### Expense Management

Required capabilities could include:

- mobile receipt capture,
- approval workflow,
- coding,
- VAT capture,
- Xero integration.

### Reporting

Required capabilities could include:

- POS data input,
- Xero data input,
- site-level reporting,
- KPI calculation,
- exception reporting,
- trend analysis.

---

## Prioritisation

| Priority | Initiative | Reason |
|---|---|---|
| 1 | Standardise supplier invoice process | High admin burden and control risk |
| 2 | Improve purchasing approvals / committed spend visibility | Direct cost-control benefit |
| 3 | Standardise management reporting | Improves management visibility across all sites |
| 4 | Strengthen supplier and contract data | Supports negotiation and cost control |
| 5 | Improve cash-flow inputs | Better forward visibility |
| 6 | Automate expenses | Useful efficiency gain but lower strategic priority |

---

## Implementation Approach

Fictional & Co should avoid changing several systems at once.

A phased approach is recommended:

### Phase 1 — Process and Data Foundations

- supplier register,
- contract register,
- approval rules,
- KPI definitions,
- reporting ownership,
- consistent data structures.

### Phase 2 — Workflow Automation

- invoice capture,
- invoice approvals,
- purchasing controls,
- renewal reminders.

### Phase 3 — Integration and Reporting

- reduce manual data transfer,
- improve POS / finance reporting connection,
- automate dashboard refresh where practical.

---

## Expected Impact

The recommended systems approach should:

- reduce repetitive administration,
- improve financial visibility,
- strengthen purchasing and approval controls,
- improve supplier management,
- shorten reporting cycles,
- improve auditability,
- and support growth without creating unnecessary system complexity.

---

## Key Recommendation

Fictional & Co does not need a large-scale digital transformation programme.

The strongest opportunity is to combine better-defined processes with targeted automation and integration around the systems the business already uses.

The next stage of the case study will translate these recommendations into a practical 90-day implementation roadmap.
