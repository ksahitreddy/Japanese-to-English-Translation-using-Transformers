# Japanese To English Translation using Transformers

## Dataset

You can download or refer the dataset used here by clicking on [this link](https://huggingface.co/datasets/Helsinki-NLP/opus-100).


## Usage

Run the following command to install the required dependencies:

```bash
pip install -r requirements.txt
```

After installing the dependencies, run the code with:

```bash
python train.py
```

If you want to change the configuration of the training such as epochs, batch size, sequence length, etc., you can do so in the [config.py](config.py) file.
