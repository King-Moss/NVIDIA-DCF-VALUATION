# NVIDIA Corporation (NVDA) — DCF Valuation

**Ticker:** NVDA | **Exchange:** NASDAQ | **Valuation Date:** 19 May 2026
**Data Source:** Macrotrends | **Methodology:** Discounted Cash Flow (FCFF)

---

## Company Overview

NVIDIA designs the semiconductors that train artificial intelligence. That single sentence explains why the company's revenue grew from $26.9B in FY2022 to $215.9B in FY2026, a 703% increase in four years. The H100 and B200 GPU families have become the de facto compute standard for large language model training, and every major hyperscaler (Microsoft, Google, Amazon, Meta) is spending aggressively to secure allocation. NVIDIA does not manufacture its chips, it designs them and outsources fabrication to TSMC, which means the business is almost entirely a software and IP story wrapped in a semiconductor ticker.

The fiscal year 2026 data used in this model reflects the first full year of Blackwell GPU revenue, which ramped faster than any product in the company's history.

---

## Investment Thesis

NVIDIA's current valuation is a bet on whether AI infrastructure spending is a cycle or a structural shift. This model takes the position that it is both and that understanding the distinction is where the real analytical work lies.

The cyclical component is real. Hyperscalers are building data centers ahead of demand they expect to materialise. There will be a period, likely in the 2027-2028 window, where GPU shipments decelerate sharply as the current build-out digests. The revenue growth rates in FY2024 (126%) and FY2025 (114%) will not repeat. The model's revenue forecast explicitly assumes a significant deceleration — FY2027 growth drops to approximately 81% under the optimistic scenario and the trajectory continues to taper through FY2031.

The structural component is what justifies the valuation. Three dynamics underpin it.

