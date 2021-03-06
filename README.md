## AndroidNewsClient

本项目属于Android Material Design新闻类开源项目，新闻数据采集自CSDN资讯的HTML，用Jsoup抓取解析页面的数据。

在Android客户端，顶部采用Toolbar替代了Actionbar,指示器使用 TabLayout 完成，业界栏目采用 SwipeRefreshLayout + Listview 实现，此处自定义 SwipeRefreshLayout 实现了 Listview 上拉加载功能，新闻详情界面采用WebView实现。而 移动开发 栏目则采用SwipeRefreshLayout + RecyclerView 实现。

## Gradle

    compile 'com.android.support:appcompat-v7:24.2.1'
    compile 'com.android.support:design:24.2.1'
    compile 'com.android.support:recyclerview-v7:24.2.1'
    compile project(':NewsSplider')
    compile 'com.github.bumptech.glide:glide:3.7.0'

## Preview

ScreenShot文件夹为效果演示图（与项目代码无关）

![](https://raw.githubusercontent.com/smartbetter/AndroidNewsClient/master/ScreenShot/Screenshot0.gif)
![](https://raw.githubusercontent.com/smartbetter/AndroidNewsClient/master/ScreenShot/Screenshot1.gif)
![](https://raw.githubusercontent.com/smartbetter/AndroidNewsClient/master/ScreenShot/Screenshot2.gif)
![](https://raw.githubusercontent.com/smartbetter/AndroidNewsClient/master/ScreenShot/Screenshot3.gif)

## License
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
