# Physics-Data-Analysis
Master scripts, tools, and documentation for Physics Data Collection project — Google Sheets Apps Script + supporting tools.

Physics Data Analysis
=====================

Master scripts, tools, and documentation for the Physics Data Analysis project.

This project uses Google Sheets Apps Script and supporting tools to assist with:

- CSV import and management
- Sheet organization and home pages
- Data validation
- Interval analysis and reduction
- Regression processing (with modular framework)
- Error checking and logging
- User-friendly menus and Help dialog

Project Components
------------------

- Version5.0PhysicsData_SAFE.txt — Master Google Apps Script (Version 5.0)
- HelpDialog_v5.txt — Technical Help dialog (in progress)
- HelpDialog_PLAN.txt — HelpDialog generation plan
- Version_History.txt — Version history and changelog
- Example CSV files (optional)
- Example outputs (optional)

Usage
-----

This project is designed to be used within Google Sheets.

1. Open your target Google Sheet.
2. Open Apps Script editor.
3. Import or paste Version5.0PhysicsData_SAFE.txt.
4. Save and run onOpen() once.
5. Refresh the Sheet → the "CSV Manager" menu will appear.
6. Use menu options to manage data, perform interval analysis, run regression, and more.

Disclamer - Made with help of ChatGPT 4o

Future Plans
------------

- Add external Regression API integration (planned)
- Add CSV archive feature (planned)
- Add smoothing and advanced data processing options
- Expand HelpDialog with more examples

Repository Structure
--------------------

```
/
├── README.md
├── Version5.0PhysicsData_SAFE.txt
├── HelpDialog_PLAN.txt
├── HelpDialog_v5.txt (to be generated)
├── Version_History.txt
├── examples
│   ├── example_data.csv
│   ├── example_interval_analysis.png
│   ├── example_regression_results.png
├── docs
│   ├── HelpDialog_structure.md
│   ├── Regression_API_examples.md
├── scripts
│   ├── test_regression_api.js
│   ├── example_csv_import.js
```

License
-------

This project is shared publicly for collaborative development purposes and to support ongoing project work.
