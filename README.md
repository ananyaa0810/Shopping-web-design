

<body>
    <div id="app">
        <div class="shoe-selector">
      
          <div class="shoe" data-active>
      
            <div class="shoebox" data-animate>
      
              <div class="side top">
                <div class="lid"></div>
              </div>
              <div class="side front"></div>
              <div class="side back"></div>
              <div class="side left"></div>
              <div class="side right"></div>
              <div class="side bottom"></div>
      
              <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/t-1188/shoes1.png" alt="">
            </div>
            <header class="shoe-header">
              <small class="shoe-subheading" data-animate>Men's Shoe</small>
              <h2 class="shoe-heading" data-animate>Converse High Top</h2>
            </header>
            <div class="shoe-price">
              <span data-animate>$190</span>
            </div>
            <div class="shoe-rating">
              <span data-animate>4.6</span>
            </div>
          </div>
      
          <div class="shoe">
            <div class="shoebox" data-animate>
      
              <div class="side top">
                <div class="lid"></div>
              </div>
              <div class="side front"></div>
              <div class="side back"></div>
              <div class="side left"></div>
              <div class="side right"></div>
              <div class="side bottom"></div>
      
              <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/t-1188/shoes2.png" alt="">
            </div>
            <header class="shoe-header">
              <small class="shoe-subheading" data-animate>Men's Shoe</small>
              <h2 class="shoe-heading" data-animate>Nike Air Force 270</h2>
            </header>
            <div class="shoe-price">
              <span data-animate>$140</span>
            </div>
            <div class="shoe-rating">
              <span data-animate>3.9</span>
            </div>
          </div>
      
          <div class="shoe">
            <div class="shoebox" data-animate>
      
              <div class="side top">
                <div class="lid"></div>
              </div>
              <div class="side front"></div>
              <div class="side back"></div>
              <div class="side left"></div>
              <div class="side right"></div>
              <div class="side bottom"></div>
      
              <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/t-1188/shoes3.png" alt="">
            </div>
            <header class="shoe-header">
              <small class="shoe-subheading" data-animate>Ladies' Shoe</small>
              <h2 class="shoe-heading" data-animate>New Balance 996</h2>
            </header>
            <div class="shoe-price">
              <span data-animate>$180</span>
            </div>
            <div class="shoe-rating">
              <span data-animate>4.4</span>
            </div>
          </div>
      
          <div class="shoe">
            <div class="shoebox" data-animate>
      
              <div class="side top">
                <div class="lid"></div>
              </div>
              <div class="side front"></div>
              <div class="side back"></div>
              <div class="side left"></div>
              <div class="side right"></div>
              <div class="side bottom"></div>
      
              <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/t-1188/shoes4.png" alt="">
            </div>
            <header class="shoe-header">
              <small class="shoe-subheading" data-animate>Ladies' Shoe</small>
              <h2 class="shoe-heading" data-animate>Converse Comme Des Garcons</h2>
            </header>
            <div class="shoe-price">
              <span data-animate>$150</span>
            </div>
            <div class="shoe-rating">
              <span data-animate>4.3</span>
            </div>
          </div>
          <div class="shoe">
            <div class="shoebox" data-animate>
      
              <div class="side top">
                <div class="lid"></div>
              </div>
              <div class="side front"></div>
              <div class="side back"></div>
              <div class="side left"></div>
              <div class="side right"></div>
              <div class="side bottom"></div>
      
              <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/t-1188/shoes5.png" alt="">
            </div>
            <header class="shoe-header">
              <small class="shoe-subheading" data-animate>Men's Shoe</small>
              <h2 class="shoe-heading" data-animate>Converse High Top</h2>
            </header>
            <div class="shoe-price">
              <span data-animate>$140</span>
            </div>
            <div class="shoe-rating">
              <span data-animate>4.8</span>
            </div>
          </div>
        </div>
      </div>
      
      
      <script src="https://codepen.io/shshaw/pen/QmZYMG.js"></script>
      <script src="./script.js"></script>
