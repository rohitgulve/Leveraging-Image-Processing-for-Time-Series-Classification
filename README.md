# Stock Prediction using Image Processing on Time Series Data

## Introduction

This project explores the innovative intersection of image processing and machine learning to predict stock market states. By transforming financial time series data into denoised grayscale wavelet spectrum images, we aim to overcome the challenges posed by the volatile nature of stock prices. This approach allows us to capture the essence of market trends and fluctuations more effectively than traditional predictive models.

## Methodology

The core of our methodology involves:
1. **Wavelet Transform**: Transforming financial time series data using continuous wavelet transforms to denoise and convert them into grayscale wavelet spectrum images.
2. **Convolutional Neural Networks (CNNs)**: Utilizing shallow and deep CNN models to detect and learn hidden patterns within the transformed data.
3. **Data Preprocessing**: Focusing on adjusted closing prices and trading volumes with a 60-day sliding window for analysis and a 5-day window for labeling stock movements.

## Results

Our study presented findings based on denoised and raw data:
- Models trained on denoised data exhibited nuanced differences in performance when incorporating trading volume as an additional feature.
- Surprisingly, the models trained on raw data outperformed those trained on denoised data across various metrics, suggesting the denoising process might remove valuable information alongside noise.

## Discussion

The project suggests refining the CNN architecture and incorporating more diverse datasets could enhance the model's predictive accuracy. Furthermore, we propose deploying the model in a real-world environment for live testing against actual market changes.

## Setup and Running the Code

To run this project on your local machine, follow these steps:

1. **Clone the Repository**
   ```
   git clone https://github.com/rohitgulve/Stock-Prediction-using-Image-Processing-on-Time-Series-Data.git
   ```
3. **Run the Prediction Model**
   ```
   nodenoised-analysis-cnn.ipynb

Please ensure you have Python and the necessary libraries installed. For more details on the setup and the methodology, refer to the project's documentation.

## Contribution

Contributions to this project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
