# bus-system-front

#### 基本信息模块

> 对应需求1

:ok:

:question:使用模糊查询还是精确查询

:bulb:使用模糊查询 已更改

#### 站点查询模块

#####  全部站点查询

>  对应需求2：查询某条线路方向的全部站点信息。

接口：stationlinecontroller/stationofpreciseline

基本上:ok:

:bulb:必须指定上行/下行，查询”2路“将得不到结果。前端最好自动补全成上行/下行

##### 停靠公交线路查询

> 对应需求3：查询锦城广场站停靠的所有线路

:ok:

:bulb:只能打锦城广场 不能带站

##### 沿途站点查询

> 对应需求4：查询某条线路从某站到某站，线路的运行方向、沿路站点和运行时长

:ok:

##### 最短路径查询

> 对应需求5：查询某两个站台之间的最短路径

:ok:

##### 直达线路查询

> 对应需求6: 查询某两个站点之间是否存在直达线路

:ok:



####  班次查询模块
##### 全部班次信息查询
> 对应需求7

:ok:

:question: 是否需要调换行列

:bulb: 如果速度可接受感觉也不用调换？

##### 站点即将停靠线路
> 对应需求8

:ok:




##### 站点最近班次
> 对应需求9

:ok:

####  分析查询模块
##### 统计站台
>  对应需求10：统计停靠路线最多的站点并排序 
>
> 需求11A：统计特殊站台。
>
> 需求15：根据站台间线路数量排序站台

10 :ok:

11A :ok:

15:ok:

##### 统计线路
>  对应需求12:分组统计常规公交(包括干线、支线、城乡线、驳接线、社区线)、 快速公交(K字开头)、高峰公交(G字开头)、夜班公交(N字开头)的数量。
>
> 需求16:根据站点数量对线路进行排序
>
> 需求17:根据运行时间对线路进行排序

12 :ok:

16 :ok:

17 :ok:

##### 统计单行站

> 对应需求11B：统计某条线路单行站

11B :ok:

##### 线路间重复站点名

> 对应需求13：查询两条线路重复的站点名 

:ok:

:question:两条线路上下行不可以重复吗 

:+1:确实不可以因为按站点id匹配

##### 换乘线路

> 对应需求14：查询换乘线路

:ok:

##### 重复系数

> 对应需求18

:ok:

#### 线路管理

##### 增加线路

> 对应需求19：添加一条站点数不小于10的线路

站点信息和路线信息:ok:

班次信息还没有处理好:x:

##### 删除线路与恢复

> 对应需求20A：删除某条线路

:ok:

##### 更新线路

> 对应需求20B：线路的更新

:ok:

## 可能优化的地方
1. 智能联想:x:



