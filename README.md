Tooltipster中文文档
===========

一个 jQuery 工具提示(Tooltip)插件，作者 Caleb Jacob，遵循MIT协议。  
兼容 Mozilla Firefox, Google Chrome, IE8+ 及其他浏览器。 需要配合 jQuery 1.7+

以下是“选项”/“方法”速查列表。 详细说明参见Tooltipster中文文档： https://akimyou.github.io/tooltipster_cn/

选项
-------------------------

animation  
arrow  
arrowColor  
autoClose  
content  
contentAsHTML  
contentCloning  
debug  
delay  
minWidth  
maxWidth  
functionInit  
functionBefore  
functionReady  
functionAfter  
hideOnClick  
icon  
iconCloning  
iconDesktop  
iconTheme  
iconTouch  
interactive  
interactiveTolerance  
multiple  
offsetX  
offsetY  
onlyOne  
position  
positionTracker  
positionTrackerCallback  
restoration  
speed  
timer  
theme  
touchDevices  
trigger  
updateAnimation  

方法
-------------------------

$.fn.tooltipster('setDefaults', {})  
$(...).tooltipster('show' [, callback])  
$(...).tooltipster('hide' [, callback])  
$(...).tooltipster('disable')  
$(...).tooltipster('enable')  
$(...).tooltipster('destroy')  
$(...).tooltipster('content')  
$(...).tooltipster('content', myNewContent)  
$(...).tooltipster('option', optionName)  
$(...).tooltipster('option', optionName, optionValue)  
$(...).tooltipster('reposition')  
$(...).tooltipster('elementTooltip')  
$(...).tooltipster('elementIcon')  