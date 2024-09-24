# Perpetual Calendar

A spreadsheet that provides a perpetual calendar. This calendar automatically highlights the weekends (Saturday and Sunday) and adjusts the number of days for each month, including February's 29th day in leap years.

## Features
- **Weekend Highlighting**: Saturdays and Sundays are automatically highlighted in grey (modifiable).
- **Leap Year Handling**: The calendar correctly adjusts for leap years by including February 29th when applicable.
- **Automatic Updates**: Change the year in the top left cell, and the entire calendar updates to reflect the correct days and dates.

## Usage Instructions
1. **Open the Spreadsheet**: Open the file using LibreOffice Calc (or any other spreadsheet software that supports `.xlsx`).
2. **Change the Year**: To update the calendar to a specific year, simply type the desired year into the top left cell.
3. **Customizing Weekend Colors**:
   - If you want to change the default grey colour for weekends, follow these steps:
     1. Select the range of cells representing the weekends.
     2. Open the **Format** menu and choose **Conditional Formatting**.
     3. Modify the condition or formatting style to change the background colour of weekends.

## How It Works
- The spreadsheet calculates the correct number of days for each month based on the year entered in the top left cell.
- Weekends are automatically detected and highlighted, with the possibility of changing the highlight colour through conditional formatting.

## Compatibility
- **LibreOffice Calc**: Fully supported.
- **Microsoft Excel**: Compatible, though certain formatting features may differ slightly.
