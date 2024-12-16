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

## Change configuration and hyperparameters

If you want to change the configuration of the training process such as number of epochs, batch size, sequence length, etc., you can do so by editing the [config.py](config.py) file.
