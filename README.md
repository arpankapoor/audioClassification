# audio classification using an ensemble of 1D and 2D CNN

- download the [UrbanSound8K dataset](https://urbansounddataset.weebly.com/urbansound8k.html) and extract it to `data/UrbanSound8K/`
- trained model weights and dataset is available [here](https://drive.google.com/drive/folders/12Oa8ZO4UPmx9zHkwkpy1p3ToVti4Wzpb?usp=sharing)

- directory structure after setting up the data and model weights:

  ```
  - 1d.ipynb
  - 2d.ipynb
  - demo.ipynb
  - audio.wav (sample used for demo)
  - data/
      - UrbanSound8K/
      - saved_models/ (model parameters for 1D CNN)
      - 2d_saved_models/ (model parameters for 2D CNN)
      - vgg_saved_models/ (model parameters for VGG16 fine tuned 2D CNN)
  ```
- python dependencies:
  - jupyterlab
  - tensorflow-gpu
  - librosa
  - pandas
- for more details refer to the [report](report.pdf)
