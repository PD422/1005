# U100 - Startup Investment Platform

A comprehensive React-based platform for startup investment, connecting entrepreneurs with investors and providing market insights.

## Features

- **Investment Opportunities**: Browse and invest in promising startups
- **Portfolio Management**: Track your investments and returns
- **Market Data**: Real-time market insights and analytics
- **VC Radar**: Connect with venture capital firms
- **Demo Day Events**: Participate in startup showcases
- **Founder Profiles**: Meet innovative entrepreneurs
- **Community Features**: Engage with other investors
- **Mobile Optimized**: Responsive design for all devices

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone or download the project files
2. Navigate to the project directory:
   ```bash
   cd U100
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and visit: `http://localhost:3000`

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm run vercel-build` - Builds the app for Vercel deployment
- `npm eject` - Ejects from Create React App (one-way operation)

## Deployment

### Deploy to Vercel (Recommended)

This project is optimized for Vercel deployment:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

Or connect your GitHub repository to Vercel for automatic deployments.

See [DEPLOYMENT.md](./DEPLOYMENT.md) for detailed deployment instructions.

## Technology Stack

- **Frontend**: React 18, React Router
- **Styling**: Tailwind CSS
- **Charts**: Chart.js with React Chart.js 2
- **Icons**: Lucide React
- **Build Tool**: Create React App

## Project Structure

```
src/
├── components/          # React components
├── contexts/           # React context providers
├── hooks/              # Custom React hooks
├── utils/              # Utility functions and mock data
├── App.js              # Main app component
└── index.js            # App entry point
```

## Features Overview

### Investment Platform
- Browse startup projects by category and stage
- View detailed project information and financials
- Make investments with secure processing
- AI-powered investment analysis

### Portfolio Management
- Track all your investments in one place
- Monitor performance and ROI
- Receive updates on portfolio companies
- Advanced analytics and reporting

### Market Intelligence
- Real-time market data for stocks, crypto, and commodities
- Market trends and analysis
- Economic indicators and insights

### Networking
- Connect with other investors
- Find and match with VC firms
- Attend virtual demo day events
- Community discussions and insights

## Mock Data

The application uses mock data for demonstration purposes. In a production environment, this would be replaced with real API calls to backend services.

## Contributing

This is a demonstration project. For production use, consider:

1. Implementing real authentication
2. Connecting to actual APIs
3. Adding comprehensive testing
4. Setting up CI/CD pipelines
5. Implementing security best practices

## License

This project is for demonstration purposes.
