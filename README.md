# 🖼️ YOLO Object Detection Workspace
*Teaching computers to see, one image at a time! 🚀*

## 🤔 What is this?
This is a simple and fun project that uses a smart AI (YOLO) to find and identify objects in your pictures! It includes a handy script that automatically organizes your image datasets into training and testing folders, making it super easy to teach the AI new tricks or just see what it can recognize right out of the box.

## ✨ Features
- **Auto-Sorting:** Magically splits your images and labels into `train` and `val` folders so you don't have to do it manually.
- **Easy Training:** Ready-to-go setup for training the AI on your own custom dataset.
- **Instant Predictions:** Pick a random image and let the AI draw boxes around what it sees!
- **Visual Results:** Automatically saves and shows you the final image with all the detected objects highlighted.

## 🛠️ How to run it
1. Make sure you have Python installed on your computer.
2. Install the required libraries by opening your terminal or command prompt and running:
   ```bash
   pip install ultralytics pillow
   ```
3. Put your images and their matching text labels in a folder called `downloaded_images`.
4. Open the `main.ipynb` notebook in Jupyter Notebook or your favorite code editor (like VS Code).
5. Run the cells top-to-bottom to organize your dataset and start detecting!

## 🚀 Usage
Want to see it in action? Just run the prediction cells in the notebook! The code will randomly pick an image from your organized dataset, feed it to the AI, and display the result. 

```python
# The AI will look at a random image and show you what it found!
results = model.predict(source=random_image, show=True, save=True)
```

Your predicted images will be saved safely in the `runs/detect/` folder for you to look at later. Have fun detecting!
