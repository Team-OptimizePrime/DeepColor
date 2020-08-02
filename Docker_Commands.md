* git clone https://github.com/baldassarreFe/deep-koalarization
* git clone https://github.com/chandralegend/deep_colorization_with_object_detection
* cd deep-koalarization/data/original
* unzip ../../../deep_colorization_with_object_detection//unsamples.zip
* cd ../../
* curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
* bash Miniconda3-latest-Linux-x86_64.sh
* exec bash
* conda create -y -n koalarization python=3.6
* conda activate koalarization
* pip install -e .
* pip install numpy==1.14.5
* python -m koalarization.dataset.resize 'data/original' 'data/resized'
* wget -O - 'http://download.tensorflow.org/models/inception_resnet_v2_2016_08_30.tar.gz' | tar -xzv -C 'data'