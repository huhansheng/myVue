##### myVue
an example for vm implementation modal of vue

##### 原理
利用observer模式，ES5的object.definedProperty的set和get

#### 实现
1. 初始化构造（el，data，methods....）；
2. 对data属性进行观察（data改变，界面引用的值也相应改变），利用observer模式和ES5的object.definedProperty的set和get；
3. dom中属性进行解析，存储指令相应的功能；
4. 更新dom的值
