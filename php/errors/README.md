# Errors

```
ini_set('display_errors', true);
error_reporting(E_ALL); // < PHP 5.4
error_reporting(E_STRICT); // >= PHP 5.4
```
## Note

 - Set error reporting to the most verbose level possible in development

- - -

## NEVER

```PHP
$someValue = @$anArray['key'];
```

## Note
 - Never use the `@` operator

