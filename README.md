# HW1

import pandas as pd
import numpy as np
from sklearn.cluster import DBSCAN
import matplotlib.pyplot as plt

sup_all = pd.DataFrame(pd.read_csv("/content/供應商基本資料檔.csv"))
sup_all

buy_h_all = pd.DataFrame(pd.read_csv("/content/採購單單頭檔.csv"))
buy_h_all

buy_d_all = pd.DataFrame(pd.read_csv("/content/採購單單身檔.csv"))
buy_d_all
