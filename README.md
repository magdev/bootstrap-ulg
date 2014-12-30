# Bootstrap 3 for ultra-large desktops

A Bootstrap 3 stylesheet for ultra-large (>= 1600px) screens.

## Install

Using bower

```bash
bower install bootstrap-ulg
```

Or download the desired css file from the [dist-folder](dist/) manually.


## Usage

Include the stylesheet after bootstrap.css

```html
<link rel="stylesheet" href="/path/to/bootstrap-ulg.min.css"/>
```

Use the *-ulg styles in the same way as the other size-related classes.

```html
<div class="row">
    <div class="col-ulg-10">
        <h1>Lorem ipsum dolor</h1>
    </div>
    <div class="col-ulg-1 col-ulg-push-1">
        <button type="button" class="btn btn-primary btn-ulg">Button</button>
    </div>
</div>
```

### Supported Elements

  * Grid-System
  * Buttons, Button-Groups
  * Form- and Input-Elements, Input-Groups
  * Responsive Utilities
  * Wells
  * Modals
  * Pagination


## License

This software is released under the [MIT-License](LICENSE.md)
