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

## Resources
* (top hit) https://agentmorris.github.io/camera-trap-ml-survey/ -> comprehensive set of links covering ML camera traps
* https://www.wildlifeinsights.org/home -> Google backed platform to identify, share, analyze and discover near-real time information on wildlife, all in one place. Read [Googles blog post](https://blog.google/products/earth/ai-finds-where-the-wild-things-are/)
* https://www.microsoft.com/en-us/ai/ai-for-earth-tech-resources -> datasets and APIs
* https://github.com/microsoft/CameraTraps -> microsoft camera traps processing package
* https://dash-gallery.plotly.host/dash-object-detection/ -> plotly object detection dashboard
* https://github.com/streamlit/demo-self-driving -> streamlit object detection explorer
* NOAA fish monitoring tools -> https://nmfs-fish-tools.github.io/ and [read](http://www.viametoolkit.org/wp-content/uploads/2016/09/VIAME-overview-web.pdf?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&utm_content=79366324&_hsenc=p2ANqtz-_I6w5gBfe6po6ckmFgZJSOuCD8gLwy2UcSnN0W6xlZ6LC1xOP6mYP4LuOcoRNzd5he_M5DFmt-9uXfr-RsyL0G3sM6EA&_hsmi=79366324)
* [Photoprism](https://github.com/photoprism/photoprism)
* [EcoAssist](https://github.com/PetervanLunteren/EcoAssist) -> An application for detecting animals in camera trap images

## Datasets
* http://lila.science/datasets
* [Camera trap database of Tiger from Rajaji National Park, Uttarakhand](https://www.gbif.org/dataset/e61455a4-352d-4c55-83ea-dbca254e3b29)
