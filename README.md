Airline Arrival Delays — ALASKA vs AM WEST (Jupyter)

Analyze arrival outcomes across five destinations for ALASKA and AM WEST. The notebook loads a tidy CSV, computes delay rates overall and by destination, creates charts, and exports a descriptive PDF report with narrative, tables, and figures.

Files

airline_delays.csv — tidy dataset with columns:

airline (ALASKA, AM WEST)

status (on time / delayed)

destination (Los Angeles, Phoenix, San Diego, San Francisco, Seattle)

count (integer)

airline_delays_analysis_export.ipynb — main notebook (pivots, charts, PNG export, PDF export)

(Generated) overall_delay_rate.png, delay_rate_by_destination.png — charts

(Generated) airline_delays_report_descriptive.pdf — multi-page, narrative PDF report

How to run

Put airline_delays.csv and airline_delays_analysis_export.ipynb in the same folder.

Open the notebook and Run All.

You’ll see:

Pivot tables of counts and delay rates

Charts (overall delay rate, and by destination & airline)

Saved PNGs and a PDF report in the same folder
If the CSV is missing

Use the notebook’s “load data” cell that auto-creates airline_delays.csv from the values in the assignment. (Or upload your own CSV with the same schema.)

Outputs

Charts:

overall_delay_rate.png

delay_rate_by_destination.png

Report:

airline_delays_report_descriptive.pdf
Contains a cover page, an executive summary (in words), both charts, a table page with destination-level delay percentages, and a methodology/notes page.
