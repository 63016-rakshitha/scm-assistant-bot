# SCM Assistant Bot

## Public Chatbot URL

https://cloud.flowiseai.com/chatbot/e4fdb169-ef2a-4c42-8eb0-f1765146e594

## LLM Used

Gemini 2.5 Flash

## Embedding Model Used

text-embedding-004

## Chunking Configurations Tested

### Configuration 1

* Chunk Size: 1000
* Chunk Overlap: 200

### Configuration 2

* Chunk Size: 1500
* Chunk Overlap: 300

## Questions and Answers

### Q1. Which suppliers qualify for the annual Volume Rebate Program and how many are there?

According to Policy §9, there are 11 Tier-3 suppliers classified as High Risk with an active Level 3 flag: Dravex Components India, Plataforma Metales SA, Maghreb Castworks, Helios Pack Greece, Cerromax Mineria, Orinoco Pack SAPI, Quetzal Textiles, Sibertek Molding, Archipelago PCB Corp, Varna Electronics EAD, and Deltaforge Vietnam. As a result, Level 3 mitigation measures must be activated, including CPO escalation and allocation of at least 40% of procurement volume to an alternate supplier.

### Q2. Which suppliers are on Supplier Watch List (SWL) status and what does it restrict?

According to Policy §4.2, 19 suppliers qualify for the Annual Volume Rebate Program because they satisfy all eligibility requirements, including Tier-1 status, On-Time Delivery (OTD) performance of at least 93%, a defect rate below 0.5%, and a Sustainability Score of 85 or higher. The qualifying suppliers are Borealis Composites, Crestline Chemical Supply, Fenwick Alloy Solutions, Hanguk Circuit Works, Hokkaido Alloy Tech, Krauss-Polymex GmbH, Lakeshore Components, Lumivex Semiconductor NL, Maplewood Polymer Corp, Norbec Alloy Works, Nordloom Finland Oy, Orrentek Precision Mfg, Ostwind Composites AG, PrecisionForge Taiyuan, Solveig Eco Packaging, Straits Packaging Hub, Tasman Circuit Boards, Toreval Electronics, and Valdoro Special Alloys. As these suppliers meet all performance, quality, and sustainability thresholds defined in the policy, they are eligible to participate in the Annual Volume Rebate Program.

### Q3. Which region has the highest total PO value, and does it breach the concentration limit?

The EMEA region has the highest total purchase order (PO) value at $193,987,179.91, representing 48.5% of the total global spend of $399,563,494.10. According to Policy §5.3, the maximum allowable regional concentration limit is 45% of total spend to reduce geographic risk exposure. Since EMEA accounts for 48.5% of total spend, it exceeds the policy threshold by 3.5%, resulting in a policy breach. Consequently, the procurement team must submit a formal Diversification Plan to the Supply Chain Risk Committee within 60 days to reduce regional dependency and bring concentration levels back within the approved limit.


### Q4. Which product category has the highest average defect rate and does it exceed the Tier-2 limit?

According to Policy §3.4, 11 suppliers are on the Supplier Watch List (SWL) due to a Compliance Score below 60: Deltaforge Vietnam, Maghreb Castworks, Helios Pack Greece, Cerromax Mineria, Orinoco Pack SAPI, Varna Electronics EAD, Quetzal Textiles, Plataforma Metales SA, Archipelago PCB Corp, Dravex Components India, and Sibertek Molding. Suppliers on the SWL are restricted from receiving new purchase orders exceeding 20% of their prior quarter volume until their compliance status improves.

### Q5. Which suppliers require immediate Level-3 escalation?

Based on the supplier performance data, Mechanical Components have an average defect rate of 2.12% across 360 purchase orders, which remains below the Tier-2 maximum threshold of 2.50% defined in Policy §3.2. Therefore, no policy breach has occurred, although the category is approaching the allowable limit and may require continued monitoring.

## Improvements

* Add reranking for retrieval.
* Improve metadata filtering.
* Add citation references to source documents.
* Use hybrid search (vector + keyword).
* Improve prompt engineering for policy compliance responses.
