# Bootstrap Queries
Sass mixins based on bootstraps V5 media query breakpoints

### Install
```
npm i boostrap-queries
```

### Mixins

Create a media query finishing at <576px
```scss
@include screen-x-small() {
  ...
}
```

Create a media query finishing at ≥576px
```scss
@include screen-x-small() {
  ...
}
```

Create a media query starting at ≥768px

```scss
@include screen-medium() {
  ...
}

```

Create a media query starting at ≥992px

```scss
@include screen-large() {
  ...
}
```

Create a media query starting at ≥1200px

```scss
@include screen-extra-large() {
  ...
}
```

Create a media query starting at ≥1400px

```scss
@include screen-extra-extra-large() {
  ...
}
```

### Functions

Get x-small dimension
```scss
$bootstrap-x-small: get-x-small();
```

Get small dimension
```scss
$bootstrap-small: get-small();
```

Get medium dimension
```scss
$bootstrap-medium: get-medium();
```

Get large dimension
```scss
$bootstrap-large: get-large();
```

Get extra-large dimension
```scss
$bootstrap-extra-large: get-extra-large();
```

Get extra-extra-large dimension
```scss
$bootstrap-extra-extra-large: get-extra-extra-large();
```

### Utils

Hide elements at any bootstrap v5 screen width
```sass
@include hide-at-screen(get-small(), flex);
```
