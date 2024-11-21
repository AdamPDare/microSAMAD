**Anglia Ruskin University Micro-SAM Research Project** <br>

Uploaded to this Github Repository is the code used to segment and annotate nuclei and cell membranes of Fruit Flies & Zebra fish. <br>
(The TIFF Files cannot be uploaded due to size) <br>

Utilises Segment Anything for Microscopy, built upon Meta's Segment Anything Model: <br><br>

**Micro-SAM Preprint** <br>
https://www.biorxiv.org/content/10.1101/2023.08.21.554208v1     <br><br>

**Segment Anything Publication:** <br>
https://arxiv.org/abs/2304.02643    	arXiv:2304.02643   <br><br>

**Auto Segmentation (Micro-SAM) code is from:** <br>
  https://github.com/computational-cell-analytics/micro-sam <br>
  
**Micro-SAM Documentation:** <br>
  https://computational-cell-analytics.github.io/micro-sam/micro_sam.html <br><br>



  **Work Completed:** <br>
  -	Set up Miniforge/ Anaconda Environment to utilise a GPU for the SAM process <br>
  -	Learn how to use Napari to create ground truths (using the gui to annotate) <br>
    - Refer to this: https://www.youtube.com/playlist?list=PLwYZXQJ3f36GQPpKCrSbHjGiH39X4XjSO <br>
  -	Use Fijji to split the colour channels to run Micro-SAM’s Auto Segmentation <br>
  -	Utilise Micro-SAM’s auto segmentation for 2D and 3D images <br>
  - Display the results using Matplotlib <br>
  -	Export these results to a TIFF File <br>
    - To display these results use Fijji & adjust the colours <br>
  - Look into fine tuning a model using ground truths (would need to create these using Napari) <br>
      - Refer to this: https://github.com/computational-cell-analytics/micro-sam/blob/master/notebooks/sam_finetuning.ipynb <br>
  - Calculate the centroids of the labels/ annotations from the Micro-SAM Model. <br><br>


  **Improvements that could be made:** <br>
  - Centroid Labels need to be exported to a TIFF File <br>
  - Centroids need to be unique to the slide, not just all of them <br>
  - Add an option to name the output files for the Annotations <br>
  - Output files take the filename of the input file automatically<br>
  
  

