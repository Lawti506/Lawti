# **Laser Cutting**
## Introduction
Laser cutting is a precision manufacturing process that uses a focused laser beam to cut or engrave materials by melting, burning, or vaporizing targeted areas. It produces clean, accurate edges and is commonly used on metals, plastics, wood, and textiles.

### Importance:
* High precision and repeatability for complex shapes and tight tolerances
* Fast production speed, reducing lead times and increasing throughput
* Minimal material waste due to narrow kerf and accurate nesting
* Clean edges and reduced need for secondary finishing
* Versatile across many materials (metals, plastics, wood, textiles) and thicknesses
* Easy automation and integration with CAD workflows for consistent results
# Software used: Inkscape
# Introduction
Inkscape is a free, open-source vector graphics editor that creates and edits scalable illustrations, logos, and diagrams using SVG as its native format. It offers intuitive tools like Bézier drawing, layers, and object grouping, plus a customizable workspace and helpful tutorials that make it user-friendly for beginners and professionals alike.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1GDzRd1I56mneTtp6oEjMSqEOxcFycpLS&sz=w400" alt="Profile Photo">>*source:google*

## Steps included to do Laser Cutting:
1) First, you need to get a picture from any software (e.g., Pinterest).
 - for example, this is the first picture I got from pinterest to laser cut. <img class="profile-photo" src="https://drive.google.com/thumbnail?id=1BS1DfT-WwhxceTcwx_rRktB-eUnz0cWy&sz=w400" alt="Profile Photo"> 
>>* the picture should be in black and white.

2) Convert the Image to Vectors
* Trace Bitmap: Go to Path > Trace Bitmap. Adjust the "Threshold" until your image looks crisp in the preview, then click Apply. This creates a vector version of your Pinterest find.
* Delete the Original: Move the new vector to the side and delete the original blurry Pinterest photo.
* Simplify: If the image is too complex, use Path > Simplify ($Ctrl+L$) to reduce the number of nodes, which makes the laser run smoother.

3)Set Strokes for Cutting vs. Engraving

* For Cutting: Select your path and open the Fill and Stroke menu ($Ctrl+Shift+F$). Set the "Fill" to None and the "Stroke paint" to Red.
* Hairline Thickness: In the "Stroke style" tab, set the width to 0.025 mm or 0.001 in. Most laser software recognizes this "hairline" thickness as a command to cut all the way through.
* For Engraving: Set the "Fill" to Black and "Stroke paint" to None. The laser will treat solid black areas as a "raster" or etch.


