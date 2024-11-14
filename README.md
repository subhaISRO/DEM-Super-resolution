# DEM-Super-resolution
Our guided DEM SR dataset is is available at: https://drive.google.com/file/d/1wo5b6zJaTiwEGdp9ER6x62FveNgOuGB4/view?usp=share_link

Note: This is a subset of original dataset. Full dataset is coming soon.

About Dataset:
  1. All files are numpy files (.npy).
  2. There are 3 sub-directories
       a. 'final_sr_dataset/band/' contains High-resolution guide images.
       b. 'final_sr_dataset/cdem/' contains High-resolution DEM data.
       c. 'final_sr_dataset/cdem/' contains Low-resolution (LR) DEM data.
  3. All images are resized to 128x128 patches. LR DEMs are already 3x bicubic interpolated.
  4. DEM data ranges from -300m to 6000m.
  5. Guide images ranges from 0 to 2047.
