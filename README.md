# Self Driving Simulator 

### Self driving simulator which uses the [Udacity Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim). and utilizes Nvidia's [End-to-End Deep Learning Using NVIDIA PX](https://images.nvidia.com/content/tegra/automotive/images/2016/solutions/pdf/end-to-end-dl-using-px.pdf) Behavioural Cloning technique. 

## Requirements:
A virtual environment is highly reccomended.

The current Environment file is conda 3.10 on Windows 11

```conda env create -f environment.yml ```

## Data Collection
Image data is gathered from the [Udacity Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim).

## Training the Model

Make sure the Virtual Environment is enabled 

[Training Demo](https://drive.google.com/file/d/1Vvy0jGtMlDVa9sWj9DWL2KaaHeNNllWO/view?usp=drive_link)


Once data is gathered, training can be done through ```train.ipynb``` which show cases each step of the data pipeline and data process.

## Validating the Model.

```python drive.py ```

