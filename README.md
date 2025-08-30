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
        │   └── saudi_arabia_exports_2019.csv
        ├── domestic/
        │   └── saudi_arabia_domestic_2019.csv
        └── analysis_summary.md
```

## Data Sources

- **Primary Source**: Exiobase v3 Multi-Regional Input-Output (MRIO) database
- **Trade Data**: US Census Bureau trade statistics
- **Environmental Factors**: Environmental extension matrices from Exiobase

## Comprehensive Trade Statistics (2019)

### Import Flows (Saudi Arabia → US): $13.5B
1. **Oil & Gas Extraction (211000)**: $11.49B - 85% of total imports
2. **Petroleum Refineries (324110)**: $887.9M 
3. **Fertilizers (325310)**: $249.8M
4. **Aluminum Production (33131B)**: $254.1M
5. **Iron & Steel Mills (331110)**: $114.1M

### Export Flows (US → Saudi Arabia): $9.27B
1. **Industrial Machinery (333111)**: $2.14B - Advanced manufacturing equipment
2. **Petroleum Equipment (324110)**: $1.85B - Refinery technology
3. **Electronic Equipment (333120)**: $1.42B - High-tech exports
4. **Power Generation (335110)**: $980M - Energy infrastructure
5. **Agricultural Products (311111)**: $750M - Food exports

### Domestic Trade Flows (Within Saudi Arabia): $152B
1. **Oil to Refining (211000→324110)**: $45B - Primary processing
2. **Refining to Petrochemicals (324110→325110)**: $28B - Value-added processing
3. **Petrochemicals to Fertilizers (325110→325190)**: $18.5B - Chemical manufacturing
4. **Steel Production (331110→332119)**: $12B - Metal manufacturing
5. **Power Generation (211000→333111)**: $8.5B - Energy integration

### Trade Balance Summary:
- **Total Saudi Exports**: $13.5B
- **Total US Exports**: $9.27B
- **Net Trade Surplus**: $4.23B (favoring Saudi Arabia)
- **Domestic Economy Scale**: $152B (11x larger than exports)

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