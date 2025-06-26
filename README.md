
# Task 1: Data Cleaning and Preprocessing

## Dataset: Medical Appointment No Shows

### Summary of Changes:
- Removed duplicate rows using Excel's 'Remove Duplicates' / Pandas `drop_duplicates()`.
- Filled missing values in Gender, Age, and ScheduledDay using forward fill.
- Standardized Gender values (converted to lowercase and replaced 'female' to 'f').
- Converted 'ScheduledDay' and 'AppointmentDay' to `dd-mm-yyyy` datetime format.
- Renamed all column headers to lowercase and replaced spaces with underscores.
- Ensured Age is numeric and Date columns are datetime formatted.

This dataset is now clean and ready for analysis or modeling.
