# Saudi Arabia Trade Flow Data - 2019

This repository contains comprehensive trade flow data for Saudi Arabia for the year 2019, extracted from the Exiobase database and US Census trade data.

## Data Structure

```
data/
└── 2019/
    └── saudi-arabia/
        ├── imports/
        │   └── saudi_arabia_imports_2019.csv
        ├── exports/
        └── domestic/
```

## Data Sources

- **Primary Source**: Exiobase v3 Multi-Regional Input-Output (MRIO) database
- **Trade Data**: US Census Bureau trade statistics
- **Environmental Factors**: Environmental extension matrices from Exiobase

## Key Saudi Arabia Trade Statistics (2019)

### Top Import Sectors to US:
1. **Oil & Gas Extraction (211000)**: $11.49B - Represents 8.1% of national total
2. **Petroleum Refineries (324110)**: $887.9M 
3. **Fertilizers (325310)**: $249.8M
4. **Nitrogenous Fertilizers (325211)**: $59.4M
5. **Aluminum Production (33131B)**: $254.1M
6. **Iron & Steel Mills (331110)**: $114.1M

### Regional Classification:
- **Country Code**: WM (Western Middle East)
- **Region**: ROW (Rest of World)
- **Trade Partner**: United States

## Data Fields

### Import Data (`saudi_arabia_imports_2019.csv`)

| Field | Description |
|-------|-------------|
| BEA Detail | Bureau of Economic Analysis detailed industry code |
| Year | Data year (2019) |
| Country | Source country (Saudi Arabia) |
| Import Quantity | Trade value in USD |
| Unit | Currency unit (USD) |
| Source | Data source (Census) |
| BEA Summary | BEA summary industry category |
| CountryCode | Country/region code (WM) |
| Region | Geographic region (ROW) |
| cntry_cntrb_to_national_detail | Country contribution to national detail level |
| cntry_cntrb_to_region_detail | Country contribution to regional detail level |
| cntry_cntrb_to_national_summary | Country contribution to national summary level |
| cntry_cntrb_to_region_summary | Country contribution to regional summary level |

## Usage

This data can be used for:

- **Economic Analysis**: Understanding Saudi Arabia's trade patterns with the US
- **Environmental Impact Assessment**: Calculating embodied environmental impacts in trade
- **Industry Analysis**: Identifying key trading sectors and their contributions
- **Policy Research**: Supporting trade policy and economic development decisions

## Data Processing

The data has been extracted and processed from the original Exiobase database using automated Python scripts that:

1. Parse multi-regional input-output matrices
2. Extract country-specific trade flows
3. Calculate environmental impact coefficients
4. Generate structured CSV outputs for analysis

## Contact

Repository maintained by Rakshanda Hedawoo for trade flow analysis and research.

---

*Last Updated: August 29, 2025*