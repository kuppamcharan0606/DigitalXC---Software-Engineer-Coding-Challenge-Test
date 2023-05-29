# DigitalXC---Software-Engineer-Coding-Challenge-Test
# Group Occurrences Count

This project provides a Python script that reads an input data file and identifies the occurrences of groups based on a specified identifier in the "Additional comments" column. It outputs a list of group names along with their respective occurrence counts.

## Usage

1. Ensure you have Python 3.x installed on your system.

2. Install the required dependencies by running the following command:

3. Clone this repository to your local machine or download the source code.

4. Place the input data file in the same directory as the script. Make sure it is in the Excel format (.xlsx) and follows the same structure as the provided sample file.

5. Open the script file `group_occurrences_count.py` and modify the following variables as per your requirements:
- `file_path`: Provide the path to the input data file.
- `column_name`: Specify the column name containing the additional comments.
- `group_identifier`: Set the string identifier to locate the groups in the comments.

6. Run the script by executing the following command:

The script will process the input data and display the list of group names along with their respective occurrence counts.

## Example

Suppose you have an input data file named `Input-Data.xlsx` with the following structure:

| Additional comments |
|---------------------|
| Comment 1           |
| Comment 2           |
| Comment 3           |

And you want to identify the groups using the identifier "Groups :" within the "Additional comments" column. After executing the script, the output will be displayed as follows:


Feel free to customize the script and adjust the variables according to your specific requirements.
