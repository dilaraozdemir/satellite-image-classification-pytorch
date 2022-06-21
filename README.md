# Image Classification with Python on Satellite Image Classification Dataset-RSI-CB256

**NOTE** 📝 This dataset is taken from [kaggle](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification?resource=download).


## Dataset Explanation

❗ In this dataset; 

There are 4 classes: "cloud", "desert", "green_area" and "water". While obtaining the data, the Google map snapshots were mixed with the data received from the sensors.

### Visualization samples of dataset

🔸 Cloud

<kbd><img src="/images/cloudy/train_12.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/cloudy/train_26.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/cloudy/train_352.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd>


🔸 Desert

<kbd><img src="/images/desert/desert(1).jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/desert/desert(2).jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/desert/desert(4).jpg" alt="train_352" style="height: 100px; width:100px;"/>
</kbd>

🔸 Green Area

<kbd><img src="/images/green_area/Forest_2.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/green_area/Forest_4.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/green_area/Forest_55.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd>

🔸 Water

<kbd><img src="/images/water/SeaLake_1.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/water/SeaLake_2.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd><kbd><img src="/images/water/SeaLake_37.jpg" alt="train_352" style="height: 100px; width:100px;"/></kbd>


 ## Usage
 
 ### Creating Anaconda Environment

    conda create -n torchgpu python=3.6 
    conda activate torchgpu 

## Pytorch Installation


You can install pytorch by running the following commands:
 
    conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch


❗ In order for the command to work, NVIDIA's distributions for cuda packages must be installed on your computer.
