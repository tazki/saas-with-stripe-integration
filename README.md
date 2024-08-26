# Laravel 11 + React SPA Project

A simple project management application using Laravel 11 and React.

I follow this tutorial for a SPA Project to further learn more about React implementation

## Features

1. Registration & Login
2. Create features and charge credits to users by using these features.
3. Control which features you want to publish on the website from the database.
4. Assign number of required credits to each feature.
5. Control how many free credits you want to give to a user upon registration.
6. When user uses particular feature user's number of credits decrease.
7. If the user does not have enough credits for particular feature the feature gets blocked.
8. Full control of how many tiers of packages you want to show. How many credits each package should contain or what should be it's price.
9. Implement buying more credits using Stripe.
10. Track your feature usage history.

## Installation

1. Clone the project
2. Navigate to the project's root directory using terminal
3. Create `.env` file - `cp .env.example .env`
4. Execute `composer install`
5. Execute `npm install`
6. Set application key - `php artisan key:generate --ansi`
7. Execute migrations and seed data - `php artisan migrate --seed`
8. Start vite server - `npm run dev`
9. Start Artisan server - `php artisan serve`

## Credits

-   [TheCodeholic](https://www.youtube.com/watch?v=BdGvI3W0f9E)
