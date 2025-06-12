# AI-CUP

extract features:

origin code 用於extract features

change code (27feature average)用於extract 27features後average

change code (27feature)用於extract 27features

lightGBM:

  train method:
  
    origin code for origin code & change code (27feature average)
    
    change code (27feature train) for change code (27feature)

  test method(cv_predict):
  
    origin code for origin code & change code (27feature average)
    
    change code (27feature test) for change code (27feature)

XGboost:

  train method:
  
  origin code for origin code
  
  test method(cv_predict):
  
  XGboost for origin code

output csv 輸出最後預測結果(csv)

