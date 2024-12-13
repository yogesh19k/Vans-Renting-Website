# VanBnb - Van Rental App

Welcome to **VanBnb**, a van rental application built to simplify renting vans for adventures. This project is inspired by the Scrimba course on React Router 6 and demonstrates the practical implementation of client-side routing in a React app.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

**VanBnb** is designed for travelers and van enthusiasts looking for a seamless way to rent vans. It allows users to explore a catalog of available vans, view details about each van, and book the perfect ride for their journey. Additionally, van owners can list their vans for rental.

This app is a hands-on project that showcases:
- Dynamic routing
- Nested routes
- Route parameters
- Protected routes
- React hooks like `useParams` and `useNavigate`

---

## Features

- **Explore Vans**: Browse through a variety of vans available for rent.
- **Van Details**: View detailed information about each van, including pricing and availability.
- **Authentication**: Log in to access additional features like booking and managing vans.
- **Book a Van**: Securely book your favorite van for your next trip.
- **Host Dashboard**: For van owners to list and manage their vans.

---

## Technologies Used

- **React**: For building the user interface.
- **React Router 6**: For implementing client-side routing.
- **CSS**: For styling the application.
- **JSON Server**: As a mock backend API for demonstration purposes.

---

## Getting Started

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- npm (comes with Node.js) or yarn

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/vanbnb.git
   cd vanbnb
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the JSON server (mock backend):
   ```bash
   npm run server
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The app will run locally on [http://localhost:3000](http://localhost:3000).

---

## Usage

### Browsing Vans
Navigate to the homepage to view all available vans. Click on a van to view detailed information, including price, type, and additional features.

### Booking a Van
Log in to your account, select a van, and follow the prompts to book it for your desired dates.

### Host Dashboard
Van owners can log in to access the host dashboard, where they can:
- List new vans for rent.
- Manage existing listings.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

This project is inspired by the Scrimba React Router 6 course and demonstrates the application of modern React routing concepts.