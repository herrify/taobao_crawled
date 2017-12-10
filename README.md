# 淘宝爬虫
###### 利用selenium抓取淘宝商品列表
###### 利用requests抓取商品评论
###### 将保存数据到mysql和mongodb


#### 抓取商品的关键字
* 商品的id
* 店铺id
* 商品的url
* 商品价格
* 商品的销量
* 商品的名称
* 店铺名字
* 店铺地址


#### 抓取评论的关键字
* 用户的id
* 用户购买的商品分类
* 用户的评论


#### 抓取原理
* 利用selenium模拟访问，获取指定商品的总页数，然后分别获取每页的商品信息，并保存到数据库
* 利用抓取到的商品信息，用商品id和店铺id构造url，访问得到json数据，在将其保存到数据库


