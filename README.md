# [getrector.com](https://getrector.com) Website

### Customization

- Use `.env.local` to customize environment variables.

## First Run

Install npm and dependencies:

```bash
sudo apt-get install npm
sudo npm install --global yarn
npm install
yarn run dev
```

Install composer dependencies:

```bash
cp .env.dist .env
composer install
```

Run website in local browser:

```bash
php artisan serve
```
