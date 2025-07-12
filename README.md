# 911-Calls-Capstone-Project
# Emergency Calls Data Analysis

This repository contains data and analysis related to emergency calls in Montgomery County, Pennsylvania. The dataset includes information about various emergency incidents, including EMS, fire, and traffic events, with details such as location, time, and type of emergency.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [File Structure](#file-structure)
- [Requirements](#requirements)
- [Usage](#usage)
- [Analysis Highlights](#analysis-highlights)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project explores and visualizes patterns in emergency call data. The goal is to identify trends by time, location, and type of emergency to support public safety initiatives and resource allocation.

## Dataset Description

The dataset contains the following columns:

| Column      | Description                                      |
|-------------|--------------------------------------------------|
| lat         | Latitude of the incident                         |
| lng         | Longitude of the incident                        |
| desc        | Description of the incident location             |
| zip         | Zip code of the incident                         |
| title       | Type and reason for the emergency call           |
| timeStamp   | Date and time of the incident                    |
| twp         | Township where the incident occurred             |
| addr        | Address of the incident                          |
| e           | Dummy variable (always 1)                        |
| Reason      | General category of the emergency (EMS, Fire, Traffic) |
| Hour        | Hour of the incident                             |
| Month       | Month of the incident                            |
| Day of Week | Day of the week                                  |
| Date        | Date (YYYY-MM-DD)                                |

## File Structure

- `01-911-1.IPY`: Main notebook containing data analysis and visualizations
- `README.md`: Project documentation (this file)
- (Add other files as necessary)

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- matplotlib / seaborn (for visualization)

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone 
   ```
2. Open the notebook:
   ```bash
   jupyter notebook 01-911-1.IPY
   ```
3. Run the cells to explore the data and visualizations.

## Analysis Highlights

- Breakdown of emergency call types (EMS, Fire, Traffic)
- Temporal analysis by hour, day, and month
- Geographic distribution of incidents
- Insights into peak times and locations for emergency services

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with suggestions or improvements.

## Contact

For questions or feedback, please contact:

- Name: Mosopefoluwa Eniserije
- Email: eeniserijemosope@gmail.com

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/59854893/d67265e7-f392-4f44-9820-dcc2982b9e1c/01-911-1.IPY
