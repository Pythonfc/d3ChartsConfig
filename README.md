稳定版：<script src="//s.thsi.cn/js/datav/charts/0.4.23/d3_charts.js"></script>    附件d3_charts.js为稳定版
最新版：<script src="//s.thsi.cn/js/datav/charts/latest/d3_charts.js"></script>    附件d3_charts_last.js为最新版    

d3_charts 组件实例：https://datav.iwencai.com/platform/config.html#/
          配置文档：https://datav.iwencai.com/platform/doc/configdoc/
		  接口文档：https://datav.iwencai.com/platform/doc/api/

获取不同组件集合的 D3Charts
目前d3charts一共提供 simple，common，hq，和完整版 四种。
每新发一个版本都会同时发这四个组件集合的包

//s.thsi.cn/js/datav/charts/0.4.23/d3_charts.simple.js
//s.thsi.cn/js/datav/charts/0.4.23/d3_charts.common.js
//s.thsi.cn/js/datav/charts/0.4.23/d3_charts.hq.js
//s.thsi.cn/js/datav/charts/0.4.23/d3_charts.js

simple 文件大小 290kb 左右。 仅包含：
/** 图表类型 **/
import './chart/arc'; //环状
import './chart/pie'; //饼图
import './chart/line'; // 折线图
import './chart/bar'; // 柱状图
import './chart/scatter'; // 散点图

