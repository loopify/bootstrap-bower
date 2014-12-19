bootstrap-bower
===============

Identical to the original repo, except for a small addition: The ability to prevent dropdowns from closing when clicking inside the dropdown menu itself.

To prevent a dropdown from closing add a 'prevent-close-on-click' attribute to your 'dropdown-menu' element.

Example:

```html
<button class="dropdown-toggle">

<ul class="dropdown-menu filter-dropdown" prevent-close-on-click role="menu">
  <li>Menu Item</li>
</ul>
```
