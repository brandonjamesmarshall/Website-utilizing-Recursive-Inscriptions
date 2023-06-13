# Website utilizing recursive inscriptions
Provided here is a template that you can use to inscribe your own single-page HTML website.

This can be used as a landing page, digital business card, quick bio, whatever!

## Quick instructions:
1. Inscribe a photo of yourself (or find a photo you want to use) and make note of its Inscription ID
2. Edit template.html and modify with your own information.
3. Use a minify servie such as https://www.willpeavy.com/tools/minifier/ to remove all the comments and extra white space. This will result in the smallest file size possible!
3. Inscribe template.html using an inscription service such as https://ordinalsbot.com/


## Some additional notes for how I made this:
### > original-files/brandonmarshall-max.html was used for internal testing to build out the site

Once I verified everything was working on that level, I inscribed all the assets (WEBP and SVGs) and took note of each of their Inscription IDs.

From there, I created a new doc and replaced the static files with using /source/INSCRIPTIONID

I also minified the HTML file, which isn't required but removed unnecessary blank space to cut down on the file size and make it even cheaper to inscribe.

### > The actual HTML file I originally inscribed is in original-files/brandonmarshal.html

