# 数据可视化
* Github标签有data-visualization,dashboards
* Topic 数据可视化 https://github.com/topics/data-visualization
* Topic 可视化 https://github.com/topics/visualization
* Topic BI https://github.com/topics/business-intelligence
* just dashboard https://github.com/kantord/just-dashboard
> BI Business Intelligence (BI) in Python, OLAP
* CBoard https://github.com/TuiQiao/CBoard
> An easy to use, self-service open BI reporting and BI dashboard platform. 

* Grafana

* ELK
  * Elasticsearch https://github.com/elastic/elasticsearch
  * Logstash https://github.com/elastic/logstash
  * Kibana https://github.com/elastic/kibana
   ```
   什么是ELK
   Elasticsearch是个开源分布式搜索引擎，
   它的特点有：分布式，零配置，自动发现，索引自动分片，索引副本机制，restful风格接口，多数据源，自动搜索负载等。
   Logstash是一个完全开源的工具，他可以对你的日志进行收集、过滤，并将其存储供以后使用（如，搜索）。
   Kibana 也是一个开源和免费的工具，它Kibana可以为 Logstash 和 ElasticSearch 提供的日志分析友好的 Web 界面，
   可以帮助您汇总、分析和搜索重要数据日志
   Grafana 最早其实应该是 Kibana 3 的分支，不相信的可以去翻 Github 的提交记录，所以但凡用过 Kibana 3的人就知道，
   Grafana 的界面风格其实和 Kibana3 的风格是一致的。两者已经分道扬镳,各有千秋.
   ```
* 静态数据展示(BI数据展示)
  * Superset https://github.com/apache/incubator-superset
   ```
   Superset的Airbnb开源的数据可视化工具，目前属于Apache孵化器项目，主要用于数据分析师进行数据可视化工作
   划重点,可能是目前颜值最高的开源BI工具-Superset
   什么时候用Grafana，什么时候用Superset
   时间序列，选Grafana
   数据量很大，用Grafana
   静态的日报、报表，Superset表现力很好
   ```
  * Redash

  * metabase https://github.com/metabase/metabase
   ```
   The simplest, fastest way to get business intelligence and analytics to everyone in your company
   Superset优点：
   可视化的选项更多，比如只要定义了Date字段，可以方便的在不同时间维度做Aggregation（日/周/月）。
   在显示指标的折线图时，可以与某段时间之前的指标在一张图上做对比。
   或是在折线图上显示一个指标的rolling averages。这些在做指标分析时挺有用的。
   缺点：
   每一张用的表，都需要Sources -> Tables里定义。
   每一个用到的指标也需要定义。不适合做adhoc query的可视化。
   SQL Lab虽然可以做adhoc query的可视化，但每次都会生成一堆临时table，把Sources -> Tables里面的对象搞得很乱Dashboard不能分类，
   多了以后很难管理和查找权限系统特别复杂，而且不好用
   Redash优点：理念很简单，就是把一个SQL Query的结果可视化。
   不需要像Superset里定义一堆东西之后才能用。
   SQL Query可以定制参数。比如一个App的日活指标，我可能有时要按iOS/App切分，有时要按地域切分，或是按新老用户切分。
   在Superset的Dashboard上我要做三个图。
   Redash里我可以把Query的groupby做为一个参数，这样就可以在一张图上搞定。
   用的时候，可以在一个Dropdown List选切分的方式。
   数据源方面除了支持SQL以外，还支持ElasticSearch, Google Analytics, Google Spreadsheet, URL (JSON-Format)等。
   缺点：可视化的选项不如Superset多Superset对于非技术的人员相对友好一些。
   因为技术人员可以定义好数据源与每种指标，非技术人员接下来的各种查询都可以在Web UI上点选完成，而Redash则需要直接写SQL。
   不过实际上即使是Superset大部分运营和产品的人也只会看现成的Dashboard，很少有人会自己构建图表。
   从软件架构与代码质量上来说，Redash要明显优于Superset。
   ```
  * 大数据 https://github.com/metatron-app/metatron-discovery
  > Powerful & Easy way for big data discovery 

* Google Analytics的分析
  * https://github.com/matomo-org/matomo
  * 同上 https://github.com/usefathom/fathom
* 画图组件
  * echart https://github.com/apache/incubator-echarts
  * Ant-Design
  * vue
* TOPO拓扑
  * https://github.com/go-on-the-way/d3.js-network-topology
  * jtopo https://github.com/winyuan/jtopo_topology
  * jtopo网站 http://www.jtopo.com/index.html
* 组件
  * Timesheet https://github.com/sbstjn/timesheet.js
  > Simple JavaScript library to create HTML time sheets. Wrapped in an example project using Middleman …
  * 算法可视化 https://github.com/algorithm-visualizer/algorithm-visualizer
  * Dashboards using YAML or JSON files https://github.com/kantord/just-dashboard


