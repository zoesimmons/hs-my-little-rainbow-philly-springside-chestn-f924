# My Little Rainbow
In this tutorial we're going to make a rainbow with HTML `<div>` elements. A `div` tag operates similarly to `span` tag in that it acts as a box where we can group elements together and apply styling. And while we build a rainbow, we're going to learn about html elements, css styling, css selectors, how color works in css, and importing stylesheets.

**1** First you'll need to open `index.html` in both Nitrous and the browser. Click the `Open in Nitrous` button in Learn. Next, in terminal in Nitrous ente`python -m SimpleHTTPServer 3000`. 

Once you have the server running, select `preview` and then `port 3000`.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">

Notice it's completely empty in the browser. 
 
**2** Link `main.css` to `index.html` and refresh the browser. You should see a black rainbow by using the `link` tag. 

**3** Select each div individially by adding an id to each one. You'll want to use that id as your CSS selector

**4** Add CSS in `main.css` using hexadecimal colors to add the correct colors to the rainbow (Red: `#f00`; Orange: `#ffa500`; Yellow: `#ff0`; Green: `#00bc3f`; Blue: `#06f`; Indigo: `#8a2be2`; Violet: `#d300c9`). The property you'll want to use is `border-top-color` property. You can read more about hexademical colors [here](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Color).

