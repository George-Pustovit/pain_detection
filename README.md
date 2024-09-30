# Pain detection using EMG,EEG,ECG signals

## Последняя версия practice 30.09.2024
Practice_v2.0.ipynb - извлечение данных из эксперимента 3 () https://osf.io/bsv86/ 

## CNN для обучения 
VGG16.ipynb
EfficientNet.ipynb
InceptionV3.ipynb

## Системные характеристики ПК:
OS: Windows 10 Pro
GPU: NVIDIA RTX 4060
CPU: i5 12400F
RAM: 16 GB

## Пакеты использованные для обучения: 
python 3.7

NVIDIA DRIVER
+-----------------------------------------------------------------------------------------+
| NVIDIA-SMI 560.94                 Driver Version: 560.94         CUDA Version: 12.6     |
|-----------------------------------------+------------------------+----------------------+
| GPU  Name                  Driver-Model | Bus-Id          Disp.A | Volatile Uncorr. ECC |
| Fan  Temp   Perf          Pwr:Usage/Cap |           Memory-Usage | GPU-Util  Compute M. |
|                                         |                        |               MIG M. |
|=========================================+========================+======================|
|   0  NVIDIA GeForce RTX 4060      WDDM  |   00000000:01:00.0  On |                  N/A |
|  0%   41C    P8             N/A /  115W |    7182MiB /   8188MiB |      1%      Default |
|                                         |                        |                  N/A |
+-----------------------------------------+------------------------+----------------------+

| Package                      | Version            |
|------------------------------|--------------------|
| cudatoolkit                   | 11.2               |
| cudnn                         | 8.1.0              |

| Package                      | Version            |
|------------------------------|--------------------|
| absl-py                       | 2.1.0              |
| anyio                         | 3.7.1              |
| argon2-cffi                   | 23.1.0             |
| argon2-cffi-bindings          | 21.2.0             |
| asgiref                       | 3.7.2              |
| astor                         | 0.8.1              |
| astunparse                    | 1.6.3              |
| attrs                         | 24.2.0             |
| backcall                      | 0.2.0              |
| beautifulsoup4                | 4.12.3             |
| bleach                        | 6.0.0              |
| cachetools                    | 4.2.4              |
| certifi                       | 2024.8.30          |
| cffi                          | 1.15.1             |
| charset-normalizer            | 3.3.2              |
| colorama                      | 0.4.6              |
| cycler                        | 0.11.0             |
| debugpy                       | 1.7.0              |
| decorator                     | 5.1.1              |
| defusedxml                    | 0.7.1              |
| Django                        | 3.2.25             |
| entrypoints                   | 0.4                |
| exceptiongroup                | 1.2.2              |
| fastjsonschema                | 2.20.0             |
| flatbuffers                   | 24.3.25            |
| fonttools                     | 4.38.0             |
| gast                          | 0.2.2              |
| google-auth                   | 1.35.0             |
| google-auth-oauthlib          | 0.4.6              |
| google-pasta                  | 0.2.0              |
| grpcio                        | 1.62.3             |
| h5py                          | 3.8.0              |
| idna                          | 3.10               |
| image                         | 1.5.33             |
| importlib-metadata            | 6.7.0              |
| importlib-resources           | 5.12.0             |
| ipykernel                     | 6.16.2             |
| ipython                       | 7.34.0             |
| ipython-genutils              | 0.2.0              |
| jedi                          | 0.19.1             |
| Jinja2                        | 3.1.4              |
| jsonschema                    | 4.17.3             |
| jupyter_client                | 7.4.9              |
| jupyter_core                  | 4.12.0             |
| jupyter-server                | 1.24.0             |
| jupyterlab-pygments           | 0.2.2              |
| keras                         | 2.10.0             |
| Keras-Applications            | 1.0.8              |
| Keras-Preprocessing           | 1.1.2              |
| kiwisolver                    | 1.4.5              |
| libclang                      | 18.1.1             |
| Markdown                      | 3.4.4              |
| MarkupSafe                    | 2.1.5              |
| matplotlib                    | 3.5.3              |
| matplotlib-inline             | 0.1.6              |
| mistune                       | 3.0.2              |
| mne                           | 1.3.1              |
| nbclassic                     | 1.1.0              |
| nbclient                      | 0.7.4              |
| nbconvert                     | 7.6.0              |
| nbformat                      | 5.8.0              |
| nest-asyncio                  | 1.6.0              |
| notebook                      | 6.5.7              |
| notebook_shim                 | 0.2.4              |
| numpy                         | 1.21.6             |
| oauthlib                      | 3.2.2              |
| opt-einsum                    | 3.3.0              |
| packaging                     | 24.0               |
| pandas                        | 1.3.5              |
| pandocfilters                 | 1.5.1              |
| parso                         | 0.8.4              |
| pickleshare                   | 0.7.5              |
| Pillow                        | 9.5.0              |
| pip                           | 22.3.1             |
| pkgutil_resolve_name          | 1.3.10             |
| platformdirs                  | 4.0.0              |
| pooch                         | 1.8.2              |
| prometheus-client             | 0.17.1             |
| prompt_toolkit                | 3.0.48             |
| protobuf                      | 3.19.6             |
| psutil                        | 6.0.0              |
| pyasn1                        | 0.5.1              |
| pyasn1-modules                | 0.3.0              |
| pycparser                     | 2.21               |
| Pygments                      | 2.17.2             |
| pyparsing                     | 3.1.4              |
| pyrsistent                    | 0.19.3             |
| python-dateutil               | 2.9.0.post0        |
| pytz                          | 2024.2             |
| pywin32                       | 306                |
| pywinpty                      | 2.0.10             |
| pyzmq                         | 26.2.0             |
| requests                      | 2.31.0             |
| requests-oauthlib             | 2.0.0              |
| rsa                           | 4.9                |
| scipy                         | 1.7.3              |
| Send2Trash                    | 1.8.3              |
| setuptools                    | 65.6.3             |
| six                           | 1.16.0             |
| sniffio                       | 1.3.1              |
| soupsieve                     | 2.4.1              |
| sqlparse                      | 0.4.4              |
| tensorboard                   | 2.10.1             |
| tensorboard-data-server       | 0.6.1              |
| tensorboard-plugin-wit        | 1.8.1              |
| tensorflow                    | 2.10.0             |
| tensorflow-estimator          | 2.10.0             |
| tensorflow-io-gcs-filesystem  | 0.31.0             |
| termcolor                     | 2.3.0              |
| terminado                     | 0.17.1             |
| tinycss2                      | 1.2.1              |
| tornado                       | 6.2                |
| tqdm                          | 4.66.5             |
| traitlets                     | 5.9.0              |
| typing_extensions             | 4.7.1              |
| urllib3                       | 2.0.7              |
| wcwidth                       | 0.2.13             |
| webencodings                  | 0.5.1              |
| websocket-client              | 1.6.1              |
| Werkzeug                      | 2.2.3              |
| wheel                         | 0.38.4             |
| wincertstore                  | 0.2                |
| wrapt                         | 1.16.0             |
| zipp                          | 3.15.0             |






