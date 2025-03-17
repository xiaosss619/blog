# 副作用
指处理与外界或 Vue 实例状态交互的操作

# 使用watch和watchEffect钩子
watch：用于根据特定反应数据的变化运行副作用

watchEffect：当任何反应依赖关系发生变化时自动运行

# Hooks优缺点
提高了代码的复用性和可维护性
使组件的逻辑更加清晰、易于理解
更好地管理组件的副作用操作

# js 超过Number最大的数怎么处理
 使用BigInt

# 页面请求接口大规模并发
  滑动窗口  创建队列  防抖节流 分页加载

# 大文件上传
    
# vue3
基本类型值（String 、Nmuber 、Boolean 等）或单值对象（类似像 {count: 3} 这样只有一个属性值的对象）使用 ref
引用类型值（Object 、Array）使用 reactive

ref 是对传入数据的拷贝；toRef 是对传入数据的引用
ref 的值改变会更新视图；toRef 的值改变不会更新视图

toRef 将某个对象中的某个值转化为响应式数据
toRefs 对整个对象化为响应式数据
shallowReactive 监听了第一层属性的值，一旦发生改变，则更新视图 第二次数据视图不会发生变化
shallowRef  则是.value 的值的变化来更新视图的 

