Test Model Locally
------------------
- Create python virtual environment.
  python3 -m venv .venv

- Enable python virtual environment.
  source ./.venv/bin/activate

- Install dependencies
  python3 -m pip install -r requirements.txt

- Train the model
  python3 train.py

- Run the model
  python3 run_model.py --input "[10,1,5,10]"
  python3 run_model.py --input "[10,1,5,2]"
  python3 run_model.py --input "[10,1,1,1]"

Note: It creates artefacts/ directory and within it, It creates metrics.json and model.json.