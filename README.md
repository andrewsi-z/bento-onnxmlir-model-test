# bento-onnxmlir-model-test

This project demonstrates using ONNX-MLIR to compile the resnet50 model from the ONNX model zoo, and then leverages BentoML to deploy for inference. 

## Install ONNX-MLIR 

[ONNX-MLIR documentation](http://onnx.ai/onnx-mlir/)

[ONNX-MLIR project](https://github.com/onnx/onnx-mlir)

Follow the install instructions. This will include installing prerequisites, including LLVM. 
Since ONNX-MLIR is a recent project as of this writing, we suggest pulling in the most recent stable version.

Alternatively, docker images are available. See the links on the ONNX-MLIR project page.

## Compiling the model an running example

See [resnet notebook](https://github.com/andrewsi-z/bento-onnxmlir-model-test/blob/41230432acf09d37562c5b65f2d575b6637ccc77/resnet50_onnxmlir.ipynb)



