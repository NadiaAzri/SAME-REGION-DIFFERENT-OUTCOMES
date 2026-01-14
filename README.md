# Same Region, Different Outcomes: Understanding Wealth in the Middle East
**Created by**: Nadia Azri and Ximena Lucio Calzada

## Overview

This interactive Tableau storyboard explores the striking economic disparities across Middle Eastern nations, revealing how countries in the same geographic region experience vastly different levels of prosperity. Through data visualization and narrative storytelling, the project examines why oil wealth alone doesn't guarantee economic success and how governance, political stability, and corruption shape national outcomes.

## Story Narrative

### Chapter 1: Here's the Massive Inequality
**Qatar and the Gulf Surge Ahead in Income**

The story begins with a stark revelation: Qatar's GDP per capita is approximately **140 times greater** than Syria's, despite both countries being located in the same region. The Gulf states (Qatar, UAE, Kuwait) have experienced explosive economic growth, while other Middle Eastern nations lag significantly behind.

**Key Visualizations:**
- Bar chart comparing GDP per capita across Middle Eastern countries (2020, 2021, 2022)
- Time series showing the dramatic divergence in economic growth since 2000
- Qatar leads with GDP per capita exceeding $100,000, while Syria remains below $1,000

### Chapter 2: It's Not Just About Having Oil
**Where Do the Middle East's Richest Nations Really Get Their Wealth?**

This chapter challenges the assumption that oil wealth automatically translates to prosperity. While resource abundance matters, the data reveals that oil-rich nations like Iraq and Libya have struggled economically despite their natural resources.

**Key Insights:**
- Countries with high natural resource rents don't always achieve high GDP per capita
- Qatar and UAE have successfully leveraged oil wealth, while Iraq and Libya have not
- Resource management and economic diversification are critical factors
- Kuwait shows moderate-high GDP despite lower resource rents than Iraq

### Chapter 3: It's About Governance and Stability
**When Natural Wealth Isn't Enough**

The analysis reveals that corruption and political instability are the critical differentiators. Countries with strong corruption control and political stability achieve higher prosperity regardless of resource endowments.

**Key Visualizations:**
- Diverging bar chart showing corruption control scores across the region
- **Strong Control**: UAE, Qatar, KSA, Oman, Bahrain, Jordan, Kuwait
- **Weak Control**: Egypt, Iran, Lebanon, Iraq, Libya, Syria
- Scatter plot demonstrating positive correlation between political stability and GDP per capita

**Major Finding:** Countries with better governance structures convert resources into prosperity, while those with corruption and instability fail to benefit their populations.

### Chapter 4: Here's How It Affects Real People
**High Prices, Unequal Access**

The final chapter examines how economic disparities manifest in citizens' daily lives through inflation rates and internet access—indicators of both economic pressure and development.

**Key Data Points:**
- **Inflation Crisis**: Lebanon experiences over 50% average annual inflation, followed by Iran (~30%)
- **Digital Divide**: Internet penetration ranges from 30% (Iraq) to nearly 100% (Qatar, UAE, Bahrain)
- **Correlation**: Higher GDP per capita strongly correlates with greater internet access
- Gulf states maintain low inflation and universal internet access, while conflict zones face high inflation and limited connectivity

## Key Findings

### Economic Disparities
1. **140:1 GDP Gap**: Qatar's GDP per capita is 140 times higher than Syria's
2. **Gulf Dominance**: Qatar, UAE, and Kuwait lead the region in per capita wealth
3. **Bottom Tier**: Syria, Lebanon have the lowest GDP per capita

### The Oil Paradox
1. **Resource Wealth ≠ Prosperity**: Iraq and Libya have substantial oil reserves but low GDP per capita
2. **Management Matters**: How resources are governed determines outcomes more than their existence
3. **Diversification Success**: UAE and Qatar have diversified beyond oil dependence

### Governance as the Game Changer
1. **Corruption Control**: Strong anti-corruption measures correlate with higher prosperity
2. **Political Stability**: Stable governments achieve better economic outcomes
3. **Institutional Quality**: Effective governance institutions convert resources into citizen welfare

### Real-World Impacts
1. **Inflation Inequality**: Poorer nations face significantly higher inflation rates
2. **Technology Gap**: Internet access varies from 30% to nearly 100% across the region
3. **Quality of Life**: Economic disparities translate directly to citizen wellbeing

## Data Sources

All data sourced from **World Bank Open Data** via two primary datasets:

### 1. Natural Resources Data
**File**: `API_NY_GDP_TOTL_RT_ZS_DS2_en_csv_v2_129611.xlsx`
- **Indicator**: Total natural resources rents (% of GDP)
- **Source**: World Bank Development Indicators
- **Time Period**: 1970-2021
- **Used For**: Analyzing the relationship between resource wealth and economic prosperity

### 2. Development Indicators Data
**File**: `world_bank_development_indicators.xlsx`
- **Source**: World Bank Development Indicators (comprehensive dataset)
- **Indicators Used**:
  - **Economic Indicators**:
    - GDP (current US$) - `GDP_current_US`
    - Inflation (annual %) - `inflation_annual%`
    - Population
  
  - **Governance Indicators**:
    - Control of corruption estimate - `control_of_corruption_estimate`
    - Political stability estimate - `political_stability_estimate`
  
  - **Development Indicators**:
    - Individuals using internet (%) - `individuals_using_internet%`

