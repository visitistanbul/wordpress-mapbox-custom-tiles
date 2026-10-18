# Custom Mapbox Integration for WordPress & GeoDirectory

A lightweight PHP code snippet to integrate, customize, and optimize custom Mapbox tiles and layers within WordPress, specifically tailored for directory plugins like GeoDirectory.

## Features

- 🚀 **Custom Tile Loaders:** Overrides default map styles with custom Mapbox Studio styles.
- ⚡ **Performance Optimized:** Minimizes unnecessary map tile requests and assets.
- 📍 **Mapbox API Hooks:** Provides easy-to-use hooks for custom marker icons and popups.
- 📱 **Mobile Responsive:** Works seamlessly across mobile and desktop viewport devices.

## Installation

1. Download or copy the `mapbox-custom-integration.php` file from this repository.
2. Paste the snippet into your active theme's `functions.php` file, or use a code snippet manager plugin (e.g., *Code Snippets*).
3. Replace the placeholder Mapbox Access Token and Style URL with your own credentials.

## Usage Example

```php
// Configure your Mapbox credentials
define('MY_MAPBOX_ACCESS_TOKEN', 'your-mapbox-access-token-here');
define('MY_MAPBOX_STYLE_URL', 'mapbox://styles/your-username/your-style-id');
