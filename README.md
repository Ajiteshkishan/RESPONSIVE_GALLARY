Image Gallery
This project is a clean, modern, and responsive image gallery built using only HTML and CSS. The gallery displays a collection of images in an attractive card layout with grayscale effects and interactive hover transitions.

Features
Responsive layout for desktops and mobile devices

Flexible, modern CSS Flexbox gallery grid

Grayscale image effects that turn to color on hover

Smooth image scaling and drop-shadow on hover for visual feedback

Minimal, elegant design using pure HTML and CSS (no JavaScript)

Demo
Screenshot or GIF here (You can upload a screenshot of the gallery for best results).

How It Works
The gallery uses a simple structure of HTML and leverages CSS for all styling and interactivity.

HTML: The gallery.html file uses semantic elements for the gallery grid, with each image placed in a .card figure. Each card shows an image and a caption, organized inside a flexbox container for easy responsive layout.

CSS: The gallery.css file defines the grid system, card effects, hover transitions, responsive adjustments, and visual styles. Notably, the filter: grayscale property is applied to images and removed on hover, with scaling and drop-shadow for a dynamic feel.

file structure 
/
├── gallery.html      # Main HTML file for the gallery[file:11]
├── gallery.css       # Stylesheet for the gallery layout and effects[file:12]
├── image1.jpg        # Gallery images (image1...image9.jpg)
├── image2.jpg
├── image3.jpg
├── image4.jpg
├── image5.jpg
├── image6.jpg
├── image7.jpg
├── image8.jpg
├── image9.jpg
├── img.jpg           # Favicon for browser tab

How to Use or Run
Clone/download this repository to your local machine.

Make sure all image files (image1.jpg to image9.jpg, and img.jpg for favicon) are present in the same folder as gallery.html and gallery.css.

Open gallery.html in any web browser.

That's it! The gallery will render with all features enabled.

Customization
Add more images: Copy image files into the directory and add corresponding figure blocks to gallery.html.

Change styles: Edit gallery.css to update layout, colors, hover effects, and more.

Technologies Used
HTML5 - For semantic structure and accessibility

CSS3 - For layout, flexbox grid, transitions, and effects
