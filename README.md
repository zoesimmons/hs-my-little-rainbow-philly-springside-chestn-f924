# My Little Rainbow

<img src="https://s3.amazonaws.com/after-school-assets/rainbow.gif" width="300" align="right" hspace="10">

In this tutorial we're going to make a rainbow with HTML `<div>` elements. A `div` tag operates similarly to `span` tag in that it acts as a box where we can group elements together and apply styling. And while we build a rainbow, we're going to learn about HTML elements, CSS styling, CSS selectors, how color works in CSS, and practice importing style sheets.

**1** First you'll need to open `index.html` in both Nitrous and the browser. Click the `Open` button in Learn. Next, in terminal in Nitrous enter: `python -m SimpleHTTPServer 3000`. 

Once you have the server running, select `preview` and then `port 3000`.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">

Notice it's completely empty in the browser. 
 
**2** Link `main.css` to `index.html` and refresh the browser. You should see a black rainbow by using the `link` tag. Look back at previous lessons in Learn if you need help linking a CSS file to your HTML.

**3** Take a look at `index.html`, and remember that is the code we'll be applying styling to. You'll notice there isn't any text on the page, just a bunch of `div`s. Rainbows don't have text in them, so we're just styling space on the page.

You'll select each div individually by adding an ID to each one. You'll want to use that ID as your CSS selector. You can theoretically name your ID anything you want, as long as you use that ID in your CSS. However, suddenly your code only makes sense to you at this current moment. It wouldn't make sense to another developer who looked at your code, and it might not make sense to you in six months. We like to make our IDs and classes as descriptive as possible. A good one for the outer-most `div` would be `red`, because the outer-most part of a rainbow is red. Make sure to save your changes to `index.html` when you're done!

If you forgot how to define an ID, take a look at past lessons for a refresher!

**4** Add CSS in `main.css` using hexadecimal colors to add the correct colors to the rainbow (Red: `#f00`; Orange: `#ffa500`; Yellow: `#ff0`; Green: `#00bc3f`; Blue: `#06f`; Indigo: `#8a2be2`; Violet: `#d300c9`).

The property (like `font-size` or `color`) you'll want to use is `border-top-color`. 

For an example, your CSS will look something like this:

```css
#red {
  border-top-color: #f00;
}
```

Make sure to save your changes before you refresh in the browser. The browser won't know you made any changes to your files if you don't save.

Remember to shut down your server before you move on to other labs and lessons. You won't be able to start a server in those other exercises if this one is still running!

Once you're finished, you can push your code to GitHub (and mark this lab as complete in Learn) by entering in terminal in Nitrous `learn submit`.


You can read more about hexademical colors [here](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Color).



<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-my-little-rainbow' title='My Little Rainbow'>My Little Rainbow</a> on Learn.co and start learning to code for free.</p>
