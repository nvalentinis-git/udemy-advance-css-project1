# udemy-advance-css-project1


# Features

- SASS
- CSS Architecture - (7-1 Pattern)
- Grid layout with pure CSS (using 'float' and calculated 'width')

### CSS Properties

    - transform: skewX() translateX()
    - clip-path
    - shape-outside
    - box-shadow
    - background-image: linear-gradient(to right bottom,
        rgba($color-primary-light, 0.8),
        rgba($color-primary-dark, 0.8)), 
        url(../../img/nat-4.jpg);
    background-size: cover;

### SASS Mixings

    @mixin clearfix {
        &::after {
            content: "";
            display: table;
            clear: both;
        }
    }