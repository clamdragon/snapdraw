# snapdraw
Take screen shots of click-n-drag areas.
Annotate those screen grabs and get them back as pillow images.
Fits into your python application.

SnapDraw is a simple tool much like the Snipping Tool in windows, only multiplatform, a bit simpler, and easily integratable into other python apps.
Use it like so:

-ScreenshotOverlay is for getting a PIL screen grab image from drag area.

-AnnotationWindow is for editing any PIL image, and gives control back to calling frame when finished or cancelled. AnnotationWindow.final_img is result.

Or call main() to run normal configuration and get PIL image result. 

Developed on Python 2.7. Requires pillow & PySide
