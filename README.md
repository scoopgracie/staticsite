# staticsite
Static Website file layout template

Pages are organized as page directories, with the exception of the home page.
The home page is placed in the root directory and is called `index.html`.

Non-page assets go somewhere in `/assets/`.

## Page directories
Each page directory should contain exactly one HTML file, `index.html`, and
zero or more other page directories.

## `/assets/`
* Scripts go in `/assets/scripts/`.
* Styles go in `/assets/scripts/`.
* Images go in `/assets/media/images/`.
* Videos go in `/assets/media/video/`.
* Audio files go in `/assets/media/audio/`.
* Miscellaneous media (i.e. any obscure media type I forgot about) goes in `/assets/media/`.
* Any miscellaneous files that aren't pages go in `/assets/`.
* In any of the above directories, you may create your own subdirectory hierarchies.

## Note
Remember to delete `LICENSE` and `README.md` before deploying!
