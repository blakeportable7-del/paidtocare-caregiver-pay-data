# Family Caregiver Pay by U.S. State, 2026 (PaidToCare)

This dataset covers which U.S. states and the District of Columbia pay family members to provide care through Medicaid, VA or state programs, whether an adult child or a spouse can be the paid caregiver, the program to ask about, the intake phone number and, where an official page publishes one, the pay rate.

Published by PaidToCare (https://paidtocare.org/), an independent public resource run by Willow Creek Group LLC, St. Clairsville, Ohio. It is not a government agency.

## How it was made

Each row was checked individually against official sources only: state Medicaid, aging, utility commission and water utility pages, statutes, administrative code and federal agency pages. Every fact carries its official source and the date it was checked. Where an official page does not state something, the dataset says so (for example "Not confirmed" or "Unknown") rather than guessing.

Rules change. Check the official source in each row before relying on a value.

## Files

### states-that-pay-family-caregivers.csv

Summary table, one row per state and DC: whether an adult child and a spouse can be paid, the main program, the intake phone, the official source and the date checked.

51 rows. Columns:

- `State`
- `Adult child can be paid`
- `Spouse can be paid`
- `Main program`
- `Intake phone`
- `Official source`
- `Last checked`
- `State guide`

### family-caregiver-pay-2026.csv

Full table, one row per state and DC: every program type checked (structured family caregiving, self-direction, VA programs, state-funded), the spouse and relative rules with quoted rule text, published pay rates where an official page states one, who qualifies, the first call to make, sources, and which fields are unverified.

51 rows. Columns:

- `state`
- `abbr`
- `structured_family_caregiving`
- `self_direction`
- `va_pcafc`
- `va_vdc`
- `state_funded`
- `family_can_be_paid`
- `spouse_rule`
- `other_relatives_rule`
- `rule_quotes`
- `published_rate`
- `rate_note`
- `rate_source`
- `rate_checked`
- `who_qualifies`
- `first_call`
- `what_to_have_ready`
- `program_sources`
- `va_sources`
- `source_status`
- `date_checked`
- `unverified_fields`
- `fully_verified`
- `adult_child_paid`
- `spouse_paid`
- `in_confirmed_count`

## Live version

The data is maintained on these pages, which may be newer than this release:

- https://paidtocare.org/states-that-pay-family-caregivers/
- https://paidtocare.org/report/family-caregiver-pay-2026/

## How to cite

PaidToCare (2026). Family Caregiver Pay by U.S. State, 2026 [Data set]. Zenodo. Use the DOI shown on the Zenodo record for this release.

## License

CC BY 4.0. Reuse with credit to the publisher above.

Release prepared 2026-10-27.
