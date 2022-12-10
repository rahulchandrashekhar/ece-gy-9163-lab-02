# ece-gy-9163-lab-02

Steps to replicate this code

1. Clone / download the repository locally.
2. Download the following files and place them in the root directory of this repository.
    1. `bd_valid.h5` and `bd_test.h5` from [here](https://drive.google.com/drive/folders/1FoLQD8IzTg9tYYRZXOd-iIvXdijn-GSs)
    2. `test.h5` and `valid.h5` from [here](https://drive.google.com/drive/folders/1_Q3g8Yzres8E4yRLwkO31fAMjTGNPo0i)
    3. `bd_net.h5` and `bd_weights.h5` from [here](https://github.com/csaw-hackml/CSAW-HackML-2020/tree/master/lab3/models)
3. Cycle through the cells in the notebook `rc4783_Homework_2.ipynb` to evaluate.

The accuray metrics can be found in the file `ECE_GY_9163___Lab_2.pdf`

The model evaluation section of the Python notebook is using the `model_10.h5` model. Replace the filename in Cell 27 with `model_2.h5` or `model_4.h5` to evaluate on the other saved models. Specifically, update the filename in this line of code
```python
B_prime = keras.models.load_model("./model_10.h5")
```
