# Self Driving Simulator 

### Self driving simulator using [Udacity Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim) and Nvidia's [End-to-End Deep Learning Using NVIDIA PX](https://images.nvidia.com/content/tegra/automotive/images/2016/solutions/pdf/end-to-end-dl-using-px.pdf) Behavioural Cloning technique. 

## Requirements:
A virtual environment is highly reccomended.

The current Environment file is conda 3.10 on Windows 11.

```conda env create -f environment.yml ```

## Data Collection
Image data is gathered from the [Udacity Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim).



## Training the Model

Make sure the Virtual Environment is enabled.

https://github.com/user-attachments/assets/264a1a48-657a-4392-a806-e637fc0d9daa

I found the best results by going around the loop 3 times in one direction then 3 times in the other direction in order to avoid biasing but also just enough to avoid over fitting.


Once data is gathered, training can be done through ```train.ipynb``` which show cases each step of the data pipeline and data process.

## Validating the Model.

```python drive.py ```

https://github.com/user-attachments/assets/0cc06d7d-8f13-446a-ba75-ba7c6c7d6781

Note that the Validation track has never been trained on!

## Sources

1. Udacity. (n.d.). Self-driving car simulator. GitHub. Retrieved from https://github.com/udacity/self-driving-car-sim

2. NVIDIA. (2016). End to end deep learning for self-driving cars. Retrieved from https://images.nvidia.com/content/tegra/automotive/images/2016/solutions/pdf/end-to-end-dl-using-px.pdf

