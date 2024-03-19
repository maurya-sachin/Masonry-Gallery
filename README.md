# Masonry Layout

This is a simple web page showcasing a Masonry Layout for a gallery using HTML, CSS, and JavaScript. The Masonry Layout is achieved using the Masonry library.

## Live Demo
- https://maurya-sachin.github.io/Masonry-Gallery/

## Instructions

1. Clone or download the repository.
2. Open `index.html` in a web browser.

## Dependencies

- [jQuery](https://jquery.com/): A fast, small, and feature-rich JavaScript library.
- [Bootstrap](https://getbootstrap.com/): A popular CSS framework for building responsive and mobile-first websites.
- [ImagesLoaded](https://imagesloaded.desandro.com/): JavaScript library for detecting when images have been loaded.
- [Masonry](https://masonry.desandro.com/): JavaScript library for creating dynamic grid layouts.

## Gallery

The gallery displays a set of images in a Masonry Layout. The layout adjusts dynamically to fit images of varying sizes.

## HTML Structure

- `container-fluid`: Bootstrap container for full-width layout.
- `row`: Bootstrap row to contain the gallery items.
- `h1`: Heading displaying the title "Gallery".
- `wrapper`: Container for the gallery items.
- `gallery-item`: Individual items within the gallery.

## CSS

- `gallery-item`: Defines the width and padding of gallery items.
- `gallery-item img`: Specifies the width of images within gallery items.

## JavaScript

- Initializes Masonry layout for images using jQuery and Masonry library.
- Lazy loads images by setting the `src` attribute once the page is loaded.
- Contains commented-out code for handling video elements in the gallery.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the [MIT License](LICENSE).
