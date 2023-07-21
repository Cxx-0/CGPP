# Cooperative Global Path Planning for Multiple Platforms
This repository stores the codes of our CGPP Framework

### Train the Model

1. Run the `python main_train.py` command to train the model.
2. The training result will be saved in the `Output_model/XXX.pkl` file.

### Test the Model

Run the `python main_test.py` command to test the model.

## Dataset

The dataset used in this project is map data, including map data and user origin-destination data. We provide a sample dataset:

- [Map data](edge.csv, node.csv)
- [User origin-destination data] (initial_query_test)

### Data Format

#### Map Data

edge.csv
| Column Name | Data Type | Description |
| --- | --- | --- |
| start_node | int | Starting location |
| end_node | int | Ending location |
| distance | float | Distance between the starting and ending locations |
| ... | ... | ... |

node.csv
| Column Name | Data Type | Description |
| --- | --- | --- |
| ID | int | The ID of each node |
| X | float | Longitude |
| X | float | Latitude |
| ... | ... | ... |
