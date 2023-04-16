<h1>STIALA WEB SITE</h1>
voila la V4 du site
<br>
<br>
<a href="http://stiala.xyz" target="_blank" rel="noreferrer noopener">voir le site</a>
<style>
  @import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@800&family=Roboto:wght@100;300&display=swap");
:root {
  --button: #b3b3b3;
  --button-color: #0a0a0a;
  --shadow: #000;
  --bg: #737373;
  --header: #7a7a7a;
  --color: #fafafa;
  --lit-header: #e6e6e6;
  --speed: 2s;
}
* {
  box-sizing: border-box;
  transform-style: preserve-3d;
}
@property --swing-x {
  initial-value: 0;
  inherits: false;
  syntax: '<integer>';
}
@property --swing-y {
  initial-value: 0;
  inherits: false;
  syntax: '<integer>';
}
body {
  min-height: 100vh;
  display: flex;
  font-family: 'Roboto', sans-serif;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: var(--bg);
  color: var(--color);
  perspective: 1200px;
}
a {
  text-transform: uppercase;
  text-decoration: none;
  background: var(--button);
  color: var(--button-color);
  padding: 1rem 4rem;
  border-radius: 4rem;
  font-size: 0.875rem;
  letter-spacing: 0.05rem;
}
p {
  font-weight: 100;
}
.
.info {
  text-align: center;
  line-height: 1.5;
  max-width: clamp(16rem, 90vmin, 25rem);
}
.info > p {
  margin-bottom: 3rem;
}
@-webkit-keyframes swing {
  0% {
    --swing-x: -100;
    --swing-y: -100;
  }
  50% {
    --swing-y: 0;
  }
  100% {
    --swing-y: -100;
    --swing-x: 100;
  }
}
@keyframes swing {
  0% {
    --swing-x: -100;
    --swing-y: -100;
  }
  50% {
    --swing-y: 0;
  }
  100% {
    --swing-y: -100;
    --swing-x: 100;
  }
}

</style>