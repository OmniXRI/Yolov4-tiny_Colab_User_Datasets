# Yolov4-tiny_Colab_User_Datasets
Google Colab範例，使用Yolov4-tiny(darknet)對自定義資料集進行訓練及推論

yolov4-tiny_training_test.ipynb 為主程式，包含Yolov4-tiny預訓練測試、自定義資料集訓練及推論測試  
my_dataset.zip 包含100張影像及Yolo格式標註檔(＊.txt)  
my_obj.data 為資料集設定檔  
my_obj.names 為資料集分類標籤名稱  
my_yolov4-tiny-custom.cfg 為自定義模型及相關參數  
my_train.txt 為自定義資料訓練集檔案名稱列表  
my_val.txt 為自定義資料驗證集檔案名稱列表  
test01.jpg, test02.jpg 為測試用影像  

訓練時間約1~1.5小時，視分配到的GPU類型及網路速度。 

Loss 和 mAP變化圖如下： 
![](https://raw.githubusercontent.com/OmniXRI/Yolov4-tiny_Colab_User_Datasets/main/images/chart_my_yolov4-tiny-custom.png)

測試結果（test01.jpg）  
![](https://raw.githubusercontent.com/OmniXRI/Yolov4-tiny_Colab_User_Datasets/main/images/result_test01.png)

測試結果（test02.jpg）  
![](https://raw.githubusercontent.com/OmniXRI/Yolov4-tiny_Colab_User_Datasets/main/images/result_test02.png)

## 完整說明文章請參閱[如何以Google Colab及Yolov4-tiny來訓練自定義資料集─以狗臉、貓臉、人臉偵測為例](https://omnixri.blogspot.com/2021/05/google-colabyolov4-tiny.html)
