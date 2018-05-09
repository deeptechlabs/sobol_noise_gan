## Sobol Noise Vector Comparison with Normal Distribution

## Usage

#### 1. Install the dependencies
```bash
$ pip install -r requirements.txt
```

#### 2. Download the dataset
```bash
$ chmod +x download.sh
$ ./download.sh
```

#### 3. Train the model
```bash
$ python main.py --mode='train'
```

#### 4. Train the model (Sobol)
```bash
$ python main.py --mode='train' --sobol_noise
```

#### 5. Sample the images
```bash
$ python main.py --mode='sample'
```


