Amazon Clone

This project is a basic clone of the Amazon website, developed using Next.js and next-auth for authentication. It aims to replicate key functionalities of the Amazon e-commerce platform, including user authentication, product listings, and a shopping cart. The project was developed in 2022 and showcases various modern web development technologies and practices.

Features

    -User Authentication: Secure login and signup using next-auth.
    -Product Listings: Display products with detailed information.
    -Shopping Cart: Add products to the cart and manage them.
    -Responsive Design: Optimized for various screen sizes and devices.
    -Server-Side Rendering: Improved performance and SEO using Next.js.
    -API Integration: Fetch product data from a backend API.

Technologies Used

    -Next.js: A React framework for server-side rendering and static site generation.
    -next-auth: Authentication for Next.js applications.
    -React.js: A JavaScript library for building user interfaces.
    -Tailwind CSS: A utility-first CSS framework for styling.
    -Node.js: JavaScript runtime for the backend.
    -Stripe: Payment processing platform.

Installation

  To get started with this project, follow these steps:

  1. Clone the repository:
  
    git clone https://github.com/yashnayan8795/Amazon-clone.git
    cd Amazon-clone
    
  2. Install dependencies:
   
    npm install
    

  3. Set up environment variables:
  
    Create a .env.local file in the root directory and add the following variables:
    
        NEXTAUTH_URL=http://localhost:3000
        GOOGLE_CLIENT_ID=your_google_client_id
        GOOGLE_CLIENT_SECRET=your_google_client_secret
        STRIPE_PUBLIC_KEY=your_stripe_public_key
        STRIPE_SECRET_KEY=your_stripe_secret_key
        AUTH_TRUST_HOST=true
      
   4. Run the development server:
  
          npm run dev
    
      Open http://localhost:3000 to see the application in action.

Project Structure

    -pages/: Contains the Next.js pages.
    -components/: Reusable React components.
    -styles/: Global and component-specific styles.
    -lib/: Utility functions and helper modules.
    -api/: Backend API routes.

ScreenShots

  <img width="945" alt="amazon1" src="https://github.com/user-attachments/assets/ef1d26bb-8456-4fd3-b387-9cc21cb5d615">

  <img width="949" alt="amazon2" src="https://github.com/user-attachments/assets/c2700622-cde8-45bc-a00f-40773db33e52">


  
Contributing

    Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.
  
      -Fork the repository.
      -Create a new branch (git checkout -b feature-branch).
      -Make your changes.
      -Commit your changes (git commit -m 'Add some feature').
      -Push to the branch (git push origin feature-branch).
      -Open a pull request.

License

    This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

    Special thanks to the creators of Next.js, next-auth, and Tailwind CSS for their amazing tools.
    Inspired by the design and functionality of the original Amazon website.

Note:Please use your own local network url for the project for better results

Learn More

  To learn more about Next.js, take a look at the following resources:

    Next.js Documentation - learn about Next.js features and API.
    Learn Next.js - an interactive Next.js tutorial.
