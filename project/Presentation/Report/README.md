# Weather Impact Analysis System

A Python case study that analyzes daily weather reports from two farms ( Kaduna and Benue) in order to determine whether rainfall and temperature conditions favor crop growth, and whether the farm manager needs to take action.

## Goal

- Compare recorded rainfall with the minimum rainfall requirement.
- Check whether temperature is within the safe limit.
- Determine whether growing conditions are favorable.
- Recommend management action based on the result.

## Data

| Field | Kaduna | Benue |
|---|---|---|
| Crop | Maize | Rice |
| Temperature | 31°C | 38°C |
| Updated rainfall | 26 mm | 20 mm |
| Minimum rainfall required | 20 mm | 25 mm |
| Maximum safe temperature | 35°C | 35°C |
| Irrigation available | Yes | No |

## Key Findings

- **Kaduna** — rainfall requirement met, temperature within safe limit, irrigation available → **favorable conditions, no action required**.
- **Benue** — rainfall below requirement, temperature above safe limit, no irrigation → **unfavorable conditions, action required**.
- Of the two, Benue is the priority farm for an extension officer to visit.

## Tools

Python · Jupyter Notebook

## How to Run

1. Clone this repository.
2. Open `Project/Weather_Impact_Analysis_System.ipynb` in Jupyter Notebook.
3. Run all cells to see the full analysis and generated report.

## Repository Structure

- **Project/** – Python notebook and project files.
- **Presentation/** – Presentation slides.
- **Report/** – Full project report.

## Author

**Vivian Moyosore Gomes**
