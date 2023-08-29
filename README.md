<h1 align="center">Cheerful</h1>

<p align="center">
  <strong>Your Reward and Recognition Partner</strong>
</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License: MIT">
  </a>
</p>

<p align="center">
  Cheerful is a web platform enabling easy recognition and rewards for outstanding contributions through a point-system which can be exchanged for goods or services from local merchants.
</p>

## :book: Reference
- **Software Requirement Specifications**: <a href="https://docs.google.com/document/d/1jPz97ecTsStaxazhorpz8mcOdpM8mqu8y-gmIpdYLY0/edit?usp=sharing">here</a>
- **User Flow**: <a href="https://www.figma.com/file/S3nzALmaiacqMh3J7e2pUg/Cheerful-user-flow?type=whiteboard&node-id=0%3A1&t=xGdWmVaZU2r395C4-1">here</a>
- **Database Modeling**: <a href="https://dbdiagram.io/d/64bfbd7602bd1c4a5ea98a93">here</a>
- **Software Architechture**: <a href="https://www.figma.com/file/T4YQrtoooL6g8lukT6fVM4/Cheerful-Software-architechture?type=whiteboard&node-id=0%3A1&t=lbWeIsBM1OH05uLa-1">here</a>
- **Brand Guideline**: <a href="https://www.figma.com/file/T4YQrtoooL6g8lukT6fVM4/Cheerful-Software-architechture?type=whiteboard&node-id=0%3A1&t=lbWeIsBM1OH05uLa-1">here</a>

## :rocket: Tech Stack

- **Frontend**: Angular
- **Backend**: NestJS (Node.js)
- **Database**: MySQL
- **Deployment**: Netlify (Frontend), Heroku (Backend), ClearDB (Database)
- **Payment Processing**: Paystack, Stripe
- **Authentication**: JSON Web Tokens (JWT)
- **Authorization**: NestJS Built-in Guards
- **Caching**: Redis
- **Analytics**: Sentry
- **Media Storage**: Amazon S3
- **Source Control**: GitLab
- **CI/CD**: GitLab CI/CD
- **Email**: Gmail with Nodemailer

## :sparkles: Features

- **Point Management**: Load, send, and track points.
- **Digital Gift Cards**: Exchange points for digital gift cards.
- **Merchant Integration**: Local merchants offer gift cards.
- **Secure Authentication**: User data protected with JWT authentication.
- **Real-time Updates**: Stay updated with real-time point changes using Redis.
- **Admin Interface**: Manage business admin and merchant activities.
- **Email Invitations**: Invite individuals via email to register.
- **CSV Bulk Import**: Add connections in bulk via CSV.
- **Product Catalog**: Merchants can upload and manage their products.
- **Gift Card Generation**: Secure and unique gift card codes.
- **Redemption Tracking**: Merchants validate gift card redemptions.

## :zap: Getting Started

1. Clone this repository.
2. Install dependencies with `npm install`.
3. Set up environment variables for database, Redis, Amazon S3, and JWT secret.
4. Run frontend: `ng serve`.
5. Run backend: `npm run start:dev`.

## :bulb: Usage
_<a href="https://drive.google.com/file/d/1JX0rWeyOa7qeihalBay5sjX0dEsou3y_/view">:movie_camera: See how it works</a>_
### Business Admin

1. Register as a business admin from the landing page.
2. Complete registration and provide business information.
3. Invite individuals via email or username.
4. Load points and transfer them to individuals.
5. Access the dashboard and manage redemptions.

### Individuals

1. Register using an invitation via email.
2. Load points securely using Stripe or Paystack.
3. Send and receive points from connections.
4. Explore the marketplace and exchange points for gift cards.

### Merchant

1. Register as a merchant from the landing page.
2. Complete registration and set up your store.
3. Upload your product catalog to the platform.
4. Validate and track gift card redemptions.

## :octocat: Contributing

Contributions are welcome! Open issues and pull requests.

## :scroll: License

This project is licensed under the MIT License.

## :lock: Security

- Authentication: JWT ensures secure user authentication.
- Authorization: NEST JS guards handle access control.
- Gift Card Codes: SHA256 algorithm and secret key ensure code uniqueness.
- Security Scans: Regular AWS CodeWhisperer scans ensure code integrity.
