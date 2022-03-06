黑马程序员作业-移动端B站首页



![image-20220306225717625](https://s2.loli.net/2022/03/06/lJWKLSmtIwXPc2k.png)

### 总结：

1. 固定区域的z-index记得加。

1. 固定定位的时候需要给宽，因为固定定位脱标。

2. 两行标题剩余换行：

	```css
   .ellipsis-2 {
     overflow: hidden;
     text-overflow: ellipsis;
     display: -webkit-box;
     -webkit-line-clamp: 2;
     -webkit-box-orient: vertical;
   }
   ```
   

3. ![image-20220306225924667](https://s2.loli.net/2022/03/06/vcoeQI7LMVTGgAK.png)这个地方的标签名字是tab，实际开发时，视频页的数量要与tab的数量对应。