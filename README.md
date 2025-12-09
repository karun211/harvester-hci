# harvester-hci
tips and tricks


Run a container to run the tests.

`sudo nerdctl -a /run/k3s/containerd/containerd.sock run --rm --privileged --net=host -it   -v /dev:/dev -v /sys:/sys   ubuntu:latest`

Inside the container

`apt update && apt install -y iperf3 iproute2`

Now you can easily run the iperf tests
