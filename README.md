📊 Smart CRE Advisor: Post-COVID Leasing Intelligence
===

🔍 Project Summary:
=
    
  This project explores commercial real estate leasing trends      post-COVID using actual leasing, rent, and occupancy data from major U.S. markets between 2020–2024. The goal is to help clients make smarter leasing decisions by building visual insights, exploring data patterns, and developing a rule-based recommendation engine for office space selection.


🧠 Core Problem Addressed
==
Commercial tenants today face three major post-COVID challenges:

Post-COVID Return: 65% of the workforce has returned to offices, increasing demand—but rents have spiked.

Downtown vs Suburban: Choosing CBD vs Suburb has become a gamble, with shifting market behavior.

Dry Leasing Seasons: 73% of leasing happens only in Q4 each year, causing uneven competition.


💡 What I Built:
============

-📌 Visual Analytics (Python)
Rent Comparison – Sublet vs Direct Rent in Class A markets

-Sublet Rent Discount Bar Charts – Identifies top cities where subleasing is significantly cheaper

-Sublet Sweet Spot Bubble Plot – Matches rent discounts with availability to identify the best sublet markets

-Leasing Volume vs Occupancy Rate Line+Bar Chart – Combines quarterly leasing activity with occupancy recovery trends

-Heatmap: Downtown vs Suburb Leasing Share – Shows market-by-market preference shift

Choropleth: State-level lease volume visual


🧮 Rule-Based Recommendation System:
=========================================

-We developed a customizable client matching system based on:

---Budget ($/sf)

---Desired Office Class (A, B, C)

---Location Type (CBD or Suburban)

---Space Size Needed (in sqft)

---Industry Type (Tech, Legal, Finance)

Each profile is matched to leasing options using our post-COVID filtered dataset and displayed using PrettyTable outputs.


Example Profiles:

✅ Tech Startup A: 20k sqft | Suburban | Class A | Budget $40/sf

✅ Law Firm B: 15k sqft | CBD | Class A | Budget $55/sf

✅ FinTech Company C: Flexible Size | Smart Matching Logic


🤖 What’s Coming Next
================

We are preparing to extend this rule-based engine with a machine learning model, using features like:

Rent Trends

Vacancy Rates

Submarket Popularity

Lease Size vs Budget Matching



📁 Files
========

final_lease.csv – Cleaned dataset containing leasing records

unemployment.csv, occupancy.csv – Supporting trend data

Tableau Dashboards – Used for visual storytelling and city-level analysis

recommendation_model.py – Rule-based matching logic



📈 Impact
=====

By integrating rent data, space availability, and location preferences, this project:

Helps clients lease smarter, not just cheaper

Provides sublet vs direct rent guidance

Acts as a Commercial Real Estate “Zillow” with custom business intelligence
