## Insights & Recommendations

### Key Insights:
- **Top 7 variables** — including `lighting_energy`, `zone6_temperature`, `zone6_humidity`, `outdoor_temperature`, `wind_speed`, `visibility_index`, and `dew_point` — significantly influence equipment energy consumption.
- **Non-linear ensemble methods** (like **XGBoost**) capture the impact of these features far better than linear models.
- **Time-based patterns**, captured through hour/day sine and cosine features, contribute meaningfully to prediction accuracy.

### Recommendations:
- **Optimize lighting usage** through smart scheduling and energy-efficient fixtures.
- **Control zone-specific temperatures and humidity**, especially in **zone 6**, using automated HVAC systems.
- **Monitor outdoor conditions** (temperature, wind, visibility) to adjust internal operations.
- **Reduce dew point effects** via better insulation and humidity management.
- **Leverage real-time sensor data** to anticipate energy spikes and respond proactively.
- **Implement predictive maintenance** based on trends in high-impact variables.
- **Use AI models like XGBoost** for continuous energy forecasting and efficiency planning.
- **Ensure data accuracy and quality**, as the dataset contained outliers, null values, and potentially incorrect entries. Addressing these will enhance model reliability.
