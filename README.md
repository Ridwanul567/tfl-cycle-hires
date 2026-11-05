# TFL Cycle Hires


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