# Variables

```
$products = array('car', 'house');
$deletedIssue = 'all of them';
```
## Note

 - Camel case
 - One declaration per line
 - If you feel it necessary to include a comment describing your variable, you have 
 named it wrong

- - -

```PHP
for ($personIndex = 0; $personIndex < count($people); $personIndex++) {

}
```

## Note
 - Do not use single character variable names under any circumstances

- - -

```PHP
$carBrand = 'Toyota';
```

## Note

 - Use single quotes for string declarations that lack interpolated variables

- - -

```PHP
echo "This car is a {$carBrand}";
echo "This car is a {$carBrands[0]}";
```

## Note

 - Use double quotes for strings that have variables interpolated
