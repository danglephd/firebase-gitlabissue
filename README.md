# GitLab Issue Management System

A web application built with Angular 13 for managing GitLab issues with Firebase integration.

## Features

- View and manage GitLab issues
- Filter issues by status and issue number
- Sort issues by time and issue number
- Integration with Google Drive for project documentation
- Real-time updates using RxJS Subjects
- Material Design UI components

## Prerequisites

- Node.js (v14.x or higher)
- Yarn package manager
- Angular CLI
- GitLab account and API access
- Firebase project setup

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd firebase-gitlabissue
```

2. Install dependencies:
```bash
yarn install
```

## Development

To start the development server:
```bash
ng serve
```
The application will be available at `http://localhost:4200`

## Building for Production

1. Build the application:
```bash
yarn build1
```

2. Deploy to IIS:
- Copy contents from `/dist` folder to `C:\inetpub\wwwroot\gitlabissue`
- Restart IIS

## Project Structure

- `src/app/` - Main application code
  - `issue.service.ts` - Service for managing GitLab issues
  - `issue.ts` - Issue model definition
  - Components and other services

## API Integration

The application connects to:
- GitLab API for issue management
- Firebase for backend services
- Google Drive for project documentation

## Environment Configuration

The application uses different environments:
- Development: `http://localhost:4200`
- Production: Configured in `environment.prod.ts`

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the terms specified in the LICENSE file.

## Support

For support, please contact the development team or create an issue in the repository.