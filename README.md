# m228-final-project

## Notes

- There are 45 total participants.
  - 15 healthy
  - 16 pre-diabetics
  - 14 type II diabetics
- Participants 24, 25, 37, and 40 did not complete the study, so their data is missing.
  - So the numbering goes from 1 to 49 but covers only 45 participants
- In each participant's sheet, there are columns for meal types and macros, but they are empty.
- Data spans ~10 days.
- parse_data.ipynb is the script they used to process the data & build an XGBoost model
  - their repo lives at: https://github.com/PSI-TAMU/CGMacros/tree/main

## Questions
- How do we map back participant number to diabetes status? 
  - a1c level?