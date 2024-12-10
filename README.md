Overview

The "Add Machines to Collection" tool is a simple, user-friendly UI-based solution designed to quickly add machines to an SCCM collection. By specifying a collection ID and providing a text file with machine names, this tool automatically updates the collection and displays the results on the screen.

Features

- Collection ID Input: Specify the target SCCM collection ID.
- Text File Selection: Upload a text file containing the list of machine names or IDs.
- Run Button: Start the process to add the listed machines to the specified collection.
- Output Display: View the result of the operation directly on the tool's interface.

Instructions

1. Launch the Tool: Open the executable or script for the "Add Machines to Collection" tool.

2. Enter Collection ID:
   - In the provided field, input the desired SCCM collection ID where machines will be added.

3. Select Text File:
   - Click on the "Browse" button to select a text file containing the list of machine names.
   - Ensure the file contains one machine name per line.

4. Click Run:
   - Hit the "Run" button to execute the process.

5. View Results:
   - Once the operation completes, the tool will display the output below the interface. This output includes a summary of the machines added and any potential errors encountered during the process.

Requirements

- A valid SCCM environment.
- Collection ID must exist in SCCM.
- A properly formatted text file with machine names (one per line).


Troubleshooting

- If an error occurs, verify the following:

  1. The collection ID is correct and exists in SCCM.
  2. The text file is formatted correctly with valid machine names.
