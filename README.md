# jquery.jqprint-0.3.js(支持jquery1.9以上版本)
### 支持jquery1.9以上版本
------
由于jQuery从1.9版开始，移除了**$.browser**和**$.browser.version**，取而代之的是**$.support**。  
为了让jqprint这个插件能够运行在jquery1.9及其以上的版本，将js代码里面的$.browser全部替换成$.support。

###示例代码
```javascript
$.browser --> $.support
```
调用js函数的方法跟原来一样。
