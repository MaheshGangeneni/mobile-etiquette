### Mobile Etiquette System - Project Documentation

# Overview

The Mobile Etiquette System is a Python application designed to help users practice proper mobile phone usage in various social contexts. The system provides location-based etiquette guidelines and allows users to customize rules based on their personal preferences.

# Features

## Core Functionality
**Location-based etiquette rules**: Predefined rules for common locations (restaurants, meetings, public transport, etc.)
**Custom rule creation**: Users can add their own rules for specific locations
**Action verification**: Check if specific phone actions (calls, texting, photos) are appropriate
**Time-based alerts**: Quiet hour notifications for considerate phone usage
**Persistent storage**: All rules and preferences are saved in JSON files

## Technical Specifications
**Language**: Python 3
**Data Storage**: JSON files (`etiquette_rules.json`, `user_preferences.json`)
**Dependencies**: Standard Python libraries (json, os, datetime)

## Installation

1. Ensure you have Python 3 installed on your system
2. Download or clone the project files:
   ```
   git clone https://github.com/MaheshGangeneni/mobile-etiquette-system.git
   ```
3. Navigate to the project directory:
   ```
   cd mobile-etiquette-system
   ```

## Usage

Run the application by executing:
```
python main.py
```

### Main Menu Options
1. **View current etiquette rules**: Displays rules for your current location
2. **Change location**: Set your current location from available options
3. **Check if an action is appropriate**: Verify if a specific phone action is acceptable
4. **Add custom rule for current location**: Create personalized rules for locations
5. **View all locations**: See all predefined locations and their rules
6. **Edit quiet hours**: Adjust your preferred quiet hours
7. **Exit**: Close the application

## File Structure

```
mobile_etiquette/
│
├── main.py                # Main application logic
├── etiquette_rules.json    # Database of default etiquette rules
├── user_preferences.json   # User-specific settings and custom rules
└── README.md              # This documentation file
```

## Default Etiquette Rules

The system comes with predefined rules for these locations:
- Restaurant
- Meeting
- Public transport
- Cinema
- Home

Each location has rules for:
- Ringtone settings
- Phone call etiquette
- Texting guidelines
- Photo policies
- General description

## Customization

Users can:
1. Add completely new locations with custom rules
2. Override default rules for existing locations
3. Set personal quiet hours for notifications
4. Adjust time-based alert preferences

## Future Enhancements

Planned features for future versions:
1. GUI implementation (Tkinter/PyQt)
2. Location detection integration
3. Push notifications for rule changes
4. Etiquette learning modules
5. Social sharing features

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for any improvements.

## License

This project is open-source and available under the MIT License.
