# DoKit


## 介绍
对[DoKit](https://github.com/didi/DoKit)源文件进行优化，修复bug或者新增内容，当前只对iOS版本进行优化


## 如何导入

```
    pod 'DoraemonKit/Core', :git => "https://github.com/xuzeyu/DoKit.git", :configurations => ['Debug'] #必选
    pod 'DoraemonKit/WithGPS', :git => "https://github.com/xuzeyu/DoKit.git", :configurations => ['Debug'] #可选
    pod 'DoraemonKit/WithLoad', :git => "https://github.com/xuzeyu/DoKit.git", :configurations => ['Debug'] #可选
    pod 'DoraemonKit/WithLogger', :git => "https://github.com/xuzeyu/DoKit.git", :configurations => ['Debug'] #可选
    pod 'DoraemonKit/WithDatabase', :git => "https://github.com/xuzeyu/DoKit.git", :configurations => ['Debug'] #可选
    #pod 'DoraemonKit/WithMLeaksFinder', :git => "https://github.com/xuzeyu/DoKit.git", :configurations => ['Debug'] #可选
    pod 'DoraemonKit/WithWeex', :git => "https://github.com/xuzeyu/DoKit.git", :configurations => ['Debug'] #可选
```

## 版本修改
1、修复ios18功能列表上下拉崩溃的bug

2、修复ios18进入H5任意门扫码页面崩溃的bug

3、修改H5任意门扫码框的位置置中

4、修复ios18点击设置->功能管理崩溃问题

