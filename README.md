# Kuro Noodle Bar - PHP header/footer demo

A small restaurant site where every page shares `includes/header.php` and `includes/footer.php`.

## Files
- `includes/header.php` - doctype, `<head>`, site title, navigation (active link highlighted automatically)
- `includes/footer.php` - hours, address, contact links, copyright year
- `index.php` - home page with a "special of the day" that changes by weekday
- `menu.php` - menu printed from a PHP array with `foreach`
- `contact.php` - form with validation and output escaping
- `css/style.css` - styling

## Run locally
    php -S localhost:8000
Then open http://localhost:8000