</body>









@import url("https://fonts.googleapis.com/css?family=Roboto+Condensed:400,700&display=swap");
:root {
  --duration: 0.6s;
  --ease: cubic-bezier(0.5, 0, 0.5, 1);
  --fast-ease-out: cubic-bezier(0.4, 0, 0.9, 0.1);
  --fast-ease-in: cubic-bezier(0.1, 0.9, 0.3, 1);
  --fade-ease: cubic-bezier(0.7, 0, 0.1, 1);
  --tan-dark: #af957d;
  --tan: #e9cfb9;
  --orange: #fc7b1c;
  --orange-dark: #de762a;
  font-family: "Roboto Condensed", sans-serif;
}

*,
*:before,
*:after {
  position: relative;
  box-sizing: border-box;
}

img {
  display: block;
  max-width: 100%;
}

html,
body {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #e4c7b3;
}

#app {
  background: white;
  height: 90vmin;
  width: 50vmin;
  background: #eaeaec;
  border-radius: 8vmin;
  border: 2vmin solid white;
}

.shoe-selector {
  display: grid;
  grid-template: 1/1;
  justify-content: center;
  align-items: center;
  height: 90%;
}
.shoe-selector:before {
  content: "";
  height: 10vmin;
  width: 10vmin;
  position: absolute;
  background-color: #3e474e;
  border-radius: 50%;
  bottom: -5vmin;
  left: calc(50% - 5vmin);
  z-index: 10;
}

/* ---------------------------------- */
.shoe {
  height: 100%;
  grid-area: 1/1;
  display: grid;
  grid-template-columns: 50% 50%;
  grid-template-rows: 50% auto 1fr auto;
  padding: 1rem;
}
.shoe:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: none;
  background-image: linear-gradient(to bottom, transparent, transparent 40%, white);
  border-radius: 1rem;
}
.shoe > .shoebox {
  grid-column: 1/-1;
}
.shoe > .shoe-header {
  grid-column: 1/-1;
}
.shoe > .shoe-price {
  grid-column: 1/-1;
}
.shoe > .shoe-rating {
  grid-column: 1/2;
}

.shoe-header {
  text-align: center;
}

.shoe-subheading {
  display: inline-block;
  text-transform: uppercase;
  color: #777;
  margin-bottom: 0.5rem;
}

.shoe-heading {
  margin: 0;
  font-weight: 300;
  font-size: 1.25rem;
}

.shoe-price {
  display: inline-block;
  text-align: center;
  font-size: 3rem;
  font-weight: bold;
  display: flex;
  justify-content: center;
  align-items: center;
}
.shoe-price > span {
  display: inline-block;
}

.shoe-rating {
  height: 3rem;
  width: 3rem;
  box-shadow: 0 0.25rem 0.5rem rgba(0, 0, 0, 0.1);
  border-radius: 3rem;
  display: flex;
  justify-content: center;
  align-items: center;
  border: 1px solid #eee;
  overflow: hidden;
}
.shoe-rating > span {
  text-align: center;
  display: inline-block;
  width: 100%;
}

/* ---------------------------------- */
.shoe-selector {
  perspective: 80vmin;
}

.shoe {
  transform-style: preserve-3d;
}

.shoebox {
  --width: 23vmin;
  --height: 18vmin;
  --depth: 10vmin;
  transform-style: preserve-3d;
  width: var(--width);
  height: var(--height);
  margin: 13vmin auto;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 1vmin;
}

