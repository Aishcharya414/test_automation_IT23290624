# Test Automation Assignment - IT23290624

Student Registration Number: IT23290624
Student Name: M.D.A.Ariyaratna

## Objective
The objective of this assignment is to test the transliteration accuracy of the Chat Sinhala transliteration function at [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator).

## Project Structure
- `test_automation.py`: The Playwright automation script.
- `test_automation/`: Folder containing the test case data.
  - `Assignment 1 - Test cases.xlsx`: The completed test cases with results.
- `README.md`: Instructions for setup and execution.
- `Git_Repo_Link.txt`: Link to the public GitHub repository.

## Installation Instructions
1. Install Python 3.11 or later.
2. Clone the repository or extract the zip.
3. Install dependencies:
   ```bash
   pip install playwright openpyxl
   playwright install chromium
   ```

## Execution Instructions
To run the automation script:
```bash
python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

## Results
The results are automatically recorded in the `test_automation/Assignment 1 - Test cases.xlsx` file under the 'Actual output' and 'Status' columns.

