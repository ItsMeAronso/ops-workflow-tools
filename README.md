# Operations AWB Smart Router

## Business Context
During my work in logistics operations (Unilog), I noticed the team spent unnecessary time manually identifying Air Waybill (AWB) carriers and navigating to various external portals to track time-sensitive shipments. This manual process was repetitive and prone to delays.

## The Solution
I developed this lightweight, internal web-based tool to eliminate the manual routing process. The team simply pastes the AWB string, and the tool uses Regular Expressions (Regex) to instantly identify the carrier (UPS, FedEx, DHL) and generate a direct URL to the exact tracking page.

## Technical Details
* **Frontend:** HTML, CSS (Clean UI focused on operational speed).
* **Logic:** Vanilla JavaScript.
* **Mechanism:** Regex pattern matching for global logistics providers.

## Operational Impact
* **Efficiency:** Eliminated manual data entry and carrier-guessing for the ops team.
* **Adoption:** Designed as a simple UI tool so non-technical team members could integrate it instantly into their workflow without training.
