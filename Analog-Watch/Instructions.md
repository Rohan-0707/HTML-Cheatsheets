# Usage
Open the **index.html** file in your preferred web browser.

Explore the analog clock with the default theme.

Change the clock theme by clicking on the provided buttons:

**"Theme 1" changes the background image to clock1.jpg.
"Theme 2" changes the background image to clock2.jpg.
"Theme 3" changes the background image to clock3.jpg.
"Theme 4" changes the background image to clock4.jpg.**

# Customize the themes:

To add your own background images, replace the **clock1.jpg, clock2.jpg, clock3.jpg, and clock4.jpg** files in the project folder.

# Customization

You can customize the background images and other styles in the index.html and styles sections of the style tag.

&#x3C;!-- Customize the background images in the analog-clock class --&#x3E;
.analog-clock {
    background-image: url(&#x22;clock3.jpg&#x22;);
}

&#x3C;!-- Customize the URLs in the theme function --&#x3E;
function theme(image) {
    var el = document.getElementById(&#x22;watch&#x22;).style;

    if (image == &#x27;temp1&#x27;) {
        el.backgroundImage = &#x22;url(&#x27;your-image1.jpg&#x27;)&#x22;;
    }

    if (image == &#x27;temp2&#x27;) {
        el.backgroundImage = &#x22;url(&#x27;your-image2.jpg&#x27;)&#x22;;
    }

    if (image == &#x27;temp3&#x27;) {
        el.backgroundImage = &#x22;url(&#x27;your-image3.jpg&#x27;)&#x22;;
    }

    if (image == &#x27;temp4&#x27;) {
        el.backgroundImage = &#x22;url(&#x27;your-image4.jpg&#x27;)&#x22;;
    }
}
