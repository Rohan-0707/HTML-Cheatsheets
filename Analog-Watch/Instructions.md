# Usage

1. Open the **index.html** file in your preferred web browser.

2. Explore the analog clock with the default theme.

3. Change the clock theme by clicking on the provided buttons:
   - "Theme 1" changes the background image to **clock1.jpg**.
   - "Theme 2" changes the background image to **clock2.jpg**.
   - "Theme 3" changes the background image to **clock3.jpg**.
   - "Theme 4" changes the background image to **clock4.jpg**.

# Customize the Themes:

To add your own background images, replace the **clock1.jpg, clock2.jpg, clock3.jpg, and clock4.jpg** files in the project folder.

# Customization

You can customize the background images and other styles in the `index.html` and `styles` sections of the `style` tag.

```html
<!-- Customize the background images in the analog-clock class -->
.analog-clock {
    background-image: url("clock3.jpg");
}

<!-- Customize the URLs in the theme function -->
function theme(image) {
    var el = document.getElementById("watch").style;

    if (image == 'temp1') {
        el.backgroundImage = "url('your-image1.jpg')";
    }

    if (image == 'temp2') {
        el.backgroundImage = "url('your-image2.jpg')";
    }

    if (image == 'temp3') {
        el.backgroundImage = "url('your-image3.jpg')";
    }

    if (image == 'temp4') {
        el.backgroundImage = "url('your-image4.jpg')";
    }
}
```
