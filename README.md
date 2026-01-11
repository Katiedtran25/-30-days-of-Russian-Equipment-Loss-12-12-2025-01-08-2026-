# -30-days-of-Russian-Equipment-Loss-from 12-02-2025 to 01-08-2026-
Comparative Analysis: Russian Equipment Losses 12/02/2025–12/30/2025 vs 12/12/2025–01/08/2026
Step-by-step plan to go From API → Cleaned Dataset → Geo + Temporal Insights → Tableau Story, plus code snippets, data model suggestions, visualization ideas, 
and important ethical/methodology notes. I’ll target 30 days of WarSpotting in 2 periods of time from Early December 2025 to Early 2026 (WarSpotting documents 
visually-verified Russian equipment losses), 
show exactly how to pull the data, how to clean/deduplicate it, and what to build in Tableau Cloud.

**Part 1: Web scraping Using WarSpotting Data in 30 Days of Russian Equipment Losses from 2 periods from early December 2025 to early 2026**
Period 1: 12/02/2025–12/30/2025
Period 2: 12/12/2025–01/08/2026
The data is extracted from Losses ∙ Russia ∙ WarSpotting — documented material losses in Russo-Ukrainian war , use Python to web crape the data, and use cleaning
tech to eliminate the null data, the outliers, then load data to Tableau Cloud for analytic.
Data Collection and Cleaning technique

**Part 2: Data Visualization Using Tableau Cloud**
Comparative Analysis: Russian Equipment Losses from early December 2025 to late Early 2026
   


**II. Report:**
Comparative Analysis: Russian Equipment Losses (2 periods from early December 2025 vs early 2026)
1.	Early Period Map
30 days: 12/02/2025–12/30/2025
2.	Mid-to-Late Period Map + Type Table
30 days: 12/12/2025–01/08/2026
3.	Detailed Dashboard (Map, Status, Time Series, Type × Status)
30 days: 12/12/2025–01/08/2026
________________________________________
1. Geographic Evolution
Image 1 – Early Period (Dec 2–Dec 30)
•	Losses are widely dispersed:
o	Eastern Ukraine
o	Southern coastal areas
o	Isolated northern points
•	Pattern suggests:
o	Active maneuvering
o	Losses during movement, transit, or probing operations
Image 2 – Mid-to-Late Period (Dec 12–Jan 8)
•	Losses become highly clustered
•	Strong concentration along:
o	Donetsk Oblast
o	Bakhmut–Pokrovsk axis
•	Fewer isolated incidents elsewhere
Image 3 – Detailed Map (Dec 12–Jan 8)
•	Confirms tight clustering
•	Repeated losses in the same corridors
•	Indicates:
o	Fixed frontline engagements
o	Recurrent strikes on known routes and staging areas
Geographic Trend:
📍 Dispersed → Concentrated → Recurrent hotspot losses
________________________________________
2. Temporal Dynamics 
•	Daily loss counts show:
o	Sharp spikes in mid-to-late December
o	Peak day exceeding 25 losses
o	Decline entering early January
•	Interpretation:
o	Intensified combat phase before year-end
o	Possible operational pause, weather effects, or regrouping afterward
________________________________________
3. Equipment Type Comparison
Early Period 
•	Mixed equipment types
•	No dominant category
•	Suggests:
o	Broad operational exposure
o	Losses tied to mobility and repositioning
Later Period 
Dominant categories:
•	Transport vehicles (38 destroyed)
•	Infantry Fighting Vehicles (53 destroyed)
•	Tanks (25 destroyed)
Secondary but notable:
•	Drones
•	Anti-aircraft systems
•	Rocket & missile artillery
Equipment Trend:
⚙️ From mixed losses → logistics & infantry-heavy attrition
________________________________________
4. Status of Losses (Image 3)
•	Destroyed assets overwhelmingly dominate
•	Minor shares of:
o	Captured
o	Abandoned
o	Damaged
•	Indicates:
o	High lethality engagements
o	Limited recovery or battlefield control over damaged equipment
This contrasts with early-period dispersion, where losses were more likely tied to movement and isolated incidents.
________________________________________
5. Operational Interpretation Across All Three
Dimension	Early Period	Later Period
Geography	Dispersed	Clustered
Tempo	Moderate	High
Loss Type	Mixed	Transport, IFV, tanks
Status	Implied mixed	Predominantly destroyed
Posture	Maneuver	Entrenched combat
________________________________________
6. Strategic Implications
•	The transition suggests:
o	Shrinking operational flexibility
o	Increased vulnerability of logistics and troop movement
•	Concentrated destruction of transport vehicles implies:
o	Stress on sustainment
o	Reduced ability to reinforce or rotate units
•	Recurrent losses in the same locations suggest:
o	Predictable routes
o	Effective targeting and intelligence cycles
________________________________________
7. Conclusion
Across the three images, Russian equipment losses evolve from broad, maneuver-related attrition to intense, localized, and highly destructive frontline losses,
centered in eastern Ukraine. The data indicates escalating pressure on logistics and armored units, or pressure on the peace deal with sustained high-intensity
 engagements dominating the later period.

