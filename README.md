
# Improved Contrast Zero-DCE

- This is the Zero Deep curve estimation method with contrast enhancement and Noise Reduction for enchancing Low Light Images.

- This Project is for non-commercial use only.

- This Project Code is ran on Kaggle GPU 'NVIDIA TESLA P100 GPU'.


## Acknowledgements

 - [Original Zero-DCE Paper by Li-Chongyi](https://github.com/Li-Chongyi/Zero-DCE)



## My Additions to the Original Code
- Implemented CLAHE algorithm while training the model.
- Implemented Simplest Colour Balance and Noise Reduction to the results of the model

## Requirements

- Python 3.9.7
- PyTorch 1.10.1
- Open CV 4.5.4.60
- torchvision 0.11.2
- Nvidia GPU (I used Kaggle GPU)
- Training Data is taken from the original paper. 432 Images are used for training the model.
- You may use more from this [link](https://drive.google.com/file/d/1GAB3uGsmAyLgtDBDONbil08vVu5wJcG3/view)(this containes 2002 training samples).

## Authors

- [@Soumyadeep17](https://github.com/soumyadeep17/)

## Results

![This is an image](https://github.com/soumyadeep17/Improved_Contrast_Zero-DCE/blob/main/Results/image1.png)
![This is an image](https://github.com/soumyadeep17/Improved_Contrast_Zero-DCE/blob/main/Results/image10.png)
![This is an image](https://github.com/soumyadeep17/Improved_Contrast_Zero-DCE/blob/main/Results/image3.png)
![This is an image](https://github.com/soumyadeep17/Improved_Contrast_Zero-DCE/blob/main/Results/image6.png)

## Documentation

[My Paper for this Code](https://github.com/soumyadeep17/Improved_Contrast_Zero-DCE/blob/main/IPCV_report_final.pdf)


## FAQ

#### 1. Why can't I open the 'Improved_Contrast_Zero_DCE_with_Results.ipynb' file?

The size of the notebook has increased due to inclusion of results. Therefore to view this file you need to download it first to your system.

#### 2. How much time did it take to train the model.

The training took approximately 1.5 hrs on kaggle GPU using 432 images.



## Feedback

If you have any feedback, please reach out to me at soumyadeep171198@gmail.com.

If you like it Leave a Star.😊

Thank You for Visiting. 😀

## License

[MIT](https://choosealicense.com/licenses/mit/)
