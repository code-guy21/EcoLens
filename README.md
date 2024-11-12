# EcoLens

EcoLens is a sustainable marketplace app designed to connect users with eco-friendly products and promote green living. The platform allows users to browse and purchase environmentally friendly products, track their eco-impact, and engage with the community. Vendors can list their products, manage inventory, and interact with customers, all while contributing to a greener planet.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Features

- **Product Marketplace**: Browse and purchase eco-friendly products across various categories.
- **Vendor Dashboard**: Vendors can manage product listings, track sales, and interact with customers.
- **Eco Impact Tracker**: Track the environmental impact of your purchases to help reduce your carbon footprint.
- **Product Reviews and Ratings**: Leave feedback on products to encourage responsible and sustainable choices.
- **Notifications**: Real-time alerts on special deals, new products, and low inventory items.
- **Secure Payments**: Make secure transactions directly within the app using integrated payment gateways.

## Tech Stack

### Front-End

- **React**: For building a responsive and interactive user interface.
- **TypeScript**: For type safety and enhanced developer experience.
- **Redux Toolkit**: For managing global application state, such as user sessions and product data.
- **Axios**: For making API calls.
- **React Router**: For seamless navigation and routing.

### Back-End

- **Node.js** with **TypeScript**: For server-side scripting and enhanced type safety.
- **Express.js**: For building a RESTful API.
- **GraphQL**: For flexible data fetching and efficient querying.
- **PostgreSQL** with **Sequelize**: For managing relational data, such as user accounts, product inventories, and transaction history.

### API Integration

- **Stripe API** or **PayPal API**: For secure payment processing within the app.
- **Firebase Cloud Messaging**: For sending real-time notifications to users about deals and product updates.

### CI/CD and Deployment

- **GitHub Actions**: For automated testing, building, and deployment.
- **Docker**: For containerization to ensure consistent deployment environments.
- **Google Cloud Platform (GCP)**:
  - **Google Kubernetes Engine (GKE)**: For orchestrating Docker containers and managing app deployment.
  - **Cloud SQL**: For hosting and managing the PostgreSQL database.
  - **Firebase**: For managing notifications and potentially real-time data syncing.

### Analytics

- **Google BigQuery**: For analyzing eco-impact data and providing insights into user purchase behavior.

### Testing

- **Jest**: For unit and integration testing.
- **React Testing Library**: For testing frontend components.
- **Supertest**: For API endpoint testing.
- **Cypress**: For end-to-end testing of user interactions and workflows.

### Authentication

- **JWT (JSON Web Tokens)**: For secure, stateless user authentication.
- **OAuth 2.0**: For social login integrations like Google or Facebook.

## Usage

1. **Sign Up**: Register an account as a user or vendor.
2. **Browse Products**: Explore a wide range of eco-friendly products across various categories.
3. **Make a Purchase**: Add items to your cart and securely checkout using Stripe or PayPal.
4. **Track Impact**: View your eco-impact based on your purchases and get tips on reducing your carbon footprint.
5. **Vendor Management**: Vendors can manage their inventory, track sales, and interact with customers through the vendor dashboard.
6. **Notifications**: Receive real-time alerts on deals, new product listings, and updates on your orders.

## License

Green Market is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

Alexis San Javier - [ucfknight2017@gmail.com](mailto:ucfknight2017@gmail.com)

- **Website**: [alexissj.net](https://www.alexissj.net)
- **LinkedIn**: [linkedin.com/in/alexissj](https://linkedin.com/in/alexissj)
