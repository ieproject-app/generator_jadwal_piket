# Shift Scheduling Web App (Client-side)

A responsive web application for generating fair shift schedules with holiday support, export capabilities, and persistent configuration.

![Screenshot](https://via.placeholder.com/800x500?text=Shift+Scheduling+App+Screenshot) 
*(Replace with actual screenshot)*

## Features

- 📅 **Date Range Selection**: Define start and end dates for the schedule
- 🏖️ **Holiday Management**: Add multiple holidays with visual picker
- 👥 **Group Management**: 
  - Input groups via textarea or import from TXT file
  - Two scheduling modes:
    - 🔀 Random shuffle with fair distribution
    - ✋ Manual fixed order
- 📊 **Schedule Display**:
  - Organized by month in vertical layout
  - Columns split for long months (max 15 rows)
  - Holidays highlighted in red with "Libur" label
- 🔍 **Filtering Options**:
  - Filter by month, group, or holidays only
  - When filtering by group, all relevant months are shown
- 💾 **Export Capabilities**:
  - Download as CSV or Excel (XLSX) with proper formatting
  - Export/Import generator data (JSON) to save and reload schedules
- 🎨 **Clean UI**: Responsive, minimalist design using Tailwind CSS

## Usage

1. Set date range
2. Add groups (one per line or import from TXT)
3. Mark holidays (optional)
4. Choose scheduling mode (random or manual)
5. Click "Generate"
6. Filter or export as needed

## Technical Details

- Pure client-side implementation (no server required)
- Uses ExcelJS for reliable Excel export across browsers
- Persistent "Export Generator" feature saves all settings
- Responsive design works on mobile and desktop

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for version history and updates.

## License

[MIT](LICENSE)
