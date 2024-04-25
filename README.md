# Pilot-Models-for-Physics-Informed-Neural-Networks
In this we will have the codes/notes related to my research on modeling pilot control using physics informed neural networks

## 1) Overview:
1. Notes 1,2,3 are all similar in how the code is constructed. Only difference is the loss function being tweeked to see results. These codes are PINNs for a specific set of conditions.
2. Notes 4 is an extension of the PINN/iPINN for a larger dataset to try and increase its generalizability/robustness.
3. This work was for a class project thus it is slightly modified/simplified version of the thesis work but none the less if you read the report you can get the idea of how we are solving the problem.

## 2) The notes (The notes are listed in chonological order i.e. Notes 1 is the earliest version)
1. Notes 1: [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/Google%20Colab%20Code%201%20Notes.pdf)
   1. This is the architecture/code used for the AIAA paper
   2. Code: [click here](https://gist.github.com/stephenbrutch/16b24ac7bab9f077af155bdd9098dffe)
   3. Generated Data for this code [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/data%20for%20notes%201.zip)

2. Notes 2: [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/Google%20Colab%20Code%201.1%20Notes.pdf)
   1. Code: [click here](https://gist.github.com/stephenbrutch/516a3ff5da41341a28b172b0ad896c9b)
   2. Generated Data for this code [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/data%20for%20notes%201.zip)

3. Notes 3: [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/Google%20Colab%20Code%201.2%20Notes.pdf)
   1. Code: [click here](https://gist.github.com/stephenbrutch/ac56c78649bf8e3f3c4f1716b2867203)
   2. Generated Data for this code [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/data%20for%20notes%201.zip)      

4. Notes 4: This note is split into multiple chapters where each chapter goes over a different version of the model: [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/Google%20Colab%20Code%204%20Notes.pdf)
   1. Code for chapter 1: [click here](https://gist.github.com/stephenbrutch/e2b036c1a5c22db6aa0cf02943a66118). This code isnt perfectly updated but try to follow up until after the training loop portion then after that it is just standard predictions and plot predictions code
   2. Code for chapter 2: see ADCL colab under Steve folder
   3. In this code we look at purely the time invariant case
      1. Code for chapter 3: [click here](https://drive.google.com/file/d/1IZ3EtH4-3xSBb1Av3kmBOeRUuxKamZu2/view?usp=sharing)
   4. In this code we look to adjust the time invariant model to be ammendable to time invariant data. This model can work with both setups
      1. Code for chapter 4: [click here](https://colab.research.google.com/drive/1v-XAwR3TNVdPkI9JuH1LDjcz-cOctHno?usp=sharing)
     

## 3) Extra 
1. In this work I adapted the project to also use Sci-Kit Learn models to estimate the pilot behavior and pilot model parameters, there is also a comparison with NN and PINNs. This work was for a class project thus it is slightly modified/simplified version of the thesis work.

   1. Code: [click here](https://gist.github.com/stephenbrutch/f1b9d61fc1fbc12ec26d8ac260e6ff09)
   2. Report: [click here](https://github.com/stephenbrutch/Pilot-Models-for-Physics-Informed-Neural-Networks/blob/main/CS595_Final_Project_Report%20(3).pdf)
   3. Data and source code with readme file (ignore the report pdf in this folder): [click here](https://myerauedu-my.sharepoint.com/:f:/g/personal/brutchs_my_erau_edu/EgbDJa5-3T9JiKmKNWhLXvMB73Z8Bnu6-VyBRzkyb4YKnA?e=3xze4b)
