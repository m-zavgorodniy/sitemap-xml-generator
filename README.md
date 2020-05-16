# XML Sitemap Generator (PHP, Single file)
Generates XML sitemap for search engines by crawling the site with cURL
## Usage
```php
require "sitemap.class.php";

$sitemap = new SiteMap('https://example.com', '/etc/ssl/certs/cacert.pem', 3);
echo $sitemap->generate();
```
