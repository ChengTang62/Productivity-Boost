# Productivity Boost - Visualize Upcoming Deadlines & Task Trees

## Run Script

Please make sure to have Anaconda installed.

In the project directory, run:

#### `conda env create -f ddlviz.yaml`

to create the virtual environment for the project, 

#### `conda activate ddlviz`

to activate the virtual environment, 

Then run:

#### `jupyter-notebook`

to launch Jupyter Notebook.

## Features

#### Add/Delete task
#### Add/Delete subtask
#### Add deadline(s) on selected Date
#### (Un)Highlight current task threads
#### Task tree Visualization
#### Deadline Visualization
#### Calendar Work/Off day visualization
#### Data persistance
##### JSON File Structure

#### Example:

```json
{
  "tasks": [
    {
      "task": "Task Name",
      "subtasks": [
        {
          "Subtask Name": [
            "Sub-subtask Name",
            "... (other sub-subtasks)"
          ],
          "... (other subtasks)"
        }
      ]
    },
    "... (other tasks)"
  ],
  "deadlines": {
    "YYYY-MM-DD": ["Deadline 1", "... (other deadlines)"],
    "... (other dates with their associated deadlines)"
  }
}

## To Do

1. Fix misformat json file
2. Save highlight information