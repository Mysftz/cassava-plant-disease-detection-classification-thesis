<a name="readme-top"></a>
<div align="center">

[![alt text](https://github.com/Mysftz/Mysftz/blob/main/assets/READMEHeader.jpeg?raw=true)](https://github.com/Mysftz)
# Cassava Plant Disease Detection Classification Thesis
[![GitHub][GitHub-shield]](https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis)
[![Contributors][contributors-shield]](https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis/graphs/contributors)
[![Forks][forks-shield]](https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis/network/members)
[![Stargazers][stars-shield]](https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis/stargazers)
[![Issues][issues-shield]](https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis/issues)
[![License][license-shield]](https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis/blob/main/LICENSE.txt)
</div>

<p align="center">
  <a href="#about-the-project">About The Project</a> •
  <a href="#built-with">Built With</a> •
  <a href="https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis/archive/refs/heads/main.zip">Download</a> • 
  <a href="#usage">Usage</a> •
  <a href="#license">License</a> •
  <a href="#other-projects">Other Projects</a> •
  <a href="#contact">Contact</a>
</p>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#introduction">Infomation</a></li>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#other-infomation">Other Infomation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#other-projects">Other Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
### Introduction

To further explore artificial intelligent systems within society, a cognitive neural network model that detect a disease in the cassava plant is taken and improved. Initial issues arise in the model’s runtime and GPU requirement allowing only a small number of epochs to happen, where theoretically, the more epoch the better the test accuracy. Outsourcing the GPU via a python web server on Google Collab and the runtime issue resolved , it was found that the system could have the potentially to improve the test accuracy up 67% given certain criteria met through training layer independently from each other. Through testing, it was proven that the more epoch ran, the better the test accuracy however the limit was beyond the GPU restrictions but could be seen in further development. The hindrances  did not allow for the projects goals to be completed however sufficient improvement was made unto the existing model and is set for further development.

Artificial intelligence is used in various industrial and research fields to assist humanity in data analysis, medical care and recovery and more. To further enhance and explore the implementation of artificial intelligent systems detecting a disease within the cassava plant. In the project a collection of image of the plants will vary from healthy, slightly infected, fully infected and dead, "This group will endeavour to improve an existing classifier on a current data set. This groups goals are to experiment with the PCA, Decision Trees, Random Forests and Neural Networks on a data set to classify images displaying different stages of the ‘Cassava’ disease on plants. The data set [1] selected consists of thousands of images, we initial view this as an opportunity to compare the run time and accuracy of the machine learning script on different number of images supplied to the script, one could logically state that the more images analysed then the longer the run time and more accurate it will be to distinguish the identifier.

However what interests this group it how much longer will the run time be and how much will the accuracy change, once this analysis is complete, we can explore using different filters, change the script and change the image format to shorten the run time and improve accuracy. Upon initial review of the requirements, the data set is 12gb (Mostly copies of images in different formats) but only consists of 3.14gb of usable images, the Cassava data set [1] and script will be written in python which all members have and will be linked to commit to GitLab regularly. No other significant requirements are visible at this stage. The group chosen this data set as it's feasible that it can be manipulated and rewritten, we all are comfortable and believe the project goals are achievable with our current understanding.

The initial plan is to divide the workload whilst all committing to the project on GitLab. The report, research, presentation and analysis will be given to each member as their primary contribution to the project. Each group member will explore different number of images supplied to the final script to which will be analysed later via a graph displaying run time, accuracy against number of supplied images. The initial research is on-going currently as we begin to write the ML script, to which we will run a proof of concept and run 5k, 10k, 20k images and compare the run time, accuracy. In the second sprint we refine the Python script repeat the proof of concept which will give us a good comparison to how we have improved the Python script."

As a group we created various models and completed a variety of tests on these models with the main aim of improving accuracy for the testing set. We adjusted the epochs, we changed the shape of the model, the sizes of the images and augmented the images that were being read into the model. The aim was to find the best of all changes to eventually see how they worked together to end up with the best model we could for the Cassava data set, with a peak accuracy of 67% we feel that whilst it could be improved, for the size of the data set and the number of classifiers required of it that this result is very good. The images are complex and very large to start with so for a model with around 100 epochs to get a result like this was a good step forward and shows that perhaps with more changes to the data set, perhaps by flipping images along the vertical, we could have achieved an accuracy closer to 80\% with more epochs to train the model. With the Cognitive Neural Network model, training the 2d convolutional layers separately from the dense layer allowed the system to train not just faster but it improved the test accuracy up to 63\% which is the highest we've managed to get. The system however requires a lot of power to run the model and we confidently feel that the we have improved this model.

### Built With

LaTeX, Overleaf, BibTeX

### Other Infomation

LaTeX Report: https://github.com/Mysftz/cassava-plant-disease-detection-classification-thesis </br>
Python Files: https://github.com/Mysftz/cassava-plant-disease-detection-classification

<p align="right">(<a href="#readme-top">back to top</a>)</p> 

<!-- USAGE -->
## Usage

This report was submitted for the degree of a Masters of Science in Computer Science (Artificial Intelligence) at the University of Kent in April 2022.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License
Distributed under the CC-BY-SA-4.0: Creative Commons Attribution Share Alike 4.0 International License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- OTHER PROJECTS --> 
## Other Projects
<div align="center">
<a href="https://github.com/stars/Mysftz/lists/data-science-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-DataScience.jpeg?raw=true" alt="Data Science Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/data-analysis-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-DataAnalysis.jpeg?raw=true" alt="Data Analysis Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/university-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-University.jpeg?raw=true" alt="University Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/python-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Python.jpeg?raw=true" alt="Python Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/latex-projects" style="margin:10px; padding-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Latex.jpeg?raw=true" alt="LaTeX Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/other-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Other.jpeg?raw=true" alt="Other Projects Button" width="265" height="75"></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
<div align="center">

GitHub: [@Mysftz](https://github.com/Mysftz) &nbsp;&middot;&nbsp; Portfolio: [Website](https://mysftz.github.io) &nbsp;&middot;&nbsp; LinkedIn: [@lrgtomaszewski](https://www.linkedin.com/in/lrgtomaszewski/) &nbsp;&middot;&nbsp; Instagram: [@Mysftz](https://www.instagram.com/mysftz/) &nbsp;&middot;&nbsp; Twitter: [@MysftzUK](https://twitter.com/MysftzUK)
</div>

[contributors-shield]: https://img.shields.io/github/contributors/mysftz/cassava-plant-disease-detection-classification-thesis.svg?style=for-the-badge
[forks-shield]: https://img.shields.io/github/forks/mysftz/cassava-plant-disease-detection-classification-thesis.svg?style=for-the-badge
[stars-shield]: https://img.shields.io/github/stars/mysftz/cassava-plant-disease-detection-classification-thesis.svg?style=for-the-badge
[issues-shield]: https://img.shields.io/github/issues/mysftz/cassava-plant-disease-detection-classification-thesis.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/mysftz/cassava-plant-disease-detection-classification-thesis.svg?style=for-the-badge
[github-shield]: https://img.shields.io/badge/-GitHub-black.svg?style=for-the-badge&logo=GitHub&colorB=555