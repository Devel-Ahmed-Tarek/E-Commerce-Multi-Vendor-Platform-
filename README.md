# E-Commerce Multi-Vendor Platform

This is a fully-functional **multi-vendor e-commerce platform** built using **Laravel 11** and **Blade**. It allows multiple vendors to register, list products, manage orders, and interact with customers in a seamless, secure, and scalable environment. The platform includes features such as vendor-specific dashboards, integrated payment gateways, product search and filtering, customer reviews, and a responsive UI.

## Features
- **Vendor Dashboards**: Each vendor can manage their own products, track orders, and view sales data.
- **Product Search and Filtering**: Advanced search functionality with filtering options like price, categories, ratings, etc.
- **Payment Integration**: Secure and easy-to-use **All Payment Gateways** for processing transactions.
- **Customer Reviews**: Enable customers to rate and review products, enhancing trust and user engagement.
- **Responsive Design**: Built with **Blade** templates for a fully responsive and user-friendly interface.
- **Security**: Implemented authentication using **Laravel Breeze**, data validation, and other best practices for a secure platform.

## Technologies Used
- **Backend**: Laravel 11
- **Frontend**: Blade, HTML, CSS, JavaScript
- **Database**: MySQL
- **Payment Gateways**: **All Payment Gateways**
- **Authentication**: Laravel Breeze

## Installation
To set up the project locally, follow these steps:
1. Clone this repository:  
   `git clone https://github.com/yourusername/e-commerce-multi-vendor.git`
2. Install dependencies:  
   `composer install`
3. Set up your environment:  
   Copy `.env.example` to `.env` and configure the database settings.
4. Generate the application key:  
   `php artisan key:generate`
5. Migrate the database:  
   `php artisan migrate`
6. Seed the database (optional):  
   `php artisan db:seed`
7. Serve the application:  
   `php artisan serve`

## Contributing
Contributions are welcome! If you have any improvements, bug fixes, or feature requests, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
