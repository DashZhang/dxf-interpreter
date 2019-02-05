# dxf-interpreter

a simple interpreter for those who don't have NI Motion Assistant to read .dxf CAD file in LabVIEW.

## Supported Geometry:

* Line
* Polyline
* Arc
* Circle
* Hatch

## Data Structure

2D geometry is stored as 1D array of clusters for each geometry instance. For detailed infomation of geometry parameters, see [DXF Reference - Autodesk](https://images.autodesk.com/adsk/files/autocad_2012_pdf_dxf-reference_enu.pdf)

* Array (1D array of)
  * Cluster (cluster of 2 elements)
    * String (geometry label)
    * Array (1D array of geometry parameters)
      * Numberic (double-precision floating-point number)

## Credit

Thanks to : Robin Alexander Nissen at CCM-EE (ran@ccm-ee.dk) for lying down some groundwork :D
