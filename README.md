# jQuery InputCounter

A simple but powerful jQuery plugin for a input counter.

## Informations

you can design the entire UI yourself (CSS and Icons) or use something like bootstrap.

## Getting Started

see the examples in the examples-directory.

### jQuery options

```
var options = {
    selectors: {
        addButtonSelector: '.btn-add',              // the selector for the add button
        subtractButtonSelector: '.btn-subtract',    // the selector for the subtract button
        inputSelector: '.counter',                  // the selector for the <input />-field
    },
    settings: {
        checkValue: true,                           // if true, verifies that the new value is within the min and max values
        isReadOnly: true,                           //^if true, set the input-field as readonly
    },
};
```

### default html template 

```
<div class="input-counter input-group">
    <div class="input-group-prepend">
        <button type="button" class="btn-add btn btn-primary">
            <i class="fa fa-plus"></i>
        </button>
    </div>
    <input type="text" class="form-control counter" data-default="1" data-min="0" data-max="100">
    <div class="input-group-append">
        <button type="button" class="btn-subtract btn btn-primary">
            <i class="fa fa-minus"></i>
        </button>
    </div>
</div>
```