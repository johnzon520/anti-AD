# anti-AD change log
#### v4.1 (未发布)
- easylist针对性优化，支持通配符匹配，提升匹配效率
- easylist列表引入白名单支持
- 优化主动探测dns查询的效率
- 待主动探测功能稳定后将开启自动push到github上

#### v4.0 (2019.12.14)

- 开始支持主动探测无效域名，进一步降低最终生成文件（位于dist目录）的体积，提升命中率
- 开始支持dnsmasq，easylist，surge等多种格式
- 分离出国内域名的精简配置(`dist/*-basic.*`)和优化后的完整配置(`dist/*-full.*`)，可以根据需求选择屏蔽等级
- 代码重构，工程化，分离class，分离工具，逻辑更清晰


#### v3.0 (2019.10.19)

- 严格匹配域名，增强生成列表的有效性
- 黑名单逻辑优化
- 重复域名剔除算法优化，进一步精简列表
- 代码bug修复


#### 3.0之前(2017年某日开始)

单个文件生成列表，主要做了更新各种靠谱来源的收集