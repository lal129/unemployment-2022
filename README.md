# unemployment-2022

## Setup
Create enviornment:
```sh
conda create -n unemployment-env python=3.8
conda activate unemployment-env
```

Install Package Dependencies:
```sh
pip install -r requirements.txt
```

## Usage
Run Unemployment Report: 
```sh
python app/unemployment.py

#or pass env var from command line:
ALPHAVANTAGE_API_KEY="___" python app/unemployment.py
```