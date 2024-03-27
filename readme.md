## Требования
UrlHub прилоение на ларавель. Требования:

- PHP 8.2 or newer
- A web server like Apache or Nginx
- MySQL / MariaDB / SQLite


## Быстрый старт
1. Run `composer install`.

2. Rename `.env.example` file to `.env` or run `cp .env.example .env`.

   Update `.env` to your specific needs. Don't forget to set `DB_USERNAME` and `DB_PASSWORD` with the settings used behind.

3. Run `php artisan key:generate`.

4. Run `php artisan migrate --seed`.

5. Run `php artisan serve`.

6. Login

   | Email             | Username | Password | Access       |
   |-------------------|----------|----------|--------------|
   | admin@urlhub.test | admin    | admin    | Admin Access |
   | user@urlhub.test  | user     | user     | User Access  |


### Compiling assets with Laravel Mix

#### Using Yarn
1. `yarn`
2. `yarn dev` or `yarn prod`

    *You can watch assets with `yarn watch`*

#### Using NPM
1. `npm install`
2. `npm run dev` or `npm run prod`

    *You can watch assets with `npm run watch`*

   Please note that this project uses Yarn as the package manager, so you can't find the package-lock.json file that is needed by NPM.

## Contributing
The people who contribute to UrlHub do so for the love of open source, our users and ecosystem, and most importantly, pushing the web forward together. Developers like you can help by contributing to rich and vibrant documentation, issuing pull requests to help us cover niche use cases, and to help sustain what you love about UrlHub.

Anybody can help by doing any of the following:
- Ask your employer to use UrlHub in projects.
- Contribute to the core repository.

### Running Tests

From the projects root folder run
- `php artisan test`
- or `composer test`
- or `./vendor/bin/phpunit`
