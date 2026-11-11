# Robyn 3.12.2

* Fixed convergence plot export with many trials by removing the trial-based line style mapping that could cause an invalid `color` or `lty` error.
* Fixed cluster detail plot export exceeding the graphics device's pixel limit by sizing the image from the media rows shown and reducing resolution when needed.
