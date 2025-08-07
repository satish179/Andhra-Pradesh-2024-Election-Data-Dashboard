# Andhra Pradesh General Elections 2024 – Dashboard & Data Analysis

## 1. Overview  
This project contains a detailed dataset and an interactive dashboard presenting the 2024 Andhra Pradesh General (Assembly/Parliamentary) elections.  
It includes candidate-level metrics—votes received, margins, party affiliations, gender, age, assets—and aggregated visualizations (e.g., total voters/NOTA, winning party breakdown, vote comparisons).

## 2. Dataset Description  

**Data file(s):**  
`data.csv` (or `.xlsx`): Contains row-level records for each constituency.

**Columns:**  
- S.No – Serial number  
- Parliamentary constituency – District-level segment  
- YEAR – Election year (2024)  
- Constituency – Assembly seat (with number identifier)  
- polled votes – Total votes cast  
- Winning Candidate  
- winning candidate votes  
- Winning party  
- Margin – Difference between winning and runner-up counts  
- Losing candidate & Losing party & losing candidate votes  
- NOTA – “None of the Above” votes  
- Age of Winning Candidate  
- Assets of Winning Candidate  
- Gender of candidate  

## 3. Dashboard Components  

**Top KPIs (interactive filters):**  
- Total voters polled – e.g., ~39.58 million  
- Total NOTA votes – e.g., ~369,302 (≈0.93%)  
- Average age of winning candidates – e.g., 53.6 years  
- Range & filter controls for age, assets, gender, party, constituency  

**Visualizations:**  
- **Winning party count**  
  - Pie chart showing seats won per party (e.g., TDP ~135 seats, JSP, BJP).  
- **Age comparison**  
  - Bar chart comparing winning vs losing candidate ages per constituency.  
- **Vote comparison**  
  - Stacked bars for winning votes, losing votes, and NOTA per constituency.  
- **Top vote-getters table**  
  - Lists highest winning candidate vote counts (e.g., Chandrababu Naidu ~931k).  
- **Geospatial map**  
  - Interactive map with shading or markers by total polled or winning party per seat.  

All visuals support interactivity via dropdowns and sliders for focused filtering.

## 4. How to Use  

- Filters (in header) allow isolation by party, gender, constituency (Assembly or Parliamentary), age bracket, or candidate assets.  
- Charts and maps adjust dynamically based on filter selections.  
- NOTA and turnout insights provide broader context—help identify voter sentiment and demographic effects.  

## 5. Insights & Potential Analysis  

- The dominant party by seat count (e.g., TDP ~77%) vs minor parties (e.g., JSP, BJP).  
- Winning margins distribution—closely contested seats vs landslides.  
- NOTA impact—both absolute numbers and % share.  
- Rocky seats where incumbents narrowly lost or won.  
- Age and asset trends—older/richer winners vs younger challengers.
