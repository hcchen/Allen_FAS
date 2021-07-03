# R 筆記@20170415/16

## 分群實體

```
iris = scale(iris[,1:4],center = T , scale = T)
```
### 分幾群比較好

## data.Normalization 

```
data.Normalization (x,type="n0",normalization="column")
```
### n4 - unitization with zero minimum ((x-min)/range)
range = Xmax - Xmin
### n1 - standardization ((x-mean)/sd)

## Fuzzy C means
### 何為「收斂」：誤差值每個iteration改變很小


## MAC 相容 R Studio問題

XQuartz-2.7.11
http://download.cnet.com/XQuartz-X11/3000-2094_4-10912185.html


## 高斯分群 ：適用情境，當 x變數相關 不獨立時
### https://www.dropbox.com/s/gg1hj3iz32yplp9/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202017-04-15%2013.43.00.png?dl=0

## 關連規則 x  是類別     分群 x是數值

###
```
P(SB) = P(S)  P(B) => Statistically independent
P(SB) > P(S)  P(B) => Positively correlated
P(SB) < P(S)  P(B) => Negatively correlated
```
### X -> Y
### Support =c(X,Y)/cTotal 左右兩同時發生交易次數/總交易數
### cofidiance =P(X,Y)/P(X)
### Lift P(X,Y/P(X) * P(Y)

Lift > 1 正相關 
Lift < 1 負相關 
Life = 1 相關

## 一般統計
### H0：虛無假設
### H1：對立假設

## 圈圈代表離群值，比第一四分位低 1.5標準差，比第三四分位高1.5標準差

https://www.dropbox.com/s/j6r6z0fj53jzqgs/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202017-04-16%2013.17.04.png?dl=0

X vs. Y:
類別/類別：卡方檢定
類別/數值：變異數分析
數值/類別：平均值T檢定 (先做變異數F檢定)
數值/數值：相關係數
類別+數值/數值：迴歸
前提：若 “有因果” 則 “有相關”  推論：若 “不相關” 則 “沒因果”


### 運輸上可以應用的地方
#### 運輸轉乘策略

####
悠遊卡OD資料：
交易時間/路線/運具/車輛
=>
時間：星期、小時

