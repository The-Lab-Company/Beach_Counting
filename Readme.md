## Pacakges

        pip install pafy
        pip install --upgrade youtube_dl
        pip install opencv-contrib-python==4.2.0.*
        pip install lxml
        pip install bs4
        pip install tensorflow==1.13.1
        apt update && apt install -y libsm6 libxext6 libxrender-dev


After install packages, should copy models and config folder manually because these folders are not included in the repository.


## Run script for person detection

        python process_video.py [source]
        

## Donwload models
    wget https://drive.google.com/file/d/1pIwotoRlgUH09eyQvKXnhquMSx8RDWQS/view?usp=sharing
    wget https://drive.google.com/file/d/1AwqhHwOcxg7jq2iU_FeAMT-F4Z-qq3Va/view?usp=sharing