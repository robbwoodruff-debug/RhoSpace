# RhoSpace

An internal social platform that connects people within your organization by showcasing professional roles, career milestones, contact details, and personal interests.

## Overview

RhoSpace helps teams build stronger connections by giving every member a rich, discoverable profile. Whether you're looking for a colleague's expertise, celebrating a milestone, or simply learning more about the people you work with, RhoSpace makes it easy.

## Features

- **Professional Profiles** — Display roles, titles, departments, and career history
- **Milestones** — Celebrate promotions, work anniversaries, certifications, and achievements
- **Contact Details** — Centralized, always up-to-date contact information
- **Personal Interests** — Share hobbies and passions to spark human connection across teams
- **Search & Discovery** — Find colleagues by skill, role, location, or interest

## Getting Started

### Prerequisites

- Node.js 18+
- A supported database (PostgreSQL recommended)

### Installation

```bash
git clone https://github.com/robbwoodruff-debug/RhoSpace.git
cd RhoSpace
npm install
```

### Configuration

Copy the example environment file and fill in your values:

```bash
cp .env.example .env
```

### Running Locally

```bash
npm run dev
```

## Project Structure

```
RhoSpace/
├── src/
│   ├── components/     # UI components
│   ├── pages/          # Application pages/routes
│   ├── api/            # Backend API routes
│   ├── models/         # Data models
│   └── utils/          # Shared utilities
├── public/             # Static assets
└── tests/              # Test suites
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
