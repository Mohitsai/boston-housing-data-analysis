# Remodeling and Unit Loss in Boston

## Project Overview
This project was conducted for the **City of Boston Government** to analyze **remodeling trends and unit loss** across Boston’s neighborhoods. The study examined changes in **housing availability, renovation trends, and multi-unit to single-family conversions**, using historical **property assessment and building permit data**.

Key analyses included:
- **Communities gaining vs. losing housing units**
- **Impact of renovations on housing availability**
- **Factors influencing unit loss in areas like Hyde Park and the South End**
- **The role of multi-unit to single-family conversions in housing shortages**
- **Effects of income-restricted housing policies**

## Key Findings

### **1️⃣ Housing Growth and Decline Trends**
- **South Boston, Central Boston, and Dorchester** had the highest increase in housing units.
- **Mattapan experienced significant unit loss**, though not primarily due to renovations.
- **Roxbury, Dorchester, South Boston, and East Boston** showed increased safety-focused renovations.
- **R4 (multi-family) unit numbers declined**, while **R1 (single-family) units increased**, indicating a shift towards single-family housing.

### **2️⃣ Renovations and Housing Availability**
- On average, **9,173 renovation-related permits were issued per year**.
- The neighborhoods with the most renovation-related permits:
  - **Central Boston**
  - **Dorchester**
  - **Back Bay/Beacon Hill**
- **Most significant unit losses occurred in:**
  - **South End**
  - **Back Bay**
  - **Charlestown**
- **Two-unit to single-family conversions were the most common residential transformation.**

### **3️⃣ Relationship Between Renovations and Housing Availability**
- **Citywide correlation between renovations and unit growth: 0.086 (very weak)**
- Some areas showed stronger correlations (~0.3):
  - **02109** (North End)
  - **02119** (Roxbury)
  - **02130** (Jamaica Plain)
  - **02136** (Hyde Park)
  - **02124** (Dorchester)
- **02115 (Fenway/Kenmore)** showed the strongest correlation: **0.50**, suggesting that in this area, renovations were linked to increases in available housing units.

### **4️⃣ Factors Influencing Housing Changes in Hyde Park & South End**
- **Hyde Park (02136)** saw significant increases in **bedrooms and bathrooms per unit**.
- **Factors driving increase in unit size:**
  - Changing **family size and income levels**.
  - Preference for larger homes.
- **Factors driving smaller units:**
  - Urbanization and affordability concerns.
- **Interior renovations were the most common type of renovation permit.**

### **5️⃣ Multi-Unit to Single-Family Conversions**
- **Highest conversion rates observed in:**
  - **02115 (Fenway, Kenmore, Back Bay)** – a highly desirable area for affluent buyers.
  - **02136 (Hyde Park)** and **02124 (Dorchester)** also showed high conversion rates.
- **Average annual loss of 410.68 units** due to housing conversions.
- **Factors contributing to conversions:**
  - **Economic shifts:** Higher-income buyers drive demand for single-family homes.
  - **Urban development policies:** Zoning laws favor single-family dwellings.
  - **Market demand:** Preference for private, spacious homes.
  - **Gentrification:** Rising property values displace lower-income residents.

### **6️⃣ Income-Restricted Housing**
- **Income-restricted housing ensures affordability for lower-income families.**
- Most neighborhoods saw **an increase** in income-restricted housing, but **six neighborhoods experienced a decline**.
- Understanding and implementing income-restricted policies is crucial for **ensuring socio-economic equality in housing.**

## Data Sources
- **Property Assessment Data (2004-2024)**
- **Building Permits Data**
- **Zoning and Housing Policy Reports**

## Data Processing & Analysis
- **Neighborhood ZIP Code Mapping**: Grouped Boston's ZIP codes into neighborhoods.
- **Permit and Property Data Cleaning**:
  - Standardized ZIP codes.
  - Mapped **land use (LU) types**.
  - Filtered for relevant renovation-related permits.
- **Weighted Unit Process for Accurate Analysis**:
  - Assigned **LU weights** to property types to ensure **accurate unit counts**:
    - Single-family (R1) = 1
    - Two-family (R2) = 2
    - Three-family (R3) = 3
    - Multi-family (R4) = 4
    - Apartments (A) = 7
- **Correlation Analysis**:
  - Measured relationships between **permit approvals and housing availability**.
- **Permit Trends Visualization**:
  - **Line graphs, bar charts, and heatmaps** analyzed permit distributions over time.
  
## Key Visualizations
- **Unit Growth & Loss by Neighborhood (2004-2024)**
- **Top Renovation Permit Neighborhoods**
- **Housing Unit Losses Due to Conversions**
- **Interior Renovation Trends Across Boston**
- **Correlation Between Permits and Unit Availability**
- **Impact of Income-Restricted Housing Policies**

## Policy & Planning Recommendations
- **Strengthen zoning protections** for multi-unit housing in high-conversion areas.
- **Expand income-restricted housing policies** to stabilize housing availability.
- **Encourage targeted renovation incentives** in communities with strong permit-to-unit growth correlations (e.g., **02115, 02136, 02124**).
- **Monitor trends in housing conversion** to assess gentrification risks.


## 📞 Contact
For more details, please reach out:
- **[LinkedIn](https://www.linkedin.com/in/mohitsaigutha/)**
- **[Email](mailto:mohit.sai6@gmail.com)**

---

**© 2025 Mohit Sai Gutha** | Project for **City of Boston Government**

