
 
# Cosmic CSS Framework ☄️ :

_Cosmic is a CSS Framework ☄️. It has More Unique Component Designs eg: Bouncing Button, Neumorphism, Responsive Cards, Rainbow Spinner, etc.,_

# Get Started with Cosmic 🐣

### Installation ⚙️

#### Via NPM

```npm
npm install cosmiccss
```

#### Via CDN

[CDN LINK 🔥](https://raw.githack.com/Aravindakrishnan/Cosmic/master/cosmic/css/cosmic.min.css)

# How to Use Cosmic ? 🤔

_Create an Link Tag inside the Head_

### NPM

```html
<link rel="stylesheet" href="./node_modules/cosmiccss/css/comic.min.css" />
```

### CDN

```html
<link
  rel="stylesheet"
  href="https://raw.githack.com/Aravindakrishnan/Cosmic/master/cosmic/css/cosmic.min.css"
/>
```

# Features of Cosmic ? 🌈

- Neumorphism
- Buttons
- Cards
- Rainbow Spinner & More
- Backgrounds
- Outline Buttons
- Alert
- Colorful Input-control
- Quote
- Marker
- Navbar
- Image

# Feature #1 Neumorphism

### neumorphic classes 📖

- neumorphism-dark
- neumorphism-dark-inset
- neumorphism-light
- neumorphism-light-inset
- neumorphism-primary
- neumorphism-lens
- neumorphism-concave
- neumorphism-convex

_If you are going to use dark neumorphism give a body className as theme-dark_

_If you are going to use light neumorphism give a body className as theme-light_

## Dark 🌑

![alt neumorphismdarkinset](https://i.ibb.co/X4grgrG/neumorphismdarkinset.png)

```html
<div
  class="card bg-dark border-radius-min neumorphism-dark-inset"
  style="max-width: 500px"
>
  <div class="card-body text-white">
    <h4 class="card-title">Welcome to the Neumorphism 🔥</h4>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus,
      laborum. Suscipit, voluptate.
    </p>
    <button class="btn btn-dark mt-2 text-white">View Profile</button>
  </div>
</div>
```

## Light ☀️

![alt neumorphismlight](https://i.ibb.co/n0NFj7s/neumorphismlight.png)

```html
<div
  class="card bg-white border-radius-min neumorphism-light"
  style="max-width: 500px"
>
  <div class="card-body text-dark">
    <h4 class="card-title font-lg">Welcome to the Neumorphism 🔥</h4>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus,
      laborum. Suscipit, voluptate.
    </p>
    <button class="btn btn-dark mt-2 text-white">View Profile</button>
  </div>
</div>
```

# Feature #2 Buttons

### #Normal-Buttons

![alt normalbuttons](https://i.ibb.co/27ysQdL/normalbuttons.png)

```html
<button class="btn btn-primary">Primary button</button>
<button class="btn btn-danger">Danger button</button>
<button class="btn btn-secondary text-white">Secondary button</button>
<button class="btn btn-dark text-white">Dark button</button>
<button class="btn btn-warning">Warning button</button>
<button class="btn btn-success">Success button</button>
<button class="btn btn-aqua text-white">Aqua button</button>
<button class="btn btn-special text-white">Special button</button>
<button class="btn btn-white text-dark">White button</button>
```

### #Outline-Buttons

![alt outlinebuttons](https://i.ibb.co/gZsJWFZ/outlinebuttons.png)

```html
<button class="btn btn-outline-primary">Primary button</button>
<button class="btn btn-outline-danger">Danger button</button>
<button class="btn btn-outline-secondary">Secondary button</button>
<button class="btn btn-outline-dark">Dark button</button>
<button class="btn btn-outine-warning">Warning button</button>
<button class="btn btn-outline-success">Success button</button>
<button class="btn btn-outline-aqua">Aqua button</button>
<button class="btn btn-outline-special">Special button</button>
<button class="btn btn-outline-white">White button</button>
```

### More Classes for buttons

- btn-muted / btn-disabled
- btn-lg
- btn-block
- btn-group

# Feature #3 Cards

![alt cardimg](https://i.ibb.co/0fDhSCS/cards.png)

```html
<div class="card bg-aqua border-radius-min" style="max-width: 500px">
  <img
    class="img-fit border-radius-min"
    src="https://f4.bcbits.com/img/a3808804510_10.jpg"
    alt="img"
  />
  <div class="card-body text-white">
    <h2 class="card-title">We are Developers 😇</h2>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Modi dolores
      dolore magni!
    </p>
    <button class="btn btn-aqua text-white mt-2">View Profile</button>
    <button class="btn btn-aqua text-white mt-2">Follow</button>
  </div>
</div>
```

##### # Color Available in Cosmic 🌈

<br/>
- primary
- secondary
- danger
- warning
- success
- dark
- white
- special
- aqua

# Feature #4 Spinner

### # Normal Spinner

![](https://i.ibb.co/NTVYzpC/spinner.png)
<br/><br/>
_danger | warning | success | primary | dark | secondary | white | special | rainbow_

```html
<div class="spinner-colorName"></div>
```

### # Spinner sizes

- spinner-colorName-sm / spinner-colorName-min
- spinner-colorName-md / spinner-colorName-avg
- spinner-colorName-lg / spinner-colorName-max

### # Spinner Props

- spinner-colorName / spinner-colorName-sizes
- spinner-colorName-grow / spinner-colorName-grow-sizes
- spinner-dotted-colorName / spinner-dotted-colorName-sizes

# Feature #5 Alerts

![alt alertimg](https://i.ibb.co/jRcKhzz/alerts.png)

```html
<div class="alert alert-primary">Primary AlertBox</div>
<div class="alert alert-dark text-white">Dark AlertBox</div>
<div class="alert alert-danger text-dark">Danger AlertBox</div>
<div class="alert alert-warning">Warning AlertBox</div>
<div class="alert alert-success">Success AlertBox</div>
<div class="alert alert-secondary">Secondary AlertBox</div>
<div class="alert alert-special">Special AlertBox</div>
<div class="alert alert-aqua">Aqua AlertBox</div>
<div class="alert alert-white text-dark neumorphism-light">White AlertBox</div>
```

![](https://i.ibb.co/wpFMcLx/cosmiclogo.png)
