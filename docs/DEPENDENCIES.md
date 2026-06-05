# F3 Billing Software - Open Source Dependencies

This document lists all open-source dependencies used in F3 Billing Software.

## Backend Dependencies

### Core Framework
- **express** (MIT) - Web application framework
- **express-async-errors** (MIT) - Async error handling middleware

### Database
- **sequelize** (MIT) - Promise-based ORM
- **pg** (MIT) - PostgreSQL client for Node.js

### Security
- **bcryptjs** (MIT) - Password hashing
- **jsonwebtoken** (MIT) - JWT token generation and verification
- **helmet** (MIT) - Security headers middleware
- **cors** (MIT) - CORS middleware

### Utilities
- **dotenv** (BSD-2-Clause) - Environment variable management
- **joi** (BSD-3-Clause) - Data validation
- **moment** (MIT) - Date and time library
- **multer** (MIT) - File upload handling
- **pdfkit** (MIT) - PDF generation

### Development
- **nodemon** (MIT) - Auto-restart during development
- **jest** (MIT) - Testing framework
- **supertest** (MIT) - HTTP assertion library
- **sequelize-cli** (MIT) - Database migration tool

## Frontend Dependencies

### Core Framework
- **react** (MIT) - UI library
- **react-dom** (MIT) - React DOM rendering
- **react-router-dom** (MIT) - Routing library

### UI Components
- **bootstrap** (MIT) - CSS framework
- **react-bootstrap** (MIT) - Bootstrap React components

### Utilities
- **axios** (MIT) - HTTP client
- **date-fns** (MIT) - Date utilities
- **moment** (MIT) - Date manipulation

### Forms & Validation
- **formik** (Apache-2.0) - Form state management
- **yup** (MIT) - Schema validation

### Notifications
- **react-toastify** (MIT) - Toast notifications

### Data Visualization
- **recharts** (MIT) - Charts and graphs

### Development
- **react-scripts** (MIT) - Create React App scripts
- **@testing-library/react** (MIT) - Testing utilities
- **@testing-library/jest-dom** (MIT) - DOM testing helpers

## Infrastructure

### Containerization
- **docker** (Moby) - Container platform
- **docker-compose** (Moby) - Multi-container orchestration

### Version Control
- **git** (GPL-2.0) - Version control system

## Database
- **PostgreSQL** (PostgreSQL License) - Open-source relational database

## License Compatibility

All dependencies have licenses compatible with MIT License:
- MIT License (most permissive)
- Apache 2.0 License (permissive with some conditions)
- BSD Licenses (permissive)
- ISC License (permissive)

## Commercial License NOT Required

This entire project uses exclusively open-source software. No proprietary or
commercial software is required to develop, deploy, or run this application.

## Updating Dependencies

To update dependencies safely:

```bash
# Check for updates
npm outdated

# Update all dependencies
npm update

# Update major versions (breaking changes possible)
npm install <package>@latest

# Always test after updating
npm test
```

## Security Auditing

To check for security vulnerabilities:

```bash
npm audit
npm audit fix
```

## Support and Documentation

For each dependency, refer to:
- Package homepage in npm registry
- GitHub repository (if available)
- Official documentation

---

Last Updated: June 2024
