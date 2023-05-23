* {
  border: 0;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
:root {
 -moz-background-origin: white;
 -moz-background-origin: rgb(7, 7, 7);
 --primary: blue;
 --yellow: yellow;
 --yellow-t: black;
 --bezier: cubic-bezier(0.42,0,0.58,1);
 --trans-dur: 0.03%;
 font-size: calc(24px + 6 +(100vw - 320px));

}
body {
    background-color: #1b1c23;
    color: var(--fg);
    font: 1em/1.5;
    display:flex;
    height: 100vh;
    transition: background-color var(--trans-dur), color var(--trans-dur);
  }
  .rating_display {
    font-size: 1em;
    font-weight: 500;
    min-height: 1.25em;
    position: absolute;
    top: 100%;
    width: 100%;
    text-align: center;
  }
  .rating_stars {
    display: flex;
    padding-bottom: 0.375em;
    position: relative;
  }
  .rating_star {
    display: block;
    overflow: visible;
    pointer-events: none;
    width: 2em;
    height: 2em;
  }