### Data Processing
- GDP per capita calculated from GDP (current US$) divided by population
- Multi-year averages used for stability (2020-2022 where available)
- Missing data handled through interpolation or excluded from specific visualizations
- All data standardized for cross-country comparisons

### Data Attribution
All datasets are publicly available through the World Bank Open Data portal (data.worldbank.org) and are used in accordance with the World Bank's data usage terms, which permit reuse with appropriate attribution.

## Visualizations

### Chart Types Used
1. **Bar Charts**: GDP comparisons, inflation rates
2. **Line Charts**: Historical GDP trends over time
3. **Diverging Bar Charts**: Corruption control scores (strong vs. weak)
4. **Scatter Plots**: Relationships between stability, governance, and prosperity
5. **Color Coding**: Brown/red palette indicating intensity levels

### Interactive Features
- Year filters for temporal analysis
- Cross-filtering between visualizations
- Story navigation tabs
- Hover tooltips for detailed country information

## Tableau Public Link

[View Interactive Storyboard on Tableau Public](https://public.tableau.com/shared/H6FNNZW63?:display_count=n&:origin=viz_share_link)

## Technical Details

- **Platform**: Tableau Public
- **Format**: Story/Narrative Dashboard
- **Chapters**: 4 interconnected story points
- **Time Period**: Primarily 2000-2022
- **Countries Analyzed**: 20+ Middle Eastern nations
- **Design Theme**: Consistent brown palette matching regional context

## Use Cases

This storyboard serves multiple audiences:

### Policy Makers & Government Officials
- Understanding the relationship between governance and economic outcomes
- Identifying policy areas that drive prosperity
- Learning from regional success stories

### Researchers & Academics
- Studying the resource curse phenomenon
- Analyzing corruption's economic impact
- Examining development economics in practice

### Journalists & Media
- Explaining Middle East economic disparities to general audiences
- Supporting investigative reporting on governance issues
- Creating informed commentary on regional affairs

### Students & Educators
- Teaching comparative economics
- Understanding real-world governance impacts
- Case studies in development economics

### Business & Investors
- Assessing regional investment opportunities
- Understanding political risk factors
- Evaluating market potential across countries

## Key Takeaways

1. **Geography Isn't Destiny**: Being in the same region doesn't determine economic fate
2. **Resources Need Good Governance**: Natural wealth requires effective institutions to benefit citizens
3. **Stability Enables Prosperity**: Political stability is a prerequisite for sustained economic growth
4. **Corruption Destroys Value**: Poor governance prevents resources from improving lives
5. **Quality of Life Varies Dramatically**: Economic disparities directly affect citizens' daily experiences

## Repository Contents

- `middle_east_wealth_storyboard.twbx` - Tableau workbook file
- Source data files
  - `API_NY_GDP_TOTL_RT_ZS_DS2_en_csv_v2_129611.xlsx` - Natural resources rents data
  - `world_bank_development_indicators.xlsx` - Comprehensive development indicators
- Story screenshots and visualizations + PDF file of the dashboard
- `README.md` - This file

## Story Structure

```
Story Flow:
├── Chapter 1: The Massive Inequality
│   └── GDP disparities visualization
├── Chapter 2: It's Not Just About Oil
│   └── Resource wealth vs. GDP analysis
├── Chapter 3: Governance and Stability
│   └── Corruption and stability correlations
└── Chapter 4: Real-World Impacts
    └── Inflation and internet access data
```

## Insights for Action

### For High-Performing Countries
- Continue strengthening anti-corruption measures
- Maintain political stability
- Invest in digital infrastructure
- Diversify economies beyond natural resources

### For Developing Countries
- Prioritize governance reforms
- Strengthen anti-corruption institutions
- Focus on political stability
- Invest in citizen services and infrastructure

## Methodology

1. **Data Collection**: Gathered economic, governance, and social indicators from multiple sources
2. **Normalization**: Standardized metrics across countries and time periods
3. **Analysis**: Examined correlations between governance quality and economic outcomes
4. **Visualization**: Created narrative flow to guide viewers through insights
5. **Validation**: Cross-referenced findings with established economic research

## Limitations
extensive missing data:
  - **Yemen**: Insufficient economic and governance data across the study period
  - **Turkey**: Incomplete data for key indicators
  - Other countries with significant data gaps were also excluded to maintain analysis integrity
- Data availability varies by country and year
- Conflict zones may have incomplete or estimated data
- Correlation doesn't imply causation (though literature supports causal relationships)
- GDP per capita doesn't capture income distribution within countries
- Some countries (e.g., Syria) affected by ongoing conflicts skewing recent data

## Future Enhancements

- Include income inequality (Gini coefficient) data
- Add education and health outcome metrics
- Expand time series to show longer-term trends
- Include case studies of specific reform successes
- Add predictive modeling for countries implementing reforms

## Contributing

Contributions are welcome! Please consider:
- Additional data sources to strengthen analysis
- Corrections to data or interpretations
- Suggestions for additional visualizations
- Updates with more recent data


## License

This project is created for educational and analytical purposes. Please attribute appropriately if using for research or publication.

## Acknowledgments

- **World Bank Open Data** - Primary data source for all economic, governance, and development indicators
- World Bank Development Indicators database
- Tableau Public community for visualization inspiration
- Economic development researchers whose work informed this analysis

**Note**: This analysis aims to provide objective insights into regional economic disparities and is not intended to make political statements about any nation or government. All data is from publicly available sources and represents the best available information at the time of creation.
