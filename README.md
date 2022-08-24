# Tailwindcss Mini For UniApp\Mini Program

## Variable (_variable.scss)
```scss
$unit: rpx;  //unit default rpx

$black: #000;
$white: #fff;
$primary: #007bff;
$success: #28a745;
$info: #17a2b8;
$warning: #ffc107;
$error: #dc3545;

$colors: (
	black: $black,
	white: $white,
	primary: $primary,
	success: $success,
	info: $info,
	warning: $warning,
	error: $error
) !default;

$sizeDefault: 32;
$roundedDefault: 6;
$sizes: 0, 8, 10, 12, 14, 16, 18, 20, 22, 24, 28, 30, 32, 36, 40, 42, 48, 52, 60;
$sizes-map: (
	xs: 24,
	sm: 28,
	default: $sizeDefault,
	base: 32,
	lg: 36,
	xl: 42,
	2xl: 48,
	3xl: 52,
	4xl: 60
);

$opacity: 0, 25, 50, 75, 100;
```

## Style(css) Import

```css
<link rel="stylesheet" href="path/index.css" />
```
## Style(Scss) Import

```css
@import "path/index.scss";
```

## JavaScript Import Scss Color Variable

```js

import tailwind from 'path/import.scss'

console.log(tailwind)
/*
output {
    black: $black;
    white: $white;
    primary: $primary;
    success: $success;
    info: $info;
    warning: $warning;
    error: $error;
}
*/

console.log(tailwind.black)
/*
output #000(black)
*/
```

## Build css
[Link Build Css](./index.css)
## Readme More 

- [Tailwindcss](https://tailwindcss.com/)
- [UniApp](https://uniapp.dcloud.io/)


