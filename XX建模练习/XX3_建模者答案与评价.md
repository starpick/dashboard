# 建模者答案与评价
## 建模者答案
[https://github.com/heygrandpa/SAD_modeling_practice/blob/master/model.md](https://github.com/heygrandpa/SAD_modeling_practice/blob/master/model.md)

## 评价

* 用例图完整的描述了虾米音乐搜索并添加歌单的功能
* 活动图在判断歌单时有些问题，新建歌单也需要用户为已登陆状态，在未登陆状态不能新建歌单。
* 领域模型图很好地描述了各个类的属性及相关关系
* 状态图也有些问题，在新建歌单前就需要判断用户是否为登陆状态
* 系统顺序图中第一个场景，搜索歌曲的用词不够恰当，makeSelection容易误解为选择歌曲，如果用筛选会更适合；
第二个场景添加歌曲到歌单中，selectPlaylist/newPlaylist可以用opt框架表示更能体现用户的操作

