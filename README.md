The project loads two images: one is the main image, and the other is the watermark image. It then places the watermark on the main image and saves the result as a new image. Additionally, it blends the watermark with the main image using a weighted sum and saves the blended image. Finally, it overlays the blended watermark on the main image and saves the watermarked image.

Install OpenCV:

``pip install opencv-python``

Place the main image and the watermark image in the project folder. Ensure the filenames match those specified in the script.

Run the script:

``python watermark.py``

The watermarked images will be saved in the project folder with filenames watermark_place.jpeg, blend.jpeg, and elfs-watermarked.jpeg.
