# Donate-Page simple

#### Fork后需要修改以下内容为你的账户

	/script.js:4-6 对应账户的二维码路径

	/index.html:28 PayPal.me的收款页面地址

	/index.html:37 `<input id="btc-key" type="text" value="比特币收款地址" readonly="readonly">`

#### PayPal.me收款地址可以加入项目和金额参数，如：

`https://kaiyuan.github.io/donate-page/simple/?item='donate-page&price=2'`


#### 使用`iframe`嵌载方式高度至少`200px`，宽度至少`130px`，如：

```
<iframe src="http://www.yzmb.me/usr/themes/jzwalk/donate.html" scrolling="no" width="200px" height="130px" frameborder="0"></iframe>
```

### License

Released under the MIT license.
