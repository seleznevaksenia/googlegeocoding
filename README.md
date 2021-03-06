
# What is Geocoding?

Geocoding is the process of converting addresses (like "1600 Amphitheatre Parkway, Mountain View, CA") into geographic coordinates (like latitude 37.423021 and longitude -122.083739), which you can use to place markers on a map, or position the map.

Reverse geocoding is the process of converting geographic coordinates into a human-readable address.
![Alt text](map.png?raw=true "Example")

## Installation
This package can be installed with help of [Composer](http://getcomposer.org)
```
composer require selezneva/geocoding
```
```
sudo apt-get install redis-server
```
```
php artisan vendor:publish
```
```
in config/geocoding.php put your api key
```
```
in your ENV. file CACHE_DRIVER = redis
```
```
clear routes/web.php file to avoide routes conflicts
```
```
npm run dev
```
```
the project is available by "your-domain-name" in your browser 
```
## How to use functional 
**Geocoding**
```
http://your-domain-name.local/geo/?language=en&address=Paris&formatted=true
```
**Reverse Geocoding**
``` 
http://your-domain-name.local/rev/?language=en&longitude=40.7155809802915&latitude=40.7155809802915&postalCode=true
```
## License

MIT
