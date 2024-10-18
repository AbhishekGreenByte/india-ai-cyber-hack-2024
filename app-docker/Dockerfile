# Using Latest Fedora
FROM fedora:latest

# Install system dependencies
RUN dnf -y update && dnf install -y \
    python3 \
    python3-pip \
    gcc \
    make \
    curl \
    && dnf clean all \
    && rm -rf /var/cache/dnf

# Set the default Python version
RUN ln -sf /usr/bin/python3 /usr/bin/python

# Install PyTorch (with CPU support)
RUN pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

# Install TensorFlow (with CPU support)
RUN pip3 install tensorflow