##  chrome 开发技巧

###  chrome 小技巧

+  hover样式修改：  元素鼠标右键hover,acitve等  

+  元素状态改变监控  (结构，样式改变)break on  ~~

+  查看元素最终的样式  computed

+  元素事件监听  event listeners
   
+  调试js的 call stack: resource->断点

+  编辑文件并同步到本地 resource > Filesystem

+  监控并统计没有使用到的脚本与样式 more tools > Coverage

+  页面动车监控与调试 more tools > animation

+  网络条件与user-agent设置 more tools > network conditions

+  调试android 设备  more tools > remote devices

+  阻止请求某些资源  more tools > request blocking

+  对站点所有资源进行搜索  more tools > search

+  模拟传感器数据(地理位置，手机旋转方向,陀螺仪信息等)  more tools > Sensors 


###  性能分析方法

   - FPS 概念
   - Performace > cup slowdown
   - 快捷键 WASD
   - call tree 查看源码性能
   
###  内存监控的原理与方法

#### 内存模型---引用类型 与 值类型
``` 
  //demo01.js
  var a = 20
  var b = a 
  b = 30
  // a = ?   // 20    
  // a, b  在内存中
  
  //demo02.js
  var m = {a:10, b: 20}
  var n = m;
  n.a = 15;
  // m.a = ?  // 15
  //m , n在内存，　m 与 n 指向同一个Heap ({a, b} )中
```
#### JS 内存生命周期

  - 内存分配
       * 全局变量与局部变量
       * 内存回收
       * 注意spa程序的内存泄漏 
  
  - 内存泄漏
  
  - 内存膨胀
  
### manifest： 描述站点信息的json文件
      - 设置主题颜色 ， 启动样式， 自定义显示类型 等
      - 查看看manifest: applictaion > manifest 

### service workers
    - PWA
      
  












