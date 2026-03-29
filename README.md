# Virat Kohli Performance Data Analysis

An interactive **Power BI** dashboard analyzing the cricket career of Virat Kohli. The dashboard provides a deep dive into his batting trends, run-scoring patterns, match-by-match performance, and long-term statistical evolution across formats.

## Features

- Career run-scoring trends across ODI, Test, and T20 formats
- Match-by-match score breakdown with opponent and venue filters
- Strike rate, average, and centuries/half-centuries analysis
- Performance comparisons over different time periods and conditions
- Interactive slicers for format, opponent, year, and ground

## Tech Stack

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard creation & data visualization |
| CSV | Source dataset |

## Project Structure

```
virat-kohli-performance-data-analysis/
├── Virat Kohli Score DashBoard.pbix        # Power BI report file
├── Virat Kohli Score DashBoard.pdf         # Exported dashboard (PDF)
├── Virat Kohli Score DashBoard_pages-to-jpg-0001.jpg  # Dashboard preview
└── Sources/
    └── Source.csv                          # Raw performance dataset
```

## Getting Started

### Prerequisites

- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

### Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/smunir25/general-ai-virat-kohli-performance-data-analysis.git
   ```
2. Open `Virat Kohli Score DashBoard.pbix` in Power BI Desktop
3. Explore using the slicers to filter by format, opponent, year, or ground
4. To update with newer data, replace `Sources/Source.csv` and refresh the data source

## Dashboard Preview

![Dashboard Preview](Virat%20Kohli%20Score%20DashBoard_pages-to-jpg-0001.jpg)

## Key Insights Covered

| Area | Metrics |
|------|---------|
| Runs | Total runs per format, innings, and year |
| Averages | Batting average across conditions |
| Centuries | Century/half-century frequency and distribution |
| Opponents | Performance breakdown by opposition |
| Venues | Ground-wise batting statistics |

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
