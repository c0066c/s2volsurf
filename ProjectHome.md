S2VOLSURF contains utility source code and command-line programs for:

> creating compressed, 8-bit-per-pixel volumes ("xrw volumes") from NIFTI images and stacks of TGA images (nifti2xrw, tgastack2xrw);

> displaying basic information about xrw volumes including a histogram of voxel values (xrwinfo, xrwhisto);

> converting xrw volumes to mosaiced PNG files and to simple ASCII-format point sets (xrw2pngmos, xr2points);

> displaying one or more STL-format surface files (s2stl.c - source code must be modified to choose your own STL file/s);

> extracting an STL-format isosurface from an XRW-format volume (xrw2stl.c);

> displaying the coordinate range of one or more OBJ-format surfaces (objrange.c); and

> generating interactive 3-d renderings of xrw volumes, overlaid with OBJ-format surfaces, and creating PRC and PDF versions of the visualisation (xrw2pdf.c).