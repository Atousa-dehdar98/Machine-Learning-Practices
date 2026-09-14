# Image Segmentation with K-Means

This project uses K-Means clustering to segment an image into regions with similar RGB colour values.

## Workflow

- Load the source image with Pillow.
- Convert the image to a NumPy array and reshape pixels into RGB feature vectors.
- Cluster pixels with K-Means using five clusters.
- Replace each pixel with its cluster-centroid colour.
- Reconstruct and save the segmented image.

## Files

- `Image Segmentation with K-Means.ipynb` — complete segmentation workflow and report.
- `pic.jpg` — source image.
- `segmented_pic.jpg` — generated segmented image.
- `Description of Image Segmentation with K-Means practice.pdf` — task brief.

## Run

Install Jupyter, NumPy, scikit-learn, Matplotlib, and Pillow. Execute the notebook from top to bottom; adjust the number of clusters to compare segmentations.
