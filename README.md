# Traffic-sign-Recognition

Traffic Signs Recognition is a system designed to identify and classify traffic signs, such as speed limits, no entry, traffic signals, turn directions, children crossing, and more. This process is crucial for autonomous vehicles, allowing them to interpret and adhere to traffic rules effectively.

## About the Project

This project involves building a deep neural network model capable of classifying traffic signs present in images into their respective categories. With this model, we can accurately read and understand traffic signs, a vital feature for autonomous vehicles.

## Dataset

The project uses the [German Traffic Sign Recognition Benchmark (GTSRB)](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) dataset. However, you can adapt this project to recognize traffic signs from other countries using suitable datasets. The GTSRB dataset was chosen for this project due to its accessibility and comprehensiveness.

## Steps to Build the Project

1. **Download the Dataset**  
   Download the dataset from the link provided above and extract it into a folder.

2. **Fork the Repository**  
   Clone or fork this repository into the same folder.

3. **Run the Traffic Signs Classifier**  
   Locate the `traffic_signs.py` file and execute it on your machine.

4. **Use Pretrained Weights (Optional)**  
   To simplify your task, you can use the pretrained weights file provided in the repository.

## Traffic Signs Classifier GUI

This project includes a graphical user interface (GUI) built with Tkinter, a Python GUI toolkit. The GUI allows users to interact with the traffic signs classifier effortlessly. To run the GUI, execute the following command in your terminal:

```bash
python gui.py
