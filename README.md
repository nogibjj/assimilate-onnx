# Assimilate ONNX
A good starting point for a new Rust project

### Day 2:  Need to solve model portability problem

A.  Give user ability to download model via Rust CLI and accept images for path
B.  Include model inside of Rust binary

### Day 1:  Demo Sonos/Tract and Rust Wrapper Onnx

Status:  
* Got both Resnet and /example-onnx-mobilenet-v2 working by cloning repo.
* When I copy both binaries to a /tmp directory it needs both the model and the image in the same repo.
* Takeaway:  Runtime works, but need to have both model and image.

* https://github.com/sonos/tract
* https://github.com/nbigaouette/onnxruntime-rs
* https://github.com/microsoft/onnxruntime

Trying the #rust bindings example for `onnxruntime-rs`

1. cd into project
2. curl -LO "https://github.com/onnx/models/raw/master/vision/classification/squeezenet/model/squeezenet1.0-8.onnx"


## References

