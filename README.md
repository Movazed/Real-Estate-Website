# Real Estate Website

Welcome to the Real Estate Website project! This project aims to create a fully functional real estate website where users can search for properties, view property details, and contact real estate agents. The website is built with modern web technologies to ensure a seamless user experience.

## Features

- User authentication and authorization
- Property search with filters (location, price, type, etc.)
- Property detail pages with images, descriptions, and maps
- Contact forms for inquiries
- Responsive design for mobile and desktop
- Admin panel for managing properties and users

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/real-estate-website.git
    cd real-estate-website
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Set up the environment variables. Create a `.env` file in the root directory and add the following:
    ```env
    DB_HOST=your_database_host
    DB_USER=your_database_user
    DB_PASS=your_database_password
    SECRET_KEY=your_secret_key
    ```

4. Run the development server:
    ```bash
    npm start
    ```

5. Open your browser and go to `http://localhost:5173`.

## Usage

- **Home Page:** Browse featured properties and search for properties.
- **Search:** Use the search bar and filters to find properties that match your criteria.
- **Property Details:** Click on a property to view its details, images, and location.
- **Contact Agent:** Use the contact form on the property detail page to inquire about the property.
- **Admin Panel:** Log in as an admin to manage properties and users.


## Technologies Used

- **Frontend:** React, Redux, CSS, Bootstrap
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT
- **Hosting:** Vercel/Netlify
- **Other:** Google Maps API, Cloudinary

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
