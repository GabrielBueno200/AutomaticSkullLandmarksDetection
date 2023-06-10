<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Tropa-do-TCC/user-interface">

  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Tropa-do-TCC/user-interface">
  
  <a href="https://github.com/Tropa-do-TCC/user-interface/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Tropa-do-TCC/user-interface">
  </a>
  
   <img alt="GitHub" src="https://img.shields.io/github/license/Tropa-do-TCC/user-interface">
</p>

<!-- PROJECT LOGO -->
![image](https://github.com/GabrielBueno200/AutomaticSkullLandmarksDetection/assets/56837996/b4202521-31b7-41e7-9e1b-43d065d39413)

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-yellow?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="Matlab" src="https://img.shields.io/badge/Matlab-darkrgreen?style=for-the-badge&logo=matlab&logoColor=white"/>
  <img alt="Tensorflow" src="https://img.shields.io/badge/Tensorflow-darkblue?style=for-the-badge&logo=tensorflow&logoColor=white"/>
</p>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#-about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#-how-to-run">How To Run</a>
    </li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## 💻 About The Project
The project is a Computer Science undergraduate thesis conducted at FEI University Center. This undergraduate thesis presents a new approach for automatically identifying cephalometric landmarks in segmented skull tomographic images using bio-inspired algorithms and Convolutional Neural Networks (CNN). The goal is to improve the accuracy and efficiency of this process, benefiting medical and dental professionals in their analysis of craniofacial structures.

### Methodology
The proposed methods consists of a workflow (Fig. 1) containing six steps for detecting fiducial points in CT images and
reconstructing a 3D model of the skull. The first step involves
acquiring CT images with fiducial points from a database.
Two processes are then followed: one for detecting fiducial
points and the other for reconstructing the 3D model. The
first process involves preprocessing fiducial points, reducing
their dimensionality, and training a CNN with the images. The
second process involves recognizing regions belonging to the
skull and using them to reconstruct the 3D model. Finally, the
fiducial points detected by the CNN are projected onto the 3D
skull model. 

![image](https://github.com/GabrielBueno200/AutomaticSkullLandmarksDetection/assets/56837996/e38a641d-f019-4f78-9409-87674d468530)


<!-- HOW TO RUN -->
## 🚀 How To Run

```bash

# Clone the repository
$ git clone https://github.com/GabrielBueno200/AutomaticSkullLandmarksDetection.git

# Access the project folder in your terminal / cmd
$ cd AutomaticSkullLandmarksDetection

# First you need to install the packages, just run the following commands:
$ pip3 install -r requirements.txt

# After that, download the dataset in "dataset" folder:

# Then, start the application
$ python3 main

```



## 🤖 Authors

[Antonio Gustavo](https://github.com/antuniooh)

[Henrique Vital](https://github.com/henriquevital00)

[Gabriel Bueno](https://github.com/GabrielBueno200)

[João Vitor Dias](https://github.com/JoaoDias-223)

[Weverson da Silva](https://github.com/WebisD)
