# Make.com GHL Field Mapper

This tool is designed to help automate the mapping of custom fields between Make.com scenarios when working with new GHL clients. It compares the existing, working scenario JSON (Source Scenario) with a new client's scenario JSON (Target Scenario) and provides the necessary field mappings. The updated JSON with correct field mappings can be downloaded or copied directly for use in Make.com.

---

## Features

- **Field Mapping**: Automatically compares and maps custom fields between the source and target scenarios based on their labels.
- **Export Updated JSON**: After processing, the tool allows you to download the updated scenario JSON with correct field mappings.
- **Copy to Clipboard**: Copies the updated JSON to your clipboard for easy pasting.
- **Responsive Design**: The tool works seamlessly on both desktop and mobile devices.
- **Field Mapping Preview**: Displays a live preview of matched and unmatched fields.

---

## How to Use

1. **Export the Source Scenario JSON:**
   - In Make.com, go to your working scenario → Settings → Export blueprint → Copy the JSON.
   
2. **Create a New Scenario:**
   - Duplicate the existing scenario and connect it to the new client's GHL account.

3. **Export the Target Scenario JSON:**
   - Export the blueprint from the new scenario. The fields in the new scenario will have different IDs.

4. **Paste the JSONs:**
   - Paste the **Source Scenario JSON** in the first text area (working template).
   - Paste the **Target Scenario JSON** in the second text area (new client scenario).

5. **Process Field Mappings:**
   - Click the **Process Field Mappings** button to compare and map the fields.

6. **Review and Download Updated JSON:**
   - After processing, you can review the mapped fields and download the updated JSON file for import into Make.com.

---

## Tool Overview

### Workflow Steps:
1. **Paste Source JSON**: Enter the existing scenario JSON.
2. **Paste Target JSON**: Enter the new client's scenario JSON.
3. **Review Mappings**: Review the field mappings to ensure correctness.
4. **Download Updated JSON**: Download the updated JSON with the correct field mappings.

---

## Installation

The **Make.com GHL Field Mapper** is a web-based tool and does not require installation. To use it, simply follow these steps:

1. **Access the Tool**: Open the [Make.com GHL Field Mapper Tool](https://umairgujjar.github.io/Make.com-GHL-Field-Mapper/) in your browser.
2. **Input the JSONs**: Paste the old and new scenario JSONs into the provided text areas.
3. **Process and Download**: Click the "Process Field Mappings" button, review the results, and download the updated JSON file for import into Make.com.

---

## Contributing

Feel free to fork this repository and create pull requests for new features or bug fixes. You can contribute in the following ways:

- **Bug Fixes**: Report any bugs or issues with the tool.
- **Feature Requests**: Suggest new features to enhance the functionality.
- **Code Improvements**: Submit pull requests for code optimization or enhancements.

---

## License

This tool is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments

- This tool was built using **HTML, CSS, and JavaScript** for a simple yet powerful web interface.
- Special thanks to the **Make.com** and **GoHighLevel** community for inspiration and feedback.