First, NVIDIA has built a software moat that is rarely discussed relative to the hardware. CUDA, the programming platform that runs on NVIDIA GPUs, has been around since 2006 and has accumulated a two-decade installed base of developers, libraries, and tooling. Switching from CUDA to a competing platform (AMD ROCm, Intel oneAPI, or custom silicon like Google's TPUs) is not a chip swap. It requires rewriting or recompiling model training pipelines that represent years of engineering investment. This switching cost is structural, not transient, and it explains why NVIDIA's data center segment gross margins have held above 70% even as revenue scaled dramatically.

Second, NVIDIA's product roadmap is accelerating, not plateauing. The Blackwell architecture (launched FY2026) succeeded Hopper (H100) in roughly 18 months. Rubin, the next architecture, is scheduled for 2026. Each generation roughly doubles compute performance per dollar, which means NVIDIA's customers have an ongoing incentive to upgrade even during soft demand periods. This is not a market where a customer buys once and waits, it is a market where the product obsoletes itself on a two-year cycle.

Third, NVIDIA is building a recurring software revenue layer through NVIDIA AI Enterprise, NIM microservices, and DGX Cloud. These products allow enterprises and cloud providers to deploy NVIDIA-optimised AI inference on existing hardware — and they carry subscription or consumption-based pricing that is structurally different from one-time chip sales. This layer is small today but is the mechanism through which NVIDIA could eventually look more like a platform company than a hardware vendor.

The bear case is straightforward. Custom silicon from hyperscalers (Google TPUs, Amazon Trainium, Microsoft Maia, Meta MTIA) is improving rapidly. If these alternatives reach 70-80% of NVIDIA's performance at 50% of the cost which is the trajectory several of them are on — enterprise customers will adopt them for inference workloads even if training stays on NVIDIA hardware. The model's conservative scenario assigns a WACC of 16% and a TGR of 2% precisely to capture this outcome: a world where NVIDIA's pricing power erodes and growth decelerates faster than the base case.

---

## Historical Financial Performance

All figures in USD millions unless stated.

| Metric | FY2022 | FY2023 | FY2024 | FY2025 | FY2026 |
|---|---|---|---|---|---|
| Revenue | 26,914 | 26,974 | 60,922 | 130,497 | 215,938 |
| Revenue Growth | 61.4% | 0.2% | 125.9% | 114.2% | 65.5% |
| EBIT | 10,041 | 4,224 | 32,972 | 81,453 | 130,387 |
| EBIT Margin | 37.3% | 15.7% | 54.1% | 62.4% | 60.4% |
| D&A | 1,174 | 1,544 | 1,508 | 1,864 | 2,843 |
| Capex | 976 | 1,833 | 1,069 | 3,236 | 6,042 |
| Net Income | 9,752 | 4,368 | 29,760 | 72,880 | 120,067 |
| Operating Cash Flow | 9,108 | 5,641 | 28,090 | 64,089 | 102,718 |

The FY2023 margin trough (EBIT of 15.7%) reflects the post-crypto gaming GPU collapse, not any structural deterioration. The recovery to 62.4% EBIT margins in FY2025 and 60.4% in FY2026 is driven almost entirely by data center GPU mix — H100 and Blackwell chips carry materially higher ASPs and margins than gaming GPUs.

Capex remains low relative to revenue (2.8% in FY2026) because NVIDIA is a fabless designer. TSMC bears the manufacturing capex. This is a key structural advantage that inflates NVIDIA's return on invested capital relative to integrated semiconductor companies like Intel.

---

## Forecast Assumptions

The model uses a 5-year explicit forecast period (FY2027-FY2031) with three scenarios. All switches are currently set to **Optimistic (Case 3)**.

**Revenue Growth Assumptions**

| Period | Conservative | Base | Optimistic (active) |
|---|---|---|---|
| FY2027 | -5% adj. to rolling avg | Rolling avg | +10% adj. to rolling avg |
| FY2028-FY2031 | -35% decel from prior yr | -30% decel | -25% decel |

The deceleration assumption is the most critical judgment in the model. Even the optimistic case assumes revenue growth decelerates substantially from the FY2025-FY2026 pace — this is intentional and reflects the reality that triple-digit growth rates cannot compound indefinitely on a $216B revenue base.

**EBIT Margin Assumptions**

| Period | Conservative | Base | Optimistic (active) |
|---|---|---|---|
| FY2027 | 3% adj. to hist. avg | Historical avg held flat | 2.5% adj. to hist. avg |
| FY2028-FY2031 | Stepdown to 50% | Held flat at 60.4% | Step-up to 68% |

The optimistic EBIT margin assumption (reaching 68% by FY2031) reflects continued software and services mix-shift. The conservative case (declining to 50%) reflects competitive erosion from custom silicon alternatives.

**Tax Rate:** Normalised to 15.0% (conservative) / 15.1% (base and optimistic) across the forecast period, reflecting NVIDIA's historical effective rate trend.

**Forecast Revenue (Optimistic Case)**

| FY2027E | FY2028E | FY2029E | FY2030E | FY2031E |
|---|---|---|---|---|
| $390.4B | $545.8B | $806.4B | $1,162.0B | $1,637.4B |

---

## WACC

| Component | Value | Source |
|---|---|---|
| Risk-free rate (Rf) | 4.58% | US Treasury (Trading Economics) |
| Equity beta | 2.20 | Yahoo Finance |
| Market risk premium (MRP) | 4.46% | Damodaran |
| Cost of equity (Re) | 14.39% | CAPM: Rf + β × MRP |
| Cost of debt (Rd) | 2.96% | NVIDIA annual report |
| Tax rate | 15.1% | Normalised effective rate |
| After-tax cost of debt | ~2.51% | Rd × (1 - t) |
| Equity weight (E/V) | 99.8% | Market cap / (Market cap + Debt) |
| Debt weight (D/V) | 0.2% | Debt / (Market cap + Debt) |
| **WACC (computed)** | **14.37%** | Weighted average |

NVIDIA's beta of 2.20 reflects the stock's historical sensitivity to AI sentiment, interest rate movements, and semiconductor cycle positioning — all of which amplify both upside and downside relative to the broader market. The near-zero debt weight means the WACC is almost entirely the cost of equity, making it sensitive to beta and the risk-free rate but not to capital structure decisions.

The three scenarios use different WACCs to reflect uncertainty about the appropriate risk premium for a company growing this fast:

| Scenario | WACC | TGR |
|---|---|---|
| Conservative | 16.0% | 2.0% |
| Base | 14.37% (computed) | 2.5% |
| Optimistic | 12.0% | 3.0% |

---

## Discounted Cash Flow Valuation

**FCFF = EBIAT + D&A - Capex - Change in NWC**

Mid-year convention applied. Discount period begins at 0.15 years (reflecting the May 2026 valuation date relative to the January 2026 fiscal year-end).

| | FY2027E | FY2028E | FY2029E | FY2030E | FY2031E |
|---|---|---|---|---|---|
| EBIAT ($M) | 205,118 | 293,861 | 444,647 | 655,759 | 945,304 |
| D&A ($M) | 11,950 | 16,708 | 24,687 | 35,571 | 50,125 |
| Capex ($M) | 13,627 | 19,052 | 28,151 | 40,562 | 57,159 |
| Change in NWC ($M) | 44,915 | 62,797 | 92,786 | 133,695 | 188,398 |
| **FCFF ($M)** | **158,526** | **228,719** | **348,398** | **517,072** | **749,872** |
| Discounted FCFF ($M) | 155,830 | 208,829 | 284,018 | 376,361 | 487,329 |

Working capital is the largest FCF drag in the forecast, absorbing approximately 11.5% of revenue annually. This reflects NVIDIA's growing receivables and inventory requirements as it ships larger volumes of high-value hardware.

**Valuation Bridge — Optimistic Case (WACC = 12.0%, TGR = 3.0%)**

| Item | Value ($M) |
|---|---|
| Sum of discounted FCFFs | 1,512,366 |
| Terminal Value (undiscounted) | 8,581,868 |
| Discounted Terminal Value | 5,577,205 |
| **Enterprise Value** | **7,089,571** |
| Plus: Cash | 50,335 |
| Less: Debt | (8,468) |
| **Equity Value** | **7,131,438** |
| Diluted Shares | 24,391M |
| **Implied Share Price** | **$292.38** |

Terminal value represents approximately 79% of enterprise value. NVIDIA's near-term FCFs are large enough to contribute meaningfully to total value. The implied upside to the current share price of $220.61 is approximately 32.5%.

---

## Key Risks

**Custom silicon displacement.** Google, Amazon, Microsoft, and Meta are all investing heavily in proprietary AI accelerators. If these reach competitive performance levels within the explicit forecast window, NVIDIA's pricing power and market share in data center compress simultaneously a scenario the conservative case is designed to capture.

**Revenue deceleration faster than modelled.** The optimistic case still assumes NVIDIA grows from $216B to $1.6T over five years. If the hyperscaler capex cycle pauses — due to slower-than-expected AI adoption, regulatory intervention, or power and water infrastructure constraints on data center build-outs revenue growth decelerates faster than any scenario in this model projects.

**CUDA moat durability.** The switching cost thesis rests on CUDA's developer lock-in. If AMD's ROCm ecosystem, Google's JAX, or open-source alternatives reach parity in ease of use and performance, the transition cost falls and the software moat narrows.

**Geopolitical and export controls.** The US government has progressively tightened restrictions on high-end GPU exports to China. China represented a significant portion of NVIDIA's data center revenue before export controls. Further restrictions, or escalation into a broader technology trade conflict, could remove a material addressable market.

**Concentration risk.** A significant portion of NVIDIA's data center revenue is concentrated among four or five hyperscalers. If any of them meaningfully redirects AI infrastructure spend toward internal silicon, the revenue impact is immediate and large.

**Valuation entry point.** At $220.61, the stock is priced for a scenario between the base and optimistic cases in this model. There is limited margin of safety, a deceleration toward the conservative scenario implies substantial downside.

---

## Disclaimer

This model was developed for educational and investment research purposes. It does not constitute investment advice or a recommendation to buy or sell any security. All assumptions are the author's own and do not represent the views of any employer or affiliated institution.
