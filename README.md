# Petitionary

<!-- # TODO : Add a project logo -->

## Overview

Petitionary is a civic engagement platform that empowers citizens to generate and submit AI-powered petitions to government representatives on important issues like environmental protection, food safety, and public health. The platform aims to shift power to the public by increasing transparency and creating accountability for unresponsive officials.

## Features

- **AI-Powered Petition Generator**: Create professional, effective petitions from simple issue descriptions
- **Representative Matching**: Automatically find your relevant government representatives based on ZIP code
- **Public Petition Board**: Discover trending petitions and track government responsiveness
- **Multiple Submission Options**: Email representatives directly, download as PDF, or share publicly
- **Response Tracking**: Log and track official responses to increase accountability
- **Wall of Silence**: Highlight representatives who consistently ignore constituent concerns

## Project Status

⚠️ **Petitionary is currently in early development** ⚠️

We're building the MVP with a focus on:
1. Multi-step petition creation form
2. AI petition generation
3. Backend petition storage
4. Public petition board with permalinks

## Tech Stack

- **Frontend**: React/React Native with Tailwind CSS
- **Backend**: Serverless functions (Vercel) or FastAPI
- **AI**: Integration with generative AI APIs
- **Data**: AWS for authentication and petition storage
- **Email**: Mailgun or similar for representative communication

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm or yarn
- API keys for OpenAI and Google Civic API (see `.env.example`)

### Installation

```bash
# Clone the repository
git clone https://github.com/JT-Thrash/petitionary.git
cd petitionary

# Install dependencies
npm install

# Copy environment variables and configure them
cp .env.example .env

# Start the development server
npm run dev
```

## Contributing

We welcome contributions to Petitionary! Please read our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before submitting PRs or issues.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-improvement`)
3. Make your changes
4. Run tests (`npm test`)
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to your branch (`git push origin feature/amazing-improvement`)
7. Open a Pull Request

## Roadmap

- ✅ Project initialization
- 🚧 Form UI for petition creation
- 🚧 AI integration for petition generation
- 📅 Representative matching via Google Civic API
- 📅 Public petition board
- 📅 Email submission system
- 📅 Response tracking dashboard
- 📅 Mobile app version

## License

This project is licensed under the [GNU Affero General Public License v3.0](LICENSE.md) - see the LICENSE.md file for details. The AGPL is a copyleft license that requires anyone who distributes your code or a derivative work to make the source available under the same terms. For commercial licensing options that may exempt you from certain AGPL requirements, please contact the project maintainers.

## Contact

Project maintainer: [@JT-Thrash](https://github.com/JT-Thrash)

## Acknowledgments

- Thanks to the open-source community for tools and libraries that make this project possible
- Special thanks to all our contributors