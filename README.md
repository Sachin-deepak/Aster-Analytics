# Aster Call Analysis Dashboard

Aster is a lightweight dashboard designed for AI call analysis. it provides a comprehensive view of call metrics, audio quality, and conversation insights across multiple batches of recordings.

## Features

- **Batch-wise Performance**: Track pickup rates, successful reschedules, and asset availability across different call batches.
- **Audio Quality Metrics**: analyze silence percentage, speech clarity, background noise, and volume instability.
- **Interactive Call Explorer**: Search and filter through calls based on batch, quality, drop-off stage, and more.
- **Detailed Insights**: Automated rule-based insights for both audio and transcript analysis.
- **Methodology Documentation**: Transparency on how metrics are calculated and interpreted.

## Project Structure

- `index.html`: The main dashboard entry point.
- `Batch 1-5/`: Directories containing the call assets (audio and transcripts).
- `preview (3).html`: A preview version of the dashboard.

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla).
- **Visualization**: [Chart.js](https://www.chartjs.org/) for interactive charts.
- **Icons & Fonts**: Google Fonts (Inter).

## How to Use

1. Clone the repository.
2. Open `index.html` in any modern web browser.
3. Use the sidebar filters to explore the call data.

## Methodology

The analysis follows a two-lane approach:
1. **Audio Lane**: Direct measurement of the signal envelope and frequency texture.
2. **Transcript Lane**: Structural interpretation of the conversation flow and turn counts.

For more details, see the **Methodology** tab within the dashboard.

---

Built with focus on performance and explainability.
