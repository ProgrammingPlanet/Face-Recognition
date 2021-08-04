## Highly accurate facial recognition

#### only supported on mac os & linux 

### setup 

```
$ git clone https://github.com/ProgrammingPlanet/Face-Recognition.git

$ cd Face-Recognition

$ python -m venv .env

$ source .env/bin/activate

$ pip install -r requirements.txt

```


### trainning mode

```
(.env) $ python main.py 

```

### prediction mode

change ```phase = 'trainning'``` to ```phase = 'prediction'``` in main.py 

```
(.env) $ python main.py

```