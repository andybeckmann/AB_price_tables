AB_price_tables
==========

AB_price_tables displays price tables neatly for large, medium, and small screen sizes.

## Screenshot

![Screenshot](/screenshot-desktop.png?raw=true)

## Required files

### Styles
[AB_price_tables/scss/components/_AB_price_tables.scss](https://github.com/andybeckmann/AB_price_tables/blob/master/scss/components/_AB_price_tables.scss)

### Scripts
[AB_price_tables/js/AB_price_tables.js](https://github.com/andybeckmann/AB_price_tables/blob/master/js/AB_price_tables.js)

## Example

### HTML
```html
<div class="price-table-wrapper">
    <ul class="price-table">
        <li>
            <div class="column">
                <a href="#" class="column-header">
                    <h2>1</h2>
                </a>
                <div class="column-details">
                    <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                </div>
                <div class="column-benefits">
                    <table>
                        <tr><td>YES</td></tr>
                        <tr><td>YES</td></tr>
                        <tr><td><span>&#10005;</span></td></tr>
                        <tr><td><span>&#10005;</span></td></tr>
                        <tr><td><span>&#10005;</span></td></tr>
                        <tr><td><span>&#10005;</span></td></tr>
                    </table>
                </div>
                <a href="#" class="column-button">
                    Apply Now
                </a>
            </div>
        </li>
        <li>
            <div class="column middle">
                <a href="#" class="column-header">
                    <h2>2</h2>
                </a>
                <div class="column-details">
                    <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                </div>
                <div class="column-benefits">
                    <table>
                        <tr><td>YES</td></tr>
                        <tr><td>YES</td></tr>
                        <tr><td>YES</td></tr>
                        <tr><td>YES</td></tr>
                        <tr><td>YES</td></tr>
                        <tr><td>YES</td></tr>
                    </table>
                </div>
                <a href="#" class="column-button">
                    Apply Now
                </a>
            </div>
        </li>
    </ul>
</div>
```