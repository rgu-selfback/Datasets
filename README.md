# Datasets

The "raw" folder contians raw 3-axis accelerometer data recorded using the Axivity Ax3 sensor on both the wrist and the thigh. 
The folder 3 subfolders named wrist50, wrist34 and thigh34, each indicating the location of the sensor (i.e. wrist or thigh) and 
the number of people (i.e 34 or 50). Each dataset subfolder contains 6 subfolders for the different activity types, i.e. walking, 
jogging, standing, sitting, upstairs and downstairs. Each activity subfolder contains (34 or 50) .csv files containing the raw accelerometer data. Each .csv file has the following columns:
        # time: the date and time the data was recorded
        # x: x-axis accelerometer values
        # y: y-axis accelerometer values
        # z: z-axis accelerometer values
        
#References
For use of the wrist34 and thigh34 datasets, please cite the cfollowing paper:
Learning Deep and Shallow Features for Human Activity Recognition
Sani, S., Massie, S., Wiratunga, N. and Cooper, K.
International Conference on Knowledge Science, Engineering and Management – KSEM 2017

For use of the wrist50 dataset, please cite the following paper:
knn Sampling for Personalised Human Activity Recognition
Sani, S., Wiratunga, N., Massie, S. and Cooper, K.
International Conference on Case-Based Reasoning – ICCBR 2017
