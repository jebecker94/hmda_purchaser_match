# hmda_purchaser_match
Resources for matching originated and purchased mortgages within the public HMDA files.

# Use Cases
In internal HMDA-to-HMDA match between mortgage originations and purchases can be valuable for a few reasons:
1. Assisting with matches between HMDA originations and other data sets (e.g., public MBS loan-level files)
   - Matching between HMDA and other datasets is often complicated by the fact that transactions occur between origination and securitization, meaning that the loan originator is not the same entity providing the loan to the securitizing agency (FNMA/FHLMC/GNMA). An internal match between originations and purchases can provide the identity of the entity who provides the loan to the agencies, and tighten up the match between HMDA and securities data.
2. Understanding relationships between financial institutions in the mortgage business
   - Little is known about whole loan trades between institutions. A match between HMDA originations and purchases can fill out this picture by providing a glimpse into the relationships and frequency of trades between parties.
