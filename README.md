# edge-tpu-demo
A deep learning inference demo running on Coral Edge TPU USB Accelerator

docker build -t "tpu" .
docker run -it --privileged -v /dev/bus/usb:/dev/bus/usb tpu /bin/bash