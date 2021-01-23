# scap-v2-prototype
This prototype implements the components and basic message flows for the SCAP v2 Architecture which is defined [here](https://groups.google.com/a/list.nist.gov/g/scap-dev-endpoint/c/Uqdzr_ORqjM).

## Build Instructions
The following provides instructions on how to set up the SCAP v2 prototype on Ubuntu 20.04.

### Install Docker
Docker can be installed using the instructions found [here](https://docs.docker.com/engine/install/ubuntu/). Docker may be installed on other operating systems by following the instructions found [here](https://docs.docker.com/get-docker/).

### Install OpenDXL
The [OpenDXL Broker](https://hub.docker.com/r/opendxl/opendxl-broker/) Docker image can be retrieved using the following command.

`sudo docker pull opendxl/opendxl-broker`
