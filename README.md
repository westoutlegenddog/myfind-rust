# myfind-rust
For the assignment1

3210103818
杨朗骐

实现如下:  
1.将该代码重构到多个模块中  
2.增加新的功能，⽐如 –v/--verbose 参数输出所有遍历到的⽂件  
3.同时⽀持匹配多个正则  
4.给输出结果去重排序  
5.⽀持同时搜索多个path  
6.⽀持命令⾏彩⾊输出

测试样例和测试结果如下：  
构建输出：  
<img width="1295" alt="截屏2023-09-05 上午1 12 25" src="https://github.com/westoutlegenddog/myfind-rust/assets/103580732/3c00edb6-c814-46da-bdab-57617f01bbb7">  
测试样例：  
target/debug/myfind dir,target yz ya qwert fa dir,target/debug faz dir,target/debug/deps --verbose  
<img width="1236" alt="截屏2023-09-05 上午1 15 30" src="https://github.com/westoutlegenddog/myfind-rust/assets/103580732/56e26048-3bde-4ba8-8bd9-52569806fc23">  
前两个路径各个正则表达式的输出：  
<img width="857" alt="截屏2023-09-05 上午1 16 25" src="https://github.com/westoutlegenddog/myfind-rust/assets/103580732/53202b4a-f405-4e6d-9b41-88476afb6cfb">  
最后一个路径的遍历输出：  
<img width="700" alt="截屏2023-09-05 上午1 17 18" src="https://github.com/westoutlegenddog/myfind-rust/assets/103580732/509d33d2-ae69-4e75-a028-be13e0744260">  
合并、去重、排序的输出：  
<img width="695" alt="截屏2023-09-05 上午1 17 39" src="https://github.com/westoutlegenddog/myfind-rust/assets/103580732/2546486f-f0b3-493e-91ab-ee91fd62529c">