.side {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100%;
  height: 100%;
  width: var(--width);
  height: var(--height);
  box-sizing: border-box;
  background: var(--debug);
  border: solid 2px var(--color-dark);
  background: var(--color);
  background: linear-gradient(to bottom, var(--color-dark), var(--color));
  transform-style: preserve-3d;
  transform: translate(-50%, -50%) var(--rotation) translateZ(calc(var(--z) / 2));
}
.side.right:before, .side.left:before, .side.back:before,
.side .lid:before {
  --color: var(--tan);
  --color-dark: var(--tan-dark);
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  transform: translateZ(-2px);
  border: solid 2px var(--color-dark);
  background-image: linear-gradient(to right, var(--color-dark), var(--color));
}
.side.right:before {
  background-image: linear-gradient(to left, var(--color-dark), var(--color));
}
.side.back:before {
  background-image: linear-gradient(to bottom, var(--color-dark), var(--color));
}
.side.bottom {
  background-image: radial-gradient(var(--color-dark) 30%, var(--color));
  box-shadow: 0 1rem 2rem rgba(0, 0, 0, 0.1), inset 0 0 2vmin var(--color-dark);
}
.side .lid:before {
  background-image: linear-gradient(to bottom, var(--color-dark), var(--color));
}

.top,
.bottom {
  --debug: red;
  --z: var(--depth);
}

.right,
.left {
  --debug: green;
  width: var(--depth);
  --z: var(--width);
}

.front,
.back {
  --debug: blue;
  width: var(--width);
  height: var(--depth);
  --z: var(--height);
}

.top {
  --rotation: rotateY(0deg);
}

.bottom {
  --rotation: rotateY(180deg);
}

.right {
  --rotation: rotateY(90deg);
}

.left {
  --rotation: rotateY(-90deg);
}

.back {
  --rotation: rotateX(90deg);
}

.front {
  --rotation: rotateX(-90deg);
}

.top,
.lid,
.right,
.left,
.front {
  --color: var(--orange);
  --color-dark: var(--orange-dark);
}

.bottom,
.back {
  --color: var(--tan);
  --color-dark: var(--tan-dark);
}

/* ---------------------------------- */
.shoebox .top {
  background: none;
}
.shoebox .lid {
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  visibility: visible;
  background: linear-gradient(to top, var(--color-dark), var(--color) 50%);
  width: 100%;
  height: 100%;
  transition: transform var(--duration) var(--ease);
  transform-style: preserve-3d;
  transform-origin: top center;
}

[data-active] .shoebox .lid {
  transform: rotateX(90deg);
}

/* ---------------------------------- */
.shoe {
  width: 40vmin;
  pointer-events: none;
}
.shoe:not([data-active]) * {
  visibility: hidden;
}
.shoe [data-animate],
.shoe [data-animate] * {
  visibility: visible !important;
}
.shoe [data-animate] {
  transform: translateX(-100%);
  opacity: 0;
  transition-property: transform, opacity;
  transition-duration: var(--duration);
  transition-timing-function: var(--fast-ease-out), var(--fade-ease);
}
.shoe .shoebox {
  cursor: pointer;
  pointer-events: auto;
  transform: rotateX(5deg) translateX(-120%);
  transition: transform var(--duration) var(--ease) !important;
  opacity: 1;
}
.shoe[data-active] {
  z-index: 4;
  /* All Shoes After [data-active] */
  /* Only immediately after [data-active] */
}
.shoe[data-active] > * {
  pointer-events: auto;
}
.shoe[data-active]:before {
  display: block;
}
.shoe[data-active] [data-animate] {
  transform: none;
  opacity: 1;
  transition-delay: calc(var(--duration) / 2);
  transition-duration: var(--duration);
  transition-timing-function: var(--fast-ease-in), var(--fade-ease);
}
.shoe[data-active] .shoebox {
  transform: rotateX(5deg);
}
.shoe[data-active] ~ .shoe [data-animate] {
  transform: translateX(100%);
}
.shoe[data-active] ~ .shoe .shoebox {
  transform: rotateX(5deg) translateX(120%);
}
.shoe[data-active] + .shoe {
  z-index: 3;
}









console.clear();

const elShoes = document.querySelectorAll(".shoe");

[...elShoes].forEach((shoe) => {
  shoe.addEventListener("click", () => {
    [...document.querySelectorAll(".shoe[data-active]")].forEach(
      (el) => delete el.dataset.active
    );

    shoe.dataset.active = true;
  });
});

