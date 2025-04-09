# Job Portal System

A comprehensive PHP Laravel-based web application designed to support three distinct user roles: Admin, Employer, and Candidate.

## Features

- **Multi-role Authentication**: Admin, Employer, and Candidate roles
- **Job Management**: CRUD operations for job listings
- **Application Tracking**: Candidates can apply and track application status
- **Resume Upload**: File handling for resume uploads
- **Admin Panel**: User management and job post moderation

## Technology Stack

- **Backend**: PHP 8.1, Laravel 10.x
- **Frontend**: HTML, CSS, JavaScript, Bootstrap 5
- **Database**: MySQL

## Installation

1. Clone the repository
2. Run `composer install`
3. Copy `.env.example` to `.env` and configure your database
4. Run `php artisan key:generate`
5. Run `php artisan migrate --seed`
6. Run `php artisan storage:link`
7. Run `php artisan serve`

## Database Setup

1. Create a database named `job_portal`
2. Import the included `job_portal.sql` file (if available)
3. Or run migrations with `php artisan migrate --seed`

## User Roles

- **Admin**: Overall system management and job post approval
- **Employer**: Post jobs and manage applications
- **Candidate**: Browse jobs, submit applications, and track status

## Demo Login Credentials

You can use the following demo credentials to explore the system:

### Admin
- **Email**: admin@gmail.com  
- **Password**: 12345678

### Employer (Post Jobs)
- **Email**: test@gmail.com  
- **Password**: 12345678

### Candidate (User)
- **Email**: john123@gmail.com  
- **Password**: 12345678

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
