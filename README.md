# TFL Cycle Hires

## Data Files Downloaded

From 1st Feb 2026 to 31st May 2026:

- 437JourneyDataExtract01Feb2026-14Feb2026.csv
- 438JourneyDataExtract15Feb2026-28Feb2026.csv
- 439JourneyDataExtract01Mar2026-15Mar2026.csv
- 440JourneyDataExtract15Mar2026-31Mar2026.csv
- 441JourneyDataExtract01Apr2026-15Apr2026.csv
- 442JourneyDataExtract16Apr2026-30Apr2026.csv
- 443JourneyDataExtract01May2026-16May2026.csv
- 444JourneyDataExtract17May2026-31May2026.csv

## Data Format

- Number: int
- Start date: date - m/d/yyyy HH:MM:SS PM
- Start station number: int? - some numbers start with ' e.g. '001049, 300210
- Start station: str - formatted as ???, ??? e.g. Whitehall Place, Strand
- End date: date - m/d/yyyy HH:MM:SS PM
- End station number: int? - some numbers start with ' e.g. '001049, 300210
- End station: str - formatted as ???, ??? e.g. Whitehall Place, Strand
- Bike number: int
- Bike model: str - all CAPITALISED
- Total duration: str - formatted as ??m ??s e.g. 12m 32s
- Total duration (ms): int

This data format was followed for CSV files from Feb 2026 to May 2026 (across 8 files).