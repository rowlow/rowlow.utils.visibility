# rowlow.utils.visibility

Take full control of the visibility of elements among all repsonisve breakpoints.

## Install

```
    bower install --save rowlow.utils.visibility
```

## Variables

```
    $rowlow-visibility-namespace // Specific module namespace
```


## Usage

### Setup
```
    /* Set modules namespace (optional) */
    $rowlow-visibility-namespace: "namespace-";

    @import "bower_components/rowlow.utils.visibility/main.scss"
```

### CSS Selector Naming Scheme
```
    {rowlow-visibility-namespace}visible--{breakpoint-name}
    {rowlow-visibility-namespace}hidden--{breakpoint-name}
```


### HTML
```
    <div class="hidden--s"></div>
    <div class="visible--m visible--l"></div>
```

