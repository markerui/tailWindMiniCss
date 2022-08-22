# Tailwindcss Mini For UniApp

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
);

$sizeDefault: 30;
$roundedDefault: 6;
$sizes: 0, 8, 10, 12, 14, 16, 18, 20, 22, 24, 28, 30, 32, 36, 40;
$sizes-map: (
	xs: 12,
	sm: 14,
	base: 16,
	lg: 18,
	xl: 20,
	2xl: 24,
	3xl: 28,
	default: $sizeDefault,
	4xl: 32
);

$opacity: 0, 25, 50, 75, 100;
```

## Style(Scss) Import

```css
@import "path/index.scss";
```

## Vue Import Scss Color Variable

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


