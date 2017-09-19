# wp-kit/softdeletes

This is a wp-kit component that provides soft deletes for [```Eloquent```](https://laravel.com/docs/5.4/eloquent) models.

## Installation

If you're using [```Themosis```](http://framework.themosis.com/), install via [```Composer```](https://getcomposer.org/) in the root of your ```Themosis``` installation, otherwise install in your ```Composer``` driven theme folder:

```php
composer require "wp-kit/softdeletes"
```

## Usage

### Model

```wp-kit/softdeletes``` comes with a trait, so all you need to do is include these in your model. 

Based on [```drewjbartlett/wordpress-eloquent```](https://github.com/drewjbartlett/wordpress-eloquent) you can the ```Post``` model provided and use the ```SoftDeletes``` trait.

```php
namespace Theme\Models;

use WPEloquent\Model\Post;
use WPKit\SoftDeletes\SoftDeletes;

class SomePostType extends Post {
	
	use SoftDeletes;
	
}
```

## Get Involved

To learn more about how to use ```wp-kit``` check out the docs:

[View the Docs](https://github.com/wp-kit/theme/tree/docs/README.md)

Any help is appreciated. The project is open-source and we encourage you to participate. You can contribute to the project in multiple ways by:

- Reporting a bug issue
- Suggesting features
- Sending a pull request with code fix or feature
- Following the project on [GitHub](https://github.com/wp-kit)
- Sharing the project around your community

For details about contributing to the framework, please check the [contribution guide](https://github.com/wp-kit/theme/tree/docs/Contributing.md).

## Requirements

Wordpress 4+

PHP 5.6+

## License

wp-kit/softdeletes is open-sourced software licensed under the MIT License.
