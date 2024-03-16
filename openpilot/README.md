How to use Carla for co-simulation with openpilot

Ubuntu: 20.04, Docker 24.0
Carla: 0.9.13

After installing Carla locally follow these steps:

1. Pull this image: ghcr.io/commaai/openpilot-sim@sha256:6e47f5756c1ef08d83e1b78bf58d57d87da8f92c9fcdfdd042a3e8985413bb35
2. Download start_openpilot_docker.sh locally
3. Modify a few files:
4. In tmux_script.sh in the image, add --high_quality --dual_camera after the command to run bridge.py.
5. In the local start_openpilot_docker.sh, run the modified image.
6. Enjoy.
