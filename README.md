# Semantic Segmentation Martian Terrain Using Transformers

NASA has been at the forefront of extraterrestrial exploration, which has been the primary focus of human science research, for decades. Machine learning has been a major factor in enabling  autonomy, increasing the cost-effectiveness and decreasing the duration of space missions.
We focus on the topography of Mars for navigation of rovers. <br/>
AI4Mars Dataset includes terrain images from Curiosity, Opportunity and Spirit(MER) rovers.
This project model recognises landscape features - Sand, Soil, Rock, Rover, Horizon and predicts the same.


[Raw Dataset](https://data.nasa.gov/Space-Science/AI4MARS-A-Dataset-for-Terrain-Aware-Autonomous-Dri/cykx-2qix)<br/>
[Preprocessed Annotated Dataset](https://huggingface.co/datasets/Ankhitan/1000Samples)


<div class="box">
<img width="475" alt="image" src="https://user-images.githubusercontent.com/67890839/184526485-adabe245-6e66-41a5-8537-9b3145a27cb2.png"><br/>
&nbsp;&nbsp;<figcaption align = "center">Fig.1 - EDA - K-Means Clustering, Convex Hull</figcaption>

<img width="380" alt="image" src="https://user-images.githubusercontent.com/67890839/184527671-895613e0-4d4e-40cb-b702-701633471318.png"><br/>
&nbsp;&nbsp;<figcaption align = "center">Fig.2 - Rover Detection</figcaption>

<img width="475" alt="image" src="https://user-images.githubusercontent.com/67890839/184526370-cd028c4c-c4ca-4cf9-a5a5-63151d32e6c5.png"><br/>
&nbsp;&nbsp;<figcaption align = "center">Fig.3 - Masking</figcaption>

<img width="491" alt="image" src="https://user-images.githubusercontent.com/67890839/184526104-997af0a6-4ea1-43de-aea0-26c00e7fcc9b.png">

SegFormer B2 outperformed B0 and B1. Per Class metrics are mentioned below:<br/>
<img width="485" alt="image" src="https://user-images.githubusercontent.com/67890839/184526201-9271113a-b533-4749-97f4-fb1d66f50354.png">



## Model Output
<img width="393" alt="image" src="https://user-images.githubusercontent.com/67890839/184526058-f80e3cd2-dfc2-40f8-b544-99d06abc2f55.png"><br/>
Purple - Rock,
Yellow - Soil,
Brown - Sand
</div>

:point_up: <b>Most of the files are large, hence cannot be viewed on github. To view .ipynb notebooks, clone this repository.</b><br/>
:point_up: <b>List of helpful links and articles in references.txt</b>

## Contributors 
* [Ankitha C](https://github.com/Ankithac45)
* [Gagan Goutham](https://github.com/GaganGoutham)
* [Hita Juneja](https://github.com/hita03)

