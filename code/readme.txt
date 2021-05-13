运行环境：Jupyter notebook  6.3.0


1.首先运行feature.ipynb文件，将其中测试集路径改为自己的路径，用于提取特征，并在该路径下生成特征文件，
形如oterfile文件夹里的test_feature.csv文件。在ipynb文件里先运行 第一个代码块，再运行第二个。

所用到的库：
import csv
import pandas as pd
import random
import torch
import torch.nn as nn
import torch.utils.data as Data
import torchvision
from torch.autograd import Variable
from torch.utils.data import DataLoader
from torch.utils.data import Dataset
import torch.nn.functional as F
from scipy import stats,signal,fftpack
import math
from pywt import wavedec
import traceback
import sys
import os

2.然后运行predict.ipynb文件，会在该路径下生成result3.csv结果文件。

所用到的库：
import csv
import pandas as pd
import joblib
from sklearn.ensemble import RandomForestClassifier

