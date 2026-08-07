# E-Commerce Profitability Calculator — Haider's Tailored

An interactive, web-based financial modeling tool built for **Haider's Tailored**, a real apparel business, to translate their static sales spreadsheet into dynamic, actionable strategy.

🔗 **[Try the live calculator](https://namoos99.github.io/E-Commerce-Profitability-Calculator-Haider-s-Tailored/interactive_profit_calculator.html)**

## The Problem

Haider's Tailoring's sales data lived in a spreadsheet: orders, return rates, and revenue by product line. It could tell them what already happened, but not what would happen if they changed pricing, cut returns, or pushed bundles. Like most small apparel businesses, they needed a way to see the financial impact of a strategic decision before making it, without building a model in Excel from scratch every time.

## What the Data Showed

Analyzing the actual sales data surfaced a clear priority. Across five product lines, return rates ranged from 20% to 36%, and the worst offender wasn't subtle:

| Product Line | Orders | Return Rate | Return Cost |
|---|---|---|---|
| Classic Chinos | 120 | 20% | $300 |
| Corduroy Slacks | 85 | 20% | $212.50 |
| Wool Dress Trousers | 110 | 30% | $445.50 |
| Slim-Fit Denim | 200 | 28% | $784 |
| **Baggy Cargo** | **450** | **36%** | **$2,430** |

Baggy Cargo was the highest-volume line and the highest return-rate line at the same time, making it the single largest margin drain in the business. That finding shaped which levers the calculator needed to model.

## The Solution

The calculator lets Haider's Tailoring run real-time sensitivity analysis across three levers that actually move apparel margins:

- **Strategic Markups** — modeling the effect of targeted price increases on proven, high-demand "hero" items
- **Return Rate Reduction** — calculating recaptured revenue from cutting returns (the largest margin-killer in the data) through better sizing guidance and fit optimization
- **AOV-Driven Bundling** — forecasting the margin lift from shifting purchases toward 2-packs and bundles, which reduces per-item acquisition and fulfillment cost

Adjusting the sliders shows, instantly, how a conservative 2% drop in returns or a 10% shift toward bundling compounds against the bottom line, using the business's own numbers instead of a hypothetical example.

## Technical Implementation

Built for immediate accessibility and zero-friction deployment, so a non-technical business owner can open it and use it with no setup.

- **Frontend:** HTML5, JavaScript (vanilla, no framework)
- **Styling:** Tailwind CSS via CDN for standalone functionality
- **UI/UX:** Custom high-contrast aesthetic (Google Fonts: Fredoka One, Montserrat; custom CSS geometry)
- **Architecture:** Entirely self-contained in a single HTML file — no build step, no package manager, no local server required

## How to Use

1. Open the [live calculator](https://namoos99.github.io/E-Commerce-Profitability-Calculator-Haider-s-Tailored/interactive_profit_calculator.html), or download `interactive_profit_calculator.html` and open it in any modern browser
2. Toggle strategies on or off and adjust the range sliders
3. Watch baseline profit vs. projected profit update in real time as each lever changes
