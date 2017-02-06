# Woocommerce bs3 starter template
Wordpress woocommerce bootstrap3 starter template kit - latest version

**this is first release we use in our WP+WOO projects, we update it soon here**

# Install
1. copy the woocommerce folder in you wordpress template folder.
2. add code below to your theme's function.php file to support woocommerce plugin (if its not):
```php
add_action( 'after_setup_theme', 'woocommerce_support' );
function woocommerce_support() {
    add_theme_support( 'woocommerce' );
}
```
# Version
bootstrap 3
woocommerce 2.6.12

#author
[Venon Web Deveopers](https://venon.ir)
