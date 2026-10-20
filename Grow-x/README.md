# Grow-x — Standalone Angular + PHP Website

This folder documents the Grow-x standalone website project, built with Angular and a PHP contact-form endpoint.

## Local setup

1. Install Node.js 20+ and PHP 8+.
2. Run `npm install`.
3. Run `npm start` for the Angular development server.
4. Deploy the Angular build output and `php/contact.php` to a PHP-enabled web host.
5. Configure `HERON_TO_EMAIL` and `HERON_FROM_EMAIL` for PHP mail delivery.

Note: the earlier project archive passed a ZIP integrity check, but a full Angular build and live email delivery have not been verified.