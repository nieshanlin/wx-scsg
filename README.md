# wx-scsg
一个可以听歌，仿豆瓣评分的微信小程序：
本作品的第一个界面采用模拟后台加载
，用轮播实现文章推荐作用。将准备好的文章资源存储在一个文件中，依次循环加载数据，达到界面随数据变化而逐量递增，实现了小程序的模块化加载，然后采用微信小程序常用的界面跳转传参方式，将第一个界面的值传个第二个界面，节省大量代码，并在第二个界面实现收藏，转发，留言，播放背景音乐等前端功能。第二个界面实行调用了4个免费的接口，将后台的数据展示，点击进入更多页面，可以随用户下拉而循环加载页面数据，打开搜索栏，可实现对电影的搜索功能，并实现页面之间的相互带参跳转，第三个页面实现了用户登录三个页面跳转分别对应的是影视，文章，音乐，在音乐界面模拟了后台的音乐数据，使用户可以查看音乐资料，实现了一个简易音乐播放器的功能。另外由于本小程序所有的数据均来自于网络，所以本小程序能够完美的在手机端运行。
