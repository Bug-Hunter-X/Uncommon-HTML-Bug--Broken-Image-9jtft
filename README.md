# Uncommon HTML Bug: Broken Image

This repository demonstrates a common yet easily overlooked HTML bug involving an image with an invalid source path.

## Bug Description

The bug lies in the use of an image element with an `src` attribute pointing to a non-existent image file, leading to a broken image.  This is a classic issue that's often overlooked when working with images.  The bug is subtle, in that the page structure and other elements will still render. The specific issue is in the `src` attribute of the image tag.  There's no error message reported, just a broken image icon.

## Bug Solution

The solution is to use a valid image source.  If using a relative path ensure that the image file exists in the same directory or a correctly specified relative path.  If using an absolute path, ensure the path is valid and the image is accessible.

## How to reproduce

1. Clone the repository.
2. Open `bug.html` in a web browser.
3. Observe the broken image icon where the image should be.
4. Open `bugSolution.html` to see the corrected code.
