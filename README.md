# QA Risk Dashboard

A web application for tracking quality assurance tasks, risk levels, and providing alerts for high-risk items.

## Overview

This QA Risk Dashboard was developed as a solution to prevent system integration failures like the "Payroll Meltdown" scenario inspired by UK Rail System and "The Phoenix Project." The dashboard helps validate systems integrations, track cross-team dependencies, and sends alerts before going live.

## Features

- **Run QA Check Button**: Simulates refreshing data from backend systems
- **Summary Statistics**: 
  - Clickable cards showing number of incomplete tasks
  - Clickable cards showing high-risk issues
  - Toggle filters to view specific task categories
- **Responsive Task Table**:
  - Department
  - Task name
  - Completion Status (✅/❌)
  - Risk Level (None, Medium, High — color-coded)
  - Notes
- **Alert System**: Shows Slack-style warnings for critical high-risk tasks
- **Filtering Capability**: Easily filter to view incomplete or high-risk tasks
- **Modern UI**: Clean, readable design with cards, badges, and simple fonts

## Screenshots

[Insert screenshots of your application here]

## Demo

[Insert link to video demonstration]

## Technologies Used

- React.js
- Next.js
- CSS/Tailwind CSS
- JSON for mock data (easily replaceable with real API data)

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/qa-risk-dashboard.git
```

2. Navigate to the project directory:
```
cd qa-risk-dashboard
```

3. Install dependencies:
```
npm install
```

4. Run the development server:
```
npm run dev
```

5. Open your browser and visit `http://localhost:3000`

## Usage

- Click "Run QA Check" to simulate refreshing the data
- Use the summary cards to filter for incomplete tasks or high-risk issues
- Review the table for detailed information on all tasks
- Check the alerts section for critical warnings

## Future Enhancements

- Integration with real backend APIs
- Authentication system
- Email notification system
- Historical data tracking
- Custom risk assessment algorithms

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Choose an appropriate license for your project]

## Acknowledgements

- Inspired by "The Phoenix Project" by Gene Kim, Kevin Behr, and George Spafford
- Developed as part of [Your Course Name] at [Your University]
