# LEARNING_LOG.md

## Week 2 Python Lab: Explore time-series patterns using Phnom Penh precipitation

### Date: [29/09/2026]
### Student: Seng Ranut

### Learning Outcomes Achieved:

*   Time Index and Monthly Coverage: Confirmed the time index (date column) and verified complete monthly coverage from 2015-01-01 to 2025-12-01, with no missing or duplicate dates, and no missing precipitation values.
*   Time Plot: Successfully created a time plot to visualize the chronological precipitation data. Observed a clear annual repeating rise and fall pattern (wet and dry seasons) but no clear long-term increase or decrease. Identified June 2020 as an unusually high precipitation event.
*   Seasonal Plot: Generated a seasonal plot to compare monthly precipitation across years. This view clearly showed the wetter months (May-October, peaking around September/October) and the significant year-to-year variation in peak sizes. The unusual spike in June 2020 was again evident.
*   Seasonal Subseries Plot: Constructed a seasonal subseries plot, which provided a detailed view of each month's precipitation over the years, alongside its mean. This allowed for direct comparison of monthly averages and variation. Confirmed September as having a high average and February a low average, with September showing greater year-to-year variability.
*   Evidence-Based Interpretation: Supported interpretations with numerical evidence and visual features from the plots, such as the highest monthly precipitation value (June 2020: 703.62 units) and the months with highest/lowest mean precipitation (September/February).

### Key Findings and Observations:

*   The precipitation data exhibits a strong seasonal pattern, with a predictable wet and dry season in Phnom Penh.
*   While seasonal patterns are clear, there is considerable inter-annual variability in precipitation levels, especially during peak months.
*   June 2020 stands out as an extreme outlier with exceptionally high precipitation, highlighting the importance of identifying unusual observations in time series data.

### Limitations and Unclear Aspects:

*   The exact measurement unit for precipitation remains 'source units', pending independent confirmation from the full NASA POWER source metadata. This is a critical limitation for quantitative interpretation and comparison with other datasets.
*   Without external validation, extreme values like June 2020's precipitation cannot be definitively classified as measurement errors or genuine extreme weather events.

### Files Exported:

*   phnom_penh_monthly_precipitation_2015_2025_long.csv (reshaped data)
*   01_time_plot.png
*   02_seasonal_plot.png
*   03_seasonal_subseries_plot.png

### Next Steps/Further Questions:

*   Investigate the source metadata to confirm precipitation units.
*   Explore potential causes or corroborating evidence for the unusual June 2020 precipitation.
*   Begin exploring lag relationships and autocorrelation in the next lab session.