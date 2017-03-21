
## How to install
1. Download or git clone the source files from a repo
2. composer install
3. Create a database for this app
3. Edit the .env files to fit your environment
4. php artisan migrate --seed
5. Make sure there is no error.
6. Configure your localhost to host the app (e.g. 1stop-crm.dev)
7. You should be good to go by pointing to the URL on your web browser
8. If you want to create or clone another instance of the app, make sure you change the app key of the instance by running the following artisan command:

php artisan key:generate

## How to login

Email: admin@admin.com
Password: admin123

## Features overview
- Tasks management
- Leads management
- Simple invoice management
- Easy & simple time management for each task
- Role management (Create and update your own roles)
- Easy configurable settings
- Client overview (Keep easy track of open tasks for each client etc)
- Upload documents to each clients (easy track of contracts and more)
- Fast overview over your own open tasks, leads etc
- Global dashboard
