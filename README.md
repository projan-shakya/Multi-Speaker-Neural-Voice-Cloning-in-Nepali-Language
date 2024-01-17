# Multi-Speaker-Neural-Voice-Cloning-in-Nepali-Language


## Step-wise Working 

1. ```!git clone https://github.com/projan-shakya/Multi-Speaker-Neural-Voice-Cloning-in-Nepali-Language.git```
2. ```
   import os
  os.chdir('tacotron2')
  !git submodule init
  !git submodule update
  !pip install -q unidecode tensorboardX
  !pip install librosa==0.9.2```

3. Upload wav file on drive then
   ```!cp -r /content/drive/MyDrive/wav.zip /content/tacotron2```
4. ```!unzip wav.zip```

5.  To train type this code
   ```!python train.py --output_directory=<drivelink> --log_directory=<drivelink> -c <last_checkpointfile> --warm_start```
