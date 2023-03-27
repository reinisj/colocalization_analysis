# Colocalization analysis
Code for article submission.

  
1. **Preprocessing**
    - load CZI files
    - maximum intensity Z projection
    - segmentation of all nuclei with Cellpose using DAPI channel
    - remove mitotic nuclei based on previously generated segmentation masks
    - export as PNG
2. **CellProfiler**
    - extraction of intensity correlation measurements between pairs of channels separately for mitotic and non-mitotic cells
