## Accelerate ML model inferencing using open-source tools and deploy the model

In this workshop, we'll convert huggingface/transformers BERT model to the
high-performant, interoperable [ONNX](https://github.com/onnx/onnx) format,
then inference the converted model using the open-source [ONNX Runtime](https://github.com/microsoft/onnxruntime).
We'll then demonstrate how to deploy the ONNX model as a hosted webservice
using [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/).

### Getting Started
1) Open Jupyter notebook
2) From Jupyter, click on "New" -> "Terminal" and then clone this repository:
```
git clone https://github.com/prabhat00155/onnx-odsc-east
```
3) Open [pytorch-bert-experiment-exercise.ipynb](https://github.com/prabhat00155/onnx-odsc-east/blob/master/pytorch-bert-experiment-exercise.ipynb)
and run the first four cells(to install the dependencies, import the required
packages, list pre-trained BERT models and download one of them).

### Additional Resources
- [BERT WebApp Demo project](https://github.com/prabhat00155/bert-webapp): https://github.com/prabhat00155/bert-webapp
- [Blogpost](https://opendatascience.com/tutorial-accelerate-and-productionize-ml-model-inferencing-using-open-source-tools/)
- Hands-on tutorial session from ODSC London: https://github.com/prabhat00155/onnx-odsc-tutorial
- [BERT inference acceleration with
  onnxruntime](https://cloudblogs.microsoft.com/opensource/2020/01/21/microsoft-onnx-open-source-optimizations-transformer-inference-gpu-cpu/)
- [Additional
  resources](https://github.com/prabhat00155/onnx-odsc-tutorial/blob/master/additional-resources.md).

