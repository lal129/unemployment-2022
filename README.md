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
## Configuration
Obtain an API KEY from AlphaVantage

Then create a local ".env" file and provide key like this:
```sh
ALPHAVANTAGE_API_KEY="___"
```

## Usage
Run Unemployment Report: 
```sh
python -m app.unemployment
```

Run stocks report:
```sh
python -m app.stocks
```