你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# amzn-url-shoter
This is generate short Amazon Web URL.(This is only support region Japan )

```sh
$ amzn-url-shorter "https://www.amazon.co.jp/SIM%E3%82%AB%E3%83%BC%E3%83%89-SIM%E5%BE%8C%E6%97%A5%E3%81%8A%E5%B1%8A%E3%81%91-%E3%83%89%E3%82%B3-NIFMO-01-02/dp/B00PLA8OMA"
https://amazon.co.jp/dp/B00PLA8OMA

$ amzn-url-shorter < urls.txt
https://amazon.co.jp/dp/B087GHS748
https://amazon.co.jp/dp/B083ZVZXSW
```

## Usage
```sh
$ amzn-url-shorter url
$ amzn-url-shorter < file
```

## Installation
```sh
$ go get github.com/skanehira/amzn-url-shorter/cmd/amzn-url-shorter
```

You also can download from [releases](https://github.com/skanehira/amzn-url-shorter/releases)

## Author
skanehira
