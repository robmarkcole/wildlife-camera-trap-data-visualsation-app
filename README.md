# wildlife-camera-trap-data-visualsation-app
Wildlife camera trap data consists of geolocated time stamped images in folders. This app enables processing of images to identify animal species in images, logging of the time and location of the animals, and visualisation of the logged data on a map with time scrubbing. 

## Project goals
* Develop easy to use app for neural network processing of timelapse & camera trap data
* Generates a table of species and number of animal seen in each frame
* See how different models perform on your dataset and allow comparison with 'ground truth'
* Facilitates transfer learning on tflite models with the goal of deployment on live & low cost detection systems 
* Investigate ways to engage [citizen scientists & experts](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.13099) to assist with curating & labelling datasets
* Use 'free' resources such as google drive for hosting data and google colab for compute (TPU)

## MVP
* Jupyter notebook for processing single folder of images, generating a table of results, and provide a visualisation of the timeline data (scrubbing through processed images)

## Tech resources
* (top hit) https://agentmorris.github.io/camera-trap-ml-survey/ -> comprehensive set of links covering ML camera traps
* https://www.microsoft.com/en-us/ai/ai-for-earth-tech-resources -> datasets and APIs
* https://github.com/microsoft/CameraTraps -> microsoft camera traps processing package
* https://dash-gallery.plotly.host/dash-object-detection/ -> plotly object detection dashboard
* https://github.com/streamlit/demo-self-driving -> streamlit object detection explorer

## Datasets
* http://lila.science/datasets
* [Camera trap database of Tiger from Rajaji National Park, Uttarakhand](https://www.gbif.org/dataset/e61455a4-352d-4c55-83ea-dbca254e3b29)
