# Methodology for Kenya GHG Emissions Calculator

## Overview
This calculator follows the **GHG Protocol Corporate Standard** for calculating greenhouse gas emissions from business activities in Kenya.

## Emission Factors Sources

### Fuel Combustion (Scope 1)
**Source:** EPA Emission Factors for Greenhouse Gas Inventories (2014)
- **Diesel:** 2.698 kg CO₂/liter (converted from 10.21 kg CO₂/gallon)
- **Petrol:** 2.319 kg CO₂/liter (converted from 8.78 kg CO₂/gallon)
- **LPG:** 2.94 kg CO₂/kg (converted from 5.68 kg CO₂/gallon)

### Electricity (Scope 2)
**Source:** IGES Database via World Bank Kenya Grid Analysis
- **Kenya Grid:** 0.6545 kg CO₂/kWh
- **Context:** Kenya's grid is ~90% renewable energy (geothermal, hydro, wind, solar)

### Other Emissions (Scope 3)
**Source:** IPCC Guidelines for National Greenhouse Gas Inventories (2006)
- **Travel:** 0.2 kg CO₂/km (average vehicle)
- **Waste:** 0.7 kg CO₂/kg (landfill methane emissions)

## Calculation Method
**Formula:** Activity Data × Emission Factor = GHG Emissions

**Example:**
- 1,000 liters diesel × 2.698 kg CO₂/liter = 2,698 kg CO₂
- 5,000 kWh electricity × 0.6545 kg CO₂/kWh = 3,273 kg CO₂

## Scope Classification
- **Scope 1:** Direct emissions from company-owned sources
- **Scope 2:** Indirect emissions from purchased electricity
- **Scope 3:** Other indirect emissions (travel, waste, supply chain)

## Uncertainty and Limitations
- Emission factors are global/regional averages
- Local variations may occur
- Scope 3 factors are simplified estimates
- Updated annually when new data is available

## References
1. EPA (2014). Emission Factors for Greenhouse Gas Inventories
2. IGES Database - Grid Emission Factors
3. IPCC (2006). Guidelines for National Greenhouse Gas Inventories
4. GHG Protocol Corporate Accounting and Reporting Standard

---
*Last updated: June 2025*
