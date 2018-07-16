---
title: Picture Box
author: Anna Gubareva
---
# Picture Box

## <a name="overview"></a>Overview
The **Picture Box** control allows you to embed _static_ (stored along with the report) or _dynamic_ (obtained from a data source) images into a report.

To add this control to a report, drag the **Picture Box** item from the [Toolbox](../../report-designer-tools/toolbox.md) onto the report's area.

image

The Picture Box can display images of the following file formats: BMP, JPG, JPEG, GIF, TIF, TIFF, PNG, ICO, DIB, RLE, JPE, JFIF, EMF, WMF.


Use the **Image** or **Image URL** property to provide the image to display in the Picture Box. You can access these properties in the control's smart tag.

image

If you use the **Image** property, the specified image is always [saved](../../save-reports.md) along with the report. If you use the **Image URL** property, only the path to the image (not the image itself) is stored. 

## Bind a Picture Box to Data
You can use the Picture Box to display an image [dynamically obtained](../../bind-to-data/bind-controls-to-data-expression-bindings.md) from a data source. Click the control's smart tag, expand the the **Image** property's **Expression** drop-down list and select the required data field.

image

You can bind the **Image URL** property to data in the same way. 

Clicking the **Expression** option's ellipsis button invokes the **Expression Editor**, in which you can construct a complex binding expression involving two or more data fields.

You can also drag and drop a field that contains image data from the [Field List](../../report-designer-tools/ui-panels/field-list.md) to create a new Picture Box bound to this field.

image

See the [Bind Report Controls to Data](../../bind-to-data/bind-controls-to-data-expression-bindings.md) topic to learn more about how to create data-aware controls.


## Image Size Modes

Use the **Sizing** property to specify how to position an image within the Picture Box. This control supports the following image size modes:

* **Normal**
    
    The image is displayed with its original dimensions in the top left corner. The image is clipped if it does not fit the control's boundaries. 

* **Stretch Image**

    The image is stretched to fill both the control's width and height.

* **Auto Size**

    The control's dimensions are adjusted to the image size.

* **Zoom Image**

    The image is resized proportionally without clipping to fit the control dimensions in the best way.

* **Squeeze**

    The image is centered and shown full-size if the control dimensions exceed the image size. Otherwise, the image is resized to fit the control's boundaries.

* **Tile**

    The original image is replicated within the control starting from the top left corner. The replicated image is clipped if it does not fit the control's boundaries.