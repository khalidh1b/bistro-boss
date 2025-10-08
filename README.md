# Bistro Boss

Bistro Boss is a food delivery platform where users can create accounts, add foods to their cart, and checkout—similar to other online platforms. This is a MERN (MongoDB, Express, React, Node.js) application with both frontend and backend code in the same repository.

## Features

- User authentication and account creation
- Browse food items and categories
- Add items to cart
- Checkout and order management
- Admin dashboard for managing menu and orders

## Tech Stack

- **Frontend:** React, React Router, Axios, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Authentication:** JWT, bcrypt
- **State Management:** React Context API

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB (local or Atlas)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/khalidh1b/bistro-boss.git
    cd bistro-boss
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Set up environment variables:**
    - Create a `.env` file in the root directory.
    - Add your MongoDB URI and JWT secret:
      ```
       MONGO_URI=your_mongo_uri
      ```

      ```
       ACCESS_TOKEN_SECRET=your_access_token_secret
      ```
      
      ```
       PORT=4000
      ```
      
      ```
       STRIPEZ_SECRET_KEY=your_stripe_secret_key
      ```

4. **Run the application:**
    ```bash
    npm run dev
    ```
    - The frontend will be available at `http://localhost:5173`
    - The backend API will run on `http://localhost:your_.env_port`

## Folder Structure

```
/bistro-boss
  /client      # React frontend
  /server      # Express backend
  README.md
```

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For questions or feedback, please contact [mdkhalidhossen10@gmail.com](mailto:mdkhalidhossen10@gmail.com).