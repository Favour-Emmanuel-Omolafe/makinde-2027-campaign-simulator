Nigeria 2027 Electoral Strategy & Decision Simulator

Engineered by Favour Emmanuel Omolafe

An interactive 36-state + FCT structural electoral sensitivity simulator and quantitative campaign strategy model evaluating Nigeria's 2027 presidential dynamics, Section 134 constitutional spread requirements, North-South power-rotation (zoning) effects, and coalition vs. solo-run trade-offs.

Executive Overview

Winning a Nigerian presidential election requires satisfying Section 134(2) of the 1999 Constitution: securing a national plurality of votes and at least 25% of valid votes in two-thirds of all states and the FCT (24 out of 37 jurisdictions).

Using Governor Seyi Makinde's 2027 Allied People's Movement (APM) presidential bid as a quantitative case study, this repository models:

Intra-Zone Vote Splitting & Power Rotation: How running from the same geopolitical zone (South-West) as an incumbent president affects regional vote concentration and cross-regional resistance.

The 774-LGA Preparation Runway: How campaign timeline length (53-day sprint vs. 9-month grassroots surge vs. 48-month party build) governs polling-unit agent coverage and rural ward depth.

The 2023 Labour Party Surge Stress Test: Why scaling vote volume to match Peter Obi's historic 2023 surge (~6.1 million votes) still falls short of the 24-state constitutional floor under a four-way opposition split.

One-Term Transitional Coalition & Sub-National Spillover: How pooling anchor blocs (Oyo and Bauchi) into a unified coalition pact clears the 24-state floor while protecting down-ballot governorship transitions.

Repository Structure

nigeria-2027-electoral-strategy-simulator/
├── README.md                                  # Project overview, methodology, and setup guide
├── Seyi Makinde 2027 Campaign Strategy.pdf    # Formal strategic brief and political trajectory analysis
├── makinde_strategic_simulator_v4.html        # Self-contained interactive web dashboard (rename to index.html for GitHub Pages)
└── makinde_2027_electoral_simulator_v3.py     # Standalone Python Monte Carlo & sensitivity simulation engine


Key Features & Built-In Scenarios

Both the interactive HTML dashboard and the standalone Python script include five scenario presets:

Jan 2027 Solo APM Run (53 Days Left | Single-Shot): Models a solo sprint with limited national polling-unit depth against an incumbent South-West presidency.

Stress Test — Replicating Obi's 6.1M Surge: Grants the premise of a massive third-party vote explosion (~5.5M–6.1M votes) to test why regional concentration and a 4-way opposition split still cap geographic spread below 24 states.

Jan 2027 One-Term Transitional Coalition Pact: Evaluates pooling Oyo and Bauchi swing blocs with opposition allies under a single transitional term, easing North-South zoning friction and clearing Section 134.

2023 Benchmark (9-Month Surge — Obi LP Model): Calibrates the model against historical 2023 Labour Party dynamics (strong urban/youth energy without 774-LGA rural saturation).

2027–2031 Institutional Build (Post-Makinde Successor Strategy): Models a 48-month bottom-up sub-national strategy (consolidating governorships, National Assembly seats, and local councils before a future national run).

Quick Start

1. Run the Interactive Web Dashboard

Open makinde_strategic_simulator_v4.html directly in any modern web browser (no server or external dependencies required).

To host on GitHub Pages: Copy or rename makinde_strategic_simulator_v4.html to index.html in the root directory, then enable Settings → Pages from the main branch.

2. Run the Standalone Python Simulation

Ensure numpy and pandas are installed:

pip install numpy pandas
python makinde_2027_electoral_simulator_v3.py


Methodological Scope & Caveats

Structural Sensitivity Model, Not a Live Poll: Because consistent daily state-by-state polling across all 36 states + FCT is unavailable, this engine uses calibrated structural weights anchored on 2023 INEC baselines and 2026 sub-national governance alignment.

Purpose: Designed as a quantitative decision-support tool for testing strategic hypotheses, coalition math, and constitutional spread constraints under uncertainty.

Author

Favour Emmanuel Omolafe

Quantitative Decision Systems & Applied Data Analytics
