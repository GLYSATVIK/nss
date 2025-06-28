SevaIITP - NSS IIT Patna Donation Platform
Overview
SevaIITP is a comprehensive donation management platform developed for the National Service Scheme (NSS) at IIT Patna. The platform facilitates various types of donations including blood donation camps, blood requests, fundraising campaigns, and item donations. It provides a user-friendly interface for both donors and administrators to manage and participate in donation activities.

Features
Blood Donation Management
Blood Donation Camps: Create and manage blood donation camps with details like location, date, time, and required blood groups
Blood Requests: Post and respond to urgent blood donation requests
Blood Group Tracking: Track available blood groups and requirements
Fundraising
Campaign Creation: Create fundraising campaigns with goals, descriptions, and categories
Progress Tracking: Monitor campaign progress with visual progress bars
Multiple Categories: Support for medical, education, disaster relief, and social causes
Item Donations
Campaign Management: Create and manage item donation campaigns
Category-based Organization: Organize items by categories (clothing, food, books, etc.)
Drop-off Points: Manage collection points and pickup arrangements
Item Tracking: Track donated items and their conditions
User Management
Role-based Access: Separate interfaces for admin and regular users
User Profiles: Manage user information and donation history
Authentication: Secure login and registration system
Admin Dashboard
Campaign Management: Create, view, and delete all types of campaigns
Analytics: Track donation statistics and campaign progress
Cleanup Tools: Remove completed or expired campaigns
Technology Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MySQL
Authentication: Custom session-based authentication
Prerequisites
Node.js (v14 or higher)
MySQL (v8.0 or higher)
npm (Node Package Manager)
Installation
Clone the repository:

git clone https://github.com/HarshUpadhyay30/SevaIITP.git
cd SevaIITP
Install dependencies:

npm install
Create a .env file in the root directory with the following variables:

DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=donation_db
PORT=3000
Import the database schema:

mysql -u your_mysql_username -p donation_db < database.sql
Start the server:

npm start
Access the application at http://localhost:3000

Database Schema
The application uses the following main tables:

users: User accounts and authentication
blood_donation_camps: Blood donation camp details
blood_donation_requests: Blood request information
fundraising_campaigns: Fundraising campaign details
fundraising_donations: Records of monetary donations
item_donation_campaigns: Item donation campaign details
item_donations: Records of item donations
Usage
For Regular Users
Register an account or login
Browse available donation opportunities
Participate in blood donation camps, respond to blood requests, donate to fundraising campaigns, or contribute items
Track your donation history
For Administrators
Login with admin credentials
Access the admin dashboard
Manage all types of campaigns
Monitor user activities and donation statistics
Clean up completed campaigns
Default Admin Account
Email: admin@donation.com
Password: admin123
