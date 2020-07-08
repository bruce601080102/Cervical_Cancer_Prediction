# 子宮頸癌預測分析(中華商管研討會論文)
### 數據來源
- 加拉加斯的大學醫院
- 首都地區最大的專業醫療中心
- 資料數量為36個欄位
- 目前在IEEE期刊上有刊登使用Random Forest以及Support Vector Machine做預測的相關文獻

### 數據需要注意
- 數據不平衡需要使用SMOTE製造假資料
-------

### 子宮頸癌一共有四種檢測方式，因此需要將四個方法做預測分析，下面是整個的流程圖:
|Hinselmann| Schiller |  Biopsy  | Citology   |
| :------------: | :------------: | :------------: | :------------: |
| 陰道鏡檢查  |   子宮頸粘膜碘試驗| 活體組織切片  | 子宮頸或陰道抹片檢查 |
| 陰道鏡是一種可以將子宮頸放大4到30倍的子宮頸檢查內視鏡，陰道鏡並不會伸入陰道內。| 將盧戈氏碘液塗抹在子宮頸上，觀察細胞的顏色。  |  活檢方式很多，採取手術切除、內視鏡或針頭穿刺吸取等。|  子宮頸抹片檢查是採取子宮頸及陰道後壁的剝落細胞所做的檢查。 |

![image](https://github.com/bruce601080102/Cervical_Cancer_Prediction/blob/master/%E5%9C%96%E7%89%87/%E6%B5%81%E7%A8%8B%E5%9C%96.png)
![image](https://github.com/bruce601080102/Cervical_Cancer_Prediction/blob/master/%E5%9C%96%E7%89%87/%E6%B5%81%E7%A8%8B%E5%9C%962.png)
-------
### 最後預測的結果
![image](https://github.com/bruce601080102/Cervical_Cancer_Prediction/blob/master/%E5%9C%96%E7%89%87/%E5%9C%96%E7%89%871.png)
![image](https://github.com/bruce601080102/Cervical_Cancer_Prediction/blob/master/%E5%9C%96%E7%89%87/%E5%9C%96%E7%89%872.png)
![image](https://github.com/bruce601080102/Cervical_Cancer_Prediction/blob/master/%E5%9C%96%E7%89%87/%E5%9C%96%E7%89%873.png)
![image](https://github.com/bruce601080102/Cervical_Cancer_Prediction/blob/master/%E5%9C%96%E7%89%87/%E5%9C%96%E7%89%874.png)
