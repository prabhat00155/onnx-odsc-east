# From Research to Production: Performant cross-platform ML/DNN model inferencing on cloud and edge with ONNX Runtime

In this workshop, we'll convert huggingface/transformers BERT model to the
high-performant, interoperable [ONNX](https://github.com/onnx/onnx) format,
then inference the converted model using the open-source [ONNX Runtime](https://github.com/microsoft/onnxruntime).
We'll then demonstrate how to deploy the ONNX model as a hosted webservice
using [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/).

## Getting Started
1) Open Jupyter notebook
2) From Jupyter, click on "New" -> "Terminal" and then clone this repository:
```
git clone https://github.com/prabhat00155/onnx-odsc-east
```
3) Open [pytorch-bert-experiment-exercise.ipynb](https://github.com/prabhat00155/onnx-odsc-east/blob/master/pytorch-bert-experiment-exercise.ipynb)
and run the first four cells(to install the dependencies, import the required
packages, list pre-trained BERT models and download one of them).

## Additional Resources
#### Related to this workshop
* [BERT WebApp Demo project](https://github.com/prabhat00155/bert-webapp)
* [Presentation slides](./ODSC-East-2020-Slides.pdf)
* [Blog Post - BERT inference acceleration with ONNX Runtime](https://cloudblogs.microsoft.com/opensource/2020/01/21/microsoft-onnx-open-source-optimizations-transformer-inference-gpu-cpu/)
* [Blog Post for ODSC East - Tutorial: Accelerate and Productionize ML Model Inferencing Using Open-Source Tools](https://opendatascience.com/tutorial-accelerate-and-productionize-ml-model-inferencing-using-open-source-tools/)
* [Hands-on tutorial session from ODSC London](https://github.com/prabhat00155/onnx-odsc-tutorial)

#### ONNX
* ONNX ([website](http://onnx.ai/), [Github](https://github.com/onnx/onnx))
* [ONNX Converters](https://github.com/onnx/onnxmltools/tree/master/onnxmltools)
* [ONNX Tutorials](https://github.com/onnx/tutorials)

#### ONNX Runtime
* ONNX Runtime ([website](https://aka.ms/onnxruntime), [Github](https://github.com/microsoft/onnxruntime))
* [ONNX Runtime Tutorials](https://github.com/microsoft/onnxruntime#examples-and-tutorials)
* [Performance Tuning with ONNX Runtime](https://github.com/microsoft/onnxruntime/blob/master/docs/ONNX_Runtime_Perf_Tuning.md)
* [ONNX Runtime on Windows - Windows ML](https://docs.microsoft.com/en-us/windows/ai/windows-ml)

#### Deployment
* [Training, Inferencing, and deployment in AzureML with ONNX models](https://aka.ms/onnxnotebooks)
  * [General Azure Machine Learning resources](https://azure.microsoft.com/en-us/services/machine-learning)
* Deploying to Edge and IoT devices: 
  * [Intel OpenVINO based devices](https://github.com/Azure-Samples/onnxruntime-iot-edge/blob/master/README-ONNXRUNTIME-OpenVINO.md) 
  * [NVIDIA Jetson Nano (ARM64)](https://github.com/Azure-Samples/onnxruntime-iot-edge/blob/master/README-ONNXRUNTIME-arm64.md)



