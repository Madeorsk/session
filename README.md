# Session

Easy Session handling in PHP.

## Quick start

```php

use Session\Session;

// Initialize session.
$session = new Session();

$session->write("name", "this is a text value"); // Save "this is a text value" in the session.

// ...

echo $session->read("name"); // Will echo "this is a text value".
echo $session->read("undefined_name", "my default value"); // Will echo "my default value".

// ...

$value = $session->delete("name"); // Delete the value of the session variable "name" in the session and return it.

```

## Full documentation

Full API documentation is currently a work in progress. You can still see the full documentation of the different methods in the source code.
