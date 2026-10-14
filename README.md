# SWYNEX – Data Cleaning & Preparation (Task 1)

## Project overview
This project demonstrates a basic data-cleaning workflow using a small **synthetic practice dataset** of student records. The records are fictional and are for demonstrating data-cleaning methods only; they are not real student data.

## Files
- `SWYNEX_Data_Cleaning_Preparation.xlsx` – workbook with Raw Dataset, Cleaned Dataset, Cleaning Log, and Summary sheets.
- `README.md` – project description and cleaning decisions.
- `LinkedIn_Post_Draft.txt` – draft post to publish only after reviewing and understanding the project.

## Data-quality issues handled
1. Missing values in Age, Marks, and Attendance.
2. A non-numeric age value (`twenty`).
3. An exact duplicate record for student ID S009.
4. Invalid marks above 100 and attendance above 100%.
5. Inconsistent gender labels (`M`/`F`).
6. Inconsistent department formatting (case and extra spaces).
7. Numeric fields originally stored as text.

## Cleaning decisions
- Converted Age, Marks, and Attendance to numeric values.
- Removed the exact duplicate row.
- Standardized gender labels to `Male` and `Female`.
- Trimmed spaces and standardized department labels to uppercase.
- Treated marks and attendance outside the 0–100 range as invalid/missing.
- Filled missing numeric values using each column's median. This is a simple demonstration choice; in a real project, the filling strategy should be selected based on context and documented.

## How to use
Open the Excel workbook. Compare `Raw Dataset` with `Cleaned Dataset`, then review `Cleaning Log` to see each issue and the action taken. `Summary` shows the row counts.

## Important submission note
The SWYNEX task page requests a repository or cloud-folder link and a LinkedIn explanation-post link. Upload this workbook and README to a repository you control (for example, a public GitHub repository) or a Google Drive folder. Then paste your own share link in the task form. Publish the LinkedIn post yourself and paste the URL of the published post. Do not submit a local file path as a link.
