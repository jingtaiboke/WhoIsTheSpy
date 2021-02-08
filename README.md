# 谁是卧底
适合面对面玩谁是卧底游戏

#适用场景
* 仅适用于面对面玩
* 3人及3人以上(为啥有的最少4人?)


[原Demo](http://sswd.zhengyi.one) 

[原demo2](http://sswd2.zhengyi.one)

[License](https://zhengyi.mit-license.org/@2017)

[新Demo](https://wodi.dianbao.eu.org) 

首先感谢原作者,童童喜欢玩,自己搭建了一个,方便添加词汇

## 在python3下运行要注意

* 38行,略作修改

`db = Database('WhoIsTheSpy.sqlite',check_same_thread=False)`
* 111行略作修改

`uid = uuid.uuid4().hex #get_hex() `

## 其他修改

* fork图片去掉(cn无法访问)
* 房间内增加二维码,方便扫码
* [bootstrap CDN](/root/WhoIsTheSpy/wodi_venv/lib/python3.7/site-packages/flask_bootstrap/__init__.py) 更换为国内源

## 待办

* 裁判出题
20210208 2:22竣工

