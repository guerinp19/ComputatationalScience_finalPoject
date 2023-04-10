To run the code involving sharpness function:
- need to install opencv first use: pip install opencv-python
- You have to build the function then call the function then if you want to call the function again, you have to rebuild it again otherwise it gives you a TypeError: 'numpy.float64' object is not callable. Rebuilding it will not give you the error once you call it again. Do this everytime you want to call the function
- Theres a line in the function that converts to greyscale that is currently commented because the picture was already grey and it gives an error trying to convert an already grey image to grey. Uncomment if using a picture thats not grey.
