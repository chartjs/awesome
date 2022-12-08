<div align="center">
    <img width="320" src="https://www.chartjs.org/media/awesome.svg" alt="Awesome Chart.js">
</div>

# Awesome Chart.js [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated list of awesome things related to [Chart.js](https://www.chartjs.org)

- [Resources](#resources)
- [Charts](#charts)
- [Plugins](#plugins)
- [Adapters](#adapters)
- [Integrations](#integrations)
- [Tools](#tools)

## Resources

- [Official Guide](https://chartjs.org/docs) | The user guide and documentation site.

## Charts

  Name | Description | Chart.js v2 | Chart.js v3
  ---- | ----------- | :--: | :--:
  [bar-funnel](https://github.com/chartjs/Chart.BarFunnel.js) | Adds bar funnel chart type | ✔ |
  [boxplot](https://github.com/sgratzl/chartjs-chart-boxplot) | Adds boxplot and violin plot chart type | ✔ | ✔
  [error-bars](https://github.com/sgratzl/chartjs-chart-error-bars) | Adds diverse error bar variants of standard chart types | ✔ | ✔
  [financial](https://github.com/chartjs/chartjs-chart-financial) | Adds financial chart types such as a candlestick | ✔ | ✔
  [geo](https://github.com/sgratzl/chartjs-chart-geo) | Adds geographic map chart types such as choropleth and bubble map | ✔ | ✔
  [graph](https://github.com/sgratzl/chartjs-chart-graph) | Adds graph chart types such as a force directed graph | ✔ | ✔
  [matrix](https://github.com/kurkle/chartjs-chart-matrix) | Adds matrix chart type | ✔ | ✔
  [pcp](https://github.com/sgratzl/chartjs-chart-pcp) | Adds parallel coordinates plot chart type | ✔ | ✔
  [sankey](https://github.com/kurkle/chartjs-chart-sankey) | Adds sankey diagram chart type | | ✔
  [smith](https://github.com/chartjs/Chart.smith.js) | Adds smith chart type | ✔ |
  [stacked100](https://github.com/y-takey/chartjs-plugin-stacked100) | Draws 100% stacked bar chart | ✔ | ✔
  [treemap](https://github.com/kurkle/chartjs-chart-treemap) | Adds treemap chart type | ✔ | ✔
  [venn](https://github.com/upsetjs/chartjs-chart-venn) | Adds venn and euler chart type | | ✔
  [word-cloud](https://github.com/sgratzl/chartjs-chart-wordcloud) | Adds word-cloud chart type | | ✔

## Plugins

### Styling

  Name | Description | Chart.js v2 | Chart.js v3
  ---- | ----------- | :--: | :--:
  [autocolors](https://github.com/kurkle/chartjs-plugin-autocolors) | Automatic color generation | | ✔
  [colorschemes](https://github.com/nagix/chartjs-plugin-colorschemes) | Enables automatic coloring using predefined color schemes | ✔ | 
  [gradient](https://github.com/kurkle/chartjs-plugin-gradient) | Easy gradients | | ✔
  [rough](https://github.com/nagix/chartjs-plugin-rough) | Draws charts in a sketchy, hand-drawn-like style using Rough.js | ✔ |
  [style](https://github.com/nagix/chartjs-plugin-style) | Provides styling options such as shadow, bevel, glow or overlay effects | ✔ |

### Features

  Support | Name | Description
  -- | -- | --
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [annotation](https://github.com/chartjs/chartjs-plugin-annotation) | Draws lines and boxes on the chart area
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [crosshair](https://github.com/abelheinsbroek/chartjs-plugin-crosshair) | Adds a data crosshair to line and scatter charts
  <nobr>![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen)</nobr> | [datalabels](https://github.com/chartjs/chartjs-plugin-datalabels) | Displays labels on data for any type of charts
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [hierarchical](https://github.com/sgratzl/chartjs-plugin-hierarchical) | Adds support for hierarchical categorical scales that can be collapsed, expanded, and focused
  ![](https://img.shields.io/badge/-v2-yellow) | [regression](https://github.com/pomgui/chartjs-plugin-regression) | Calculate and draw statistical linear, exponential, power, logarithmic, and polynomial regressions (trend lines)
  ![](https://img.shields.io/badge/-v2-yellow) | [waterfall](https://github.com/everestate/chartjs-plugin-waterfall) | Enables easy use of waterfall charts

### Interactions

  Support | Name | Description
  -- | -- | --
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [deferred](https://github.com/chartjs/chartjs-plugin-deferred) | Defers initial chart update until chart scrolls into viewport
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [dragdata](https://github.com/chrispahm/chartjs-plugin-dragdata) | Lets users drag data points on the chart
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [zoom](https://github.com/chartjs/chartjs-plugin-zoom) | Enables zooming and panning on charts

### Data Sources

  Support | Name | Description
  -- | -- | --
  ![](https://img.shields.io/badge/-v2-yellow) | [datasource-prometheus](https://github.com/samber/chartjs-plugin-datasource-prometheus) | Displays time-series from Prometheus
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [streaming](https://github.com/nagix/chartjs-plugin-streaming) | Adds support for live streaming data

In addition, many plugins can be found on the [npm registry](https://www.npmjs.com/search?q=chartjs-plugin-).

## Adapters

  Support | Name | Description
  -- | -- | --
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [date-fns](https://github.com/chartjs/chartjs-adapter-date-fns) | date-fns adapter
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [luxon](https://github.com/chartjs/chartjs-adapter-luxon) | Luxon adapter
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [moment](https://github.com/chartjs/chartjs-adapter-moment) | Moment.js adapter

## Integrations

### JavaScript

  Support | Name | Description
  -- | -- | --
  ![](https://img.shields.io/badge/-v2-yellow) | [ember-cli-chart](https://github.com/aomran/ember-cli-chart) | Ember CLI
  ![](https://img.shields.io/badge/-v2-yellow) | [lwcc](https://github.com/SalesforceLabs/LightningWebChartJS) | Lightning Web Component
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [ng2-charts](https://github.com/valor-software/ng2-charts) | Angular v2+
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [omi-chart](https://github.com/Tencent/omi/tree/master/components/chart) | Omi
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | React
  ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [svelte-chartjs](https://github.com/SauravKanchan/svelte-chartjs) | Svelte
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) ![](https://img.shields.io/badge/-v4-brightgreen) | [vue-chartjs](https://github.com/apertureless/vue-chartjs/) | Vue.js

### Others

  Support | Name | Description
  -- | -- | --
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [charba](https://github.com/pepstock-org/Charba) | GWT/J2CL
  ![](https://img.shields.io/badge/-v2-yellow) | [chart.java](https://github.com/mdewilde/chart/) | Java
  ![](https://img.shields.io/badge/-v2-yellow) | [chartjs-ocaml](https://github.com/monstasat/chartjs-ocaml) | OCaml
  ![](https://img.shields.io/badge/-v2-yellow) | [chartjs-ror](https://github.com/airblade/chartjs-ror) | Ruby on Rails
  ![](https://img.shields.io/badge/-v3-green) | [chart-js-rs](https://github.com/Billy-Sheppard/chart-js-rs) | Chart.js types API in Rust (WIP in Alpha/incomplete)
  ![](https://img.shields.io/badge/-v2-yellow) | [django-chartjs](https://github.com/peopledoc/django-chartjs) | Django
  &nbsp; | [figma](https://www.figma.com/community/file/1111335120507995139) | Design components
  ![](https://img.shields.io/badge/-v2-yellow) | [ipychart](https://github.com/nicohlr/ipychart) | Jupyter Notebook
  ![](https://img.shields.io/badge/-v2-yellow) | [laravel-chartjs](https://github.com/fxcosta/laravel-chartjs) | Laravel
  ![](https://img.shields.io/badge/-v2-yellow) | [liquify](https://github.com/sakos95/liquify) | Fast, multi-threaded visualization of stream data with Angular
  ![](https://img.shields.io/badge/-v2-yellow) | [nova-chartjs](https://github.com/coroo/nova-chartjs) | Laravel Nova
  ![](https://img.shields.io/badge/-v2-yellow) ![](https://img.shields.io/badge/-v3-green) | [quickchart](https://github.com/typpo/quickchart) | Web API for static charts
  ![](https://img.shields.io/badge/-v2-yellow) | [wicked-charts](https://github.com/adessoAG/wicked-charts)

## Tools

  Support | Name | Description
  -- | -- | --
  ![](https://img.shields.io/badge/-v3-green) | [xhub](https://github.com/nschloe/xhub) | Browser extension for Chart.js (and more) on GitHub pages
