# DoKit


## 介绍
对[DoKit](https://github.com/didi/DoKit)源文件进行修改，修复bug或者新增内容
当前只对iOS版本进行修改


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

## 版本新增
1、修复ios18功能列表上下拉崩溃的bug

