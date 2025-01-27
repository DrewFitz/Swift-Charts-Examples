# Swift Charts Examples
An overview of the different types of charts you can make with Swift Charts

<img width="1511" alt="image" src="https://user-images.githubusercontent.com/170948/173253882-1a80b934-a0b9-4acb-a290-a299ae3fdd7d.png">

Let's start by recreating the different chart examples that Apple gave in these session screenshots.

## Included Charts

- [x] Basis project setup
- [x] Simple Line chart
- [x] Line chart with lollipop
- [x] Heartbeat Chart
- [x] Simple Bar chart
- [x] Simple dual bar chart
- [x] Range Chart
- [x] Pyramid Chart
- [x] Area Chart
- [x] Range with Max and Min Chart
- [x] One dimensional bar
- [x] Heatmap Block Chart

## Todo
- [ ] Cumulative line Chart
- [ ] Heartbeat range Chart
- [ ] Distribution line + Point Chart
- [ ] Scatter Chart
- [ ] Funky Gradient Chart
- [ ] Other Charts
- [ ] Multi-language Support
- [ ] Make all charts accessible

See the [open issues](https://github.com/jordibruin/SwiftChartExamples/issues) if you think anything is missing from this list. You can also contact me on [Twitter](https://www.twitter.com/jordibruin) if you have any suggestions or feedback.

## Chart Types

- [Line Charts](https://github.com/jordibruin/SwiftChartExamples/tree/main/Swift%20Charts%20Examples/Charts/LineCharts)
- [Bar Charts](https://github.com/jordibruin/SwiftChartExamples/tree/main/Swift%20Charts%20Examples/Charts/BarCharts)
- [Area Charts](https://github.com/jordibruin/SwiftChartExamples/tree/main/Swift%20Charts%20Examples/Charts/AreaCharts)
- [Range Charts](https://github.com/jordibruin/SwiftChartExamples/tree/main/Swift%20Charts%20Examples/Charts/RangeCharts)
- [Heat Maps](https://github.com/jordibruin/SwiftChartExamples/tree/main/Swift%20Charts%20Examples/Charts/HeatMap)

## How to add a new chart

Each chart needs a preview chart as well as a detail view. The preview chart is used in the home screen of the app for easier navigation. Look at the Simple Chart Simple code to see what the format should be for the preview charts. On the detail view, make sure you add some customisation options in a separate section from the chart.

<img src="images/charts_wwdc_slide.png">
Source: https://developer.apple.com/videos/play/wwdc2022/10137/

# Chart Types

## Line Charts

![Line Chart](images/charts/line/singleLine.png)

![Line Chart with Lollipop](images/charts/line/singleLineLollipop.png)

![Heart Beat / ECG Chart](images/charts/line/heartBeat.png)

## Bar Charts

![One Dimensional Bar](images/charts/bar/oneDimensionalBar.png)

![Pyramid](images/charts/bar/pyramid.png)

![Single Bar](images/charts/bar/singleBar.png)

![Two Bars](images/charts/bar/twoBars.png)

## Area Charts

![Area Chart](images/charts/area/areaSimple.png)

## Other Charts

![Customizable Heat Map](images/charts/heatMap/customizeableHeatMap.png)

![Range Chart](images/charts/range/rangeSimple.png)
