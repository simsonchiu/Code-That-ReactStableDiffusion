# Run

```sh
source venv/Scripts/activate

# Export
export HUGGING_FACE_AUTH_TOKEN="TOKEN"

# Run dev fast api
cd api
uvicorn api:app --reload
```

## Install

```sh
# Initialize venv
/c/Users/simso/AppData/Local/Programs/Python/Python310/python -m venv venv

source venv/Scripts/activate

# install torch with cuda
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

pip install -r requirements.txt

# Put hugging face auth token in .env file

```