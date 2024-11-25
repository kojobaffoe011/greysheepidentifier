# MLLIB

## Description

This repo contains

- a dataset from ITM-Rec which includes student and group preferences on the topics of final projects in data base and data science classes, and it was collected from student questionnaires at the ITM department, Illinois Institute of Technology, USA. More info about the dataset can be found in the ITM-Rec/README.md
- a jupiter notebook that uses the spark mllib to identify 'greysheep' -- users with specific taste and recommending topics using sparks mmlib ALS model they would be interested in

## Prerequisites

- Python 3.x installed
- `pip` package manager
- Spark installed and running
- Jupiter Notebook

## Setup Instructions

1. **Create a virtual environment (optional but recommended):**
   `python -m venv venv`

2. **Activate the virtual environment:**

- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```
  source venv/bin/activate
  ```

4. **Install the dependencies:**
   pip install -r requirements.txt

## Running the Code

After installing the dependencies, make sure Spark is running and locate the main file `greysheepidentifier.ipynb`

## Additional Information

To deactivate the virtual environment, use:
`deactivate`
