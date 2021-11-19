## Tricks for handling biomedical imaging data

### Tools
* [ImageJ](https://imagej.nih.gov/ij/) - a simple image processing tool
* [MeVisLab](https://www.mevislab.de/download) - a visual programming interface for medical data

### Convert image stack into Raw/TIFF volume (ImageJ)
* load image stack Import > ImageSequence by pointing to the folder that contains your images
* save volume as TIFF or .raw image
### Extracting a mesh from a segmentation stack (MeVisLab)
1. use [this](https://github.com/jakobtroidl/connectomics-hacks/blob/main/seg-stack-to-mesh.mlab) MeVisLab network
2. load your volume as a TIFF file into the `image load` module
3. set the segmentation id you want to extract as a mesh in the `threshold` module
