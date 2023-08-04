# Tab bar navigation

This is a simple tab bar navigation made with HTML, CSS, and JavaScript.

### HTML

The HTML for this project is very simple. It consists of a `<div>` element with the class `container`. Inside this `<div>` element, there is another `<div>` element with the class `phone`. The `<div>` element with the class `phone` contains the navigation bar.

```html
<div class="container">
  <div class="phone">
    <nav class="navigation">
      <ul class="navigation__list">
        <li class="navigation__item">
          <a class="navigation__link active" href="#home">
            <i class="navigation__icon" data-feather="home"></i>
            <span class="navigation__text">HOME</span>
          </a>
        </li>
        <li class="navigation__item">
          <a class="navigation__link" href="#search">
            <i class="navigation__icon" data-feather="search"></i>
            <span class="navigation__text">SEARCH</span>
          </a>
        </li>
        <li class="navigation__item">
          <a class="navigation__link" href="#categories">
            <i class="navigation__icon" data-feather="layers"></i>
            <span class="navigation__text">CATEGORIES</span>
          </a>
        </li>
        <li class="navigation__item">
          <a class="navigation__link" href="#likes">
            <i class="navigation__icon" data-feather="heart"></i>
            <span class="navigation__text">LIKES</span>
          </a>
        </li>
      </ul>
    </nav>
  </div>
</div>
```

### CSS

The CSS for this project is also very simple. It uses a combination of flexbox and CSS transforms to create the tab bar navigation.

The `.container` element has a background image that is a gradient from light blue to yellow. The `.phone` element has a border radius and a border. It also has