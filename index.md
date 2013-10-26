---
title       : Life Satisfaction
subtitle    : Preliminary Results
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
hitheme: solarized_light
assets:
  css:
  - "http://fonts.googleapis.com/css?family=Raleway:300"
  - "http://fonts.googleapis.com/css?family=Oxygen"
--- 
<style>
iframe{
  height:450px;
  width:900px;
  margin:auto auto;
}

body{
  font-family: 'Raleway', sans-serif;
}


h1,h2,h3,h4 {
  font-family: 'Raleway', sans-serif;
}

</style>




















### Data and Model

- Behavioral Risk Factor Surveillance System, 2005-2010.
- Total Sample Size: 1,855,548 respondents
- Dependent Measure: Life Satisfaction (1/0)
- Independent Measures: Income, Number of Children, Marital Status, Race, Gender, Age, Gender*Age
- Model: Hierarchical Linear Model with State interactions


---

### Predicted Life Satisfaction by (Age,Gender,State)

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="960px" height="528px" viewBox="0 0 960 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-10-25 17:38:36"/>
    <gridsvg:argument name="name" value="erase_me.svg"/>
    <gridsvg:argument name="exportCoords" value="none"/>
    <gridsvg:argument name="exportMappings" value="none"/>
    <gridsvg:argument name="exportJS" value="none"/>
    <gridsvg:argument name="res" value="96"/>
    <gridsvg:argument name="prefix" value=""/>
    <gridsvg:argument name="addClasses" value="TRUE"/>
    <gridsvg:argument name="indent" value="TRUE"/>
    <gridsvg:argument name="htmlWrapper" value="FALSE"/>
    <gridsvg:argument name="usePaths" value="vpPaths"/>
    <gridsvg:argument name="uniqueNames" value="TRUE"/>
    <gridsvg:separator name="id.sep" value="."/>
    <gridsvg:separator name="gPath.sep" value="::"/>
    <gridsvg:separator name="vpPath.sep" value="::"/>
  </metadata>
  <g transform="translate(0, 528) scale(1, -1)">
    <g id="gridSVG" fill="none" stroke="rgb(0,0,0)" stroke-dasharray="none" stroke-width="1" font-size="16" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" opacity="1" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-opacity="1" fill-opacity="0" font-weight="normal" font-style="normal">
      <defs>
        <symbol id="gridSVG.pch16" viewBox="-5 -5 10 10" overflow="visible">
          <circle cx="0" cy="0" r="3.75"/>
        </symbol>
      </defs>
      <g id="layout.1" class="pushedvp viewport">
        <g id="GRID.gTableParent.53.1" class="gTableParent gTree grob gDesc">
          <defs>
            <clipPath id="layout::background.1-5-6-1.1.clipPath">
              <rect x="0" y="0" width="960" height="528" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::background.1-5-6-1.1" clip-path="url(#layout::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
            <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
              <rect id="background.1-5-6-1.1.1" x="0" y="0" width="960" height="528" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
            </g>
          </g>
          <g id="layout::spacer.4-3-4-3.1" class="pushedvp viewport"/>
          <defs>
            <clipPath id="layout::panel.3-4-3-4.1.clipPath">
              <rect x="59.65" y="52.65" width="881.15" height="456.15" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::panel.3-4-3-4.1" clip-path="url(#layout::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
            <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
              <g id="grill.gTree.31.1" class="gTree grob gDesc">
                <g id="panel.background.rect.24.1" class="rect grob gDesc">
                  <rect id="panel.background.rect.24.1.1" x="59.65" y="52.65" width="881.15" height="456.15" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                </g>
                <g id="panel.grid.minor.y.polyline.26.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.minor.y.polyline.26.1.1" points="59.65,119.85 940.8,119.85" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.26.1.2" points="59.65,256.81 940.8,256.81" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.26.1.3" points="59.65,393.77 940.8,393.77" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.y.polyline.28.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.y.polyline.28.1.1" points="59.65,188.33 940.8,188.33" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.28.1.2" points="59.65,325.29 940.8,325.29" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.28.1.3" points="59.65,462.25 940.8,462.25" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.x.polyline.30.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.x.polyline.30.1.1" points="94.43,52.65 94.43,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.2" points="152.4,52.65 152.4,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.3" points="210.37,52.65 210.37,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.4" points="268.34,52.65 268.34,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.5" points="326.31,52.65 326.31,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.6" points="384.28,52.65 384.28,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.7" points="442.25,52.65 442.25,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.8" points="500.22,52.65 500.22,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.9" points="558.19,52.65 558.19,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.10" points="616.17,52.65 616.17,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.11" points="674.14,52.65 674.14,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.12" points="732.11,52.65 732.11,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.13" points="790.08,52.65 790.08,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.14" points="848.05,52.65 848.05,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.30.1.15" points="906.02,52.65 906.02,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
              </g>
              <g id="GRID.polyline.11.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.11.1.1" points="94.43,325.42 152.4,269.33 210.37,228.73 268.34,179.98 326.31,174.06 384.28,155.81 442.25,163.13 500.22,187.68 558.19,274.42 616.17,327.68 674.14,363.77 732.11,343.67 790.08,339.05 848.05,330.36 906.02,371.69" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.2" points="94.43,327.08 152.4,265.08 210.37,231.03 268.34,188.9 326.31,167.58 384.28,150.08 442.25,164.06 500.22,203.11 558.19,283.65 616.17,342 674.14,372.52 732.11,346.75 790.08,336.4 848.05,339 906.02,375.5" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.3" points="94.43,300.44 152.4,256.3 210.37,201.16 268.34,161.53 326.31,150.84 384.28,129.06 442.25,136.97 500.22,166.46 558.19,238.9 616.17,302.84 674.14,324.04 732.11,316.86 790.08,295.06 848.05,287.13 906.02,343.54" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.4" points="94.43,324.01 152.4,273.7 210.37,229.68 268.34,189.74 326.31,182.91 384.28,155.22 442.25,161.8 500.22,187.38 558.19,270.77 616.17,344.08 674.14,374.72 732.11,364.65 790.08,347.41 848.05,337.91 906.02,377.28" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.5" points="94.43,324.5 152.4,265.19 210.37,225.75 268.34,185.64 326.31,172.82 384.28,167.89 442.25,160.3 500.22,190.98 558.19,279.17 616.17,335.65 674.14,358.1 732.11,345.77 790.08,338.18 848.05,318.46 906.02,371.69" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.6" points="94.43,354.67 152.4,308.02 210.37,262.09 268.34,219.84 326.31,195.36 384.28,190.43 442.25,200.77 500.22,236.74 558.19,311.83 616.17,365.57 674.14,387.17 732.11,378.62 790.08,360.11 848.05,363.01 906.02,404.76" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.7" points="94.43,321.97 152.4,253.05 210.37,218.3 268.34,178.5 326.31,152.99 384.28,142.6 442.25,149.37 500.22,179.29 558.19,260.98 616.17,321.33 674.14,338.19 732.11,326.81 790.08,316.51 848.05,308.31 906.02,357.82" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.8" points="94.43,263.71 152.4,218.29 210.37,173.2 268.34,129.5 326.31,111.77 384.28,99.29 442.25,100.7 500.22,138.79 558.19,214.11 616.17,278.18 674.14,306.89 732.11,293.4 790.08,279.77 848.05,269.34 906.02,315.75" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.9" points="94.43,242.01 152.4,194.09 210.37,145.17 268.34,117.96 326.31,86.81 384.28,74.02 442.25,83.54 500.22,121.31 558.19,200.26 616.17,269.47 674.14,288.4 732.11,278.13 790.08,262.54 848.05,259.81 906.02,298.15" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.10" points="94.43,276.56 152.4,224.4 210.37,182.5 268.34,135.22 326.31,132.01 384.28,111.77 442.25,107.38 500.22,149.93 558.19,225.27 616.17,295.18 674.14,312.6 732.11,306.09 790.08,286.12 848.05,291.18 906.02,327.27" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.11" points="94.43,323.35 152.4,275.5 210.37,226.42 268.34,188.41 326.31,165.25 384.28,153.69 442.25,158.24 500.22,193.47 558.19,267.51 616.17,335.2 674.14,357.47 732.11,345.33 790.08,332.37 848.05,326.92 906.02,370.34" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.12" points="94.43,290.81 152.4,232.84 210.37,196.81 268.34,150.86 326.31,131.66 384.28,108.7 442.25,110.65 500.22,150.36 558.19,215.57 616.17,289.41 674.14,322.67 732.11,305.49 790.08,287.12 848.05,294.56 906.02,330.87" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.13" points="94.43,297.07 152.4,236.91 210.37,199.15 268.34,155.86 326.31,143.75 384.28,115.11 442.25,117.91 500.22,155.31 558.19,231.67 616.17,294.4 674.14,319.44 732.11,314.5 790.08,302.38 848.05,300.13 906.02,337.79" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.14" points="94.43,382.36 152.4,325.66 210.37,276.06 268.34,248.44 326.31,221.11 384.28,213.24 442.25,214.12 500.22,254.73 558.19,320.3 616.17,379.12 674.14,415.22 732.11,399.36 790.08,393.21 848.05,388.13 906.02,426.19" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.15" points="94.43,304.35 152.4,239.13 210.37,199.69 268.34,161.03 326.31,155.95 384.28,143.63 442.25,146.01 500.22,175.63 558.19,240.79 616.17,308.72 674.14,335.5 732.11,329.14 790.08,315.53 848.05,301.08 906.02,350.11" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.16" points="94.43,279.88 152.4,225.58 210.37,183.73 268.34,150.26 326.31,151.75 384.28,112.81 442.25,114.44 500.22,161.91 558.19,243.43 616.17,299.08 674.14,325.98 732.11,312.91 790.08,295.96 848.05,280.85 906.02,333.97" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.17" points="94.43,261.98 152.4,214.34 210.37,178.84 268.34,133.34 326.31,113.44 384.28,84.55 442.25,105.11 500.22,119.79 558.19,211.31 616.17,276.29 674.14,300.85 732.11,292.75 790.08,288.39 848.05,276.78 906.02,314.81" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.18" points="94.43,256.86 152.4,197.4 210.37,154.14 268.34,115.88 326.31,88.62 384.28,82.73 442.25,87.87 500.22,132.71 558.19,221.7 616.17,287.37 674.14,313.57 732.11,298.86 790.08,275.04 848.05,277.1 906.02,309.28" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.19" points="94.43,298.28 152.4,239.1 210.37,202.19 268.34,151.9 326.31,146.52 384.28,130.46 442.25,139.1 500.22,161.13 558.19,243.31 616.17,307.63 674.14,332.58 732.11,318.04 790.08,305.75 848.05,305.16 906.02,344.53" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.20" points="94.43,348.22 152.4,287.18 210.37,249.3 268.34,211.72 326.31,205.27 384.28,182.09 442.25,190.06 500.22,222.18 558.19,299.47 616.17,354.46 674.14,383.91 732.11,367.44 790.08,361.34 848.05,357.41 906.02,396.89" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.21" points="94.43,277.38 152.4,212.58 210.37,180.94 268.34,130.7 326.31,117.59 384.28,101.55 442.25,101.11 500.22,135.95 558.19,227.93 616.17,274.71 674.14,308.86 732.11,299.64 790.08,283.02 848.05,276.65 906.02,319.5" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.22" points="94.43,326.88 152.4,270.34 210.37,239.69 268.34,193.77 326.31,174.72 384.28,155.42 442.25,176.31 500.22,197.33 558.19,268.99 616.17,326.81 674.14,349.4 732.11,349.42 790.08,328.11 848.05,321.88 906.02,372.96" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.23" points="94.43,262.22 152.4,219.54 210.37,166.63 268.34,110.97 326.31,111.75 384.28,92.71 442.25,93.55 500.22,123.49 558.19,188.96 616.17,260.22 674.14,275.31 732.11,262.01 790.08,248.62 848.05,257.19 906.02,301.71" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.24" points="94.43,278.37 152.4,217.12 210.37,174.22 268.34,138.76 326.31,123.58 384.28,103.37 442.25,119.39 500.22,155.14 558.19,240.03 616.17,287.55 674.14,304.47 732.11,296.88 790.08,290.74 848.05,285.62 906.02,325.75" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.25" points="94.43,279.48 152.4,217.95 210.37,191.22 268.34,136.82 326.31,135.79 384.28,122.74 442.25,130.89 500.22,155.28 558.19,233.85 616.17,300.67 674.14,324.09 732.11,302.82 790.08,289.38 848.05,286.5 906.02,332.25" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.26" points="94.43,258.71 152.4,201.39 210.37,178.2 268.34,141.93 326.31,116.91 384.28,99.71 442.25,91.65 500.22,131.91 558.19,210.1 616.17,261.29 674.14,300.44 732.11,288.31 790.08,272.1 848.05,258.68 906.02,311.05" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.27" points="94.43,323.45 152.4,255 210.37,221.97 268.34,182.93 326.31,164.93 384.28,159.59 442.25,160.58 500.22,184.82 558.19,257.61 616.17,321.71 674.14,340.7 732.11,329.22 790.08,317.21 848.05,316.8 906.02,362.5" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.28" points="94.43,244.87 152.4,184.51 210.37,158.15 268.34,105.67 326.31,98.56 384.28,73.38 442.25,74.71 500.22,106.81 558.19,194.5 616.17,242.32 674.14,279.86 732.11,253.1 790.08,248.77 848.05,239.13 906.02,289.73" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.29" points="94.43,313.18 152.4,253.79 210.37,221.73 268.34,187.36 326.31,154.93 384.28,146.9 442.25,142.64 500.22,175.18 558.19,263.47 616.17,335.62 674.14,349.73 732.11,331.15 790.08,316.5 848.05,320.97 906.02,361.01" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.30" points="94.43,280.63 152.4,227.31 210.37,184.36 268.34,133.05 326.31,120.59 384.28,105.52 442.25,114.79 500.22,139.12 558.19,219.29 616.17,276.79 674.14,294.37 732.11,282.69 790.08,263.18 848.05,272.01 906.02,318.59" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.31" points="94.43,258.33 152.4,204.11 210.37,154.49 268.34,125.05 326.31,104.85 384.28,81.95 442.25,93.04 500.22,122.8 558.19,212.67 616.17,273.86 674.14,302.42 732.11,299.25 790.08,285.1 848.05,268.22 906.02,309.54" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.32" points="94.43,336 152.4,286.17 210.37,235.82 268.34,201.24 326.31,193.46 384.28,167.63 442.25,163.51 500.22,205.71 558.19,279.09 616.17,353.88 674.14,373.41 732.11,368.81 790.08,345.73 848.05,338.21 906.02,384.54" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.33" points="94.43,289.61 152.4,242.67 210.37,186.9 268.34,161.75 326.31,141.67 384.28,120.93 442.25,119.83 500.22,147.8 558.19,233.49 616.17,295.49 674.14,317.73 732.11,304.13 790.08,295.73 848.05,288.87 906.02,335.48" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.34" points="94.43,309.78 152.4,247.34 210.37,217.16 268.34,176.04 326.31,156.57 384.28,141.66 442.25,143.18 500.22,182.17 558.19,262.87 616.17,326.84 674.14,337.38 732.11,336.5 790.08,316.94 848.05,319.5 906.02,358.19" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.35" points="94.43,274.66 152.4,210.2 210.37,175.37 268.34,136.21 326.31,115.56 384.28,98.02 442.25,98.67 500.22,124.73 558.19,227.63 616.17,275.05 674.14,319.83 732.11,294.13 790.08,270.03 848.05,266.57 906.02,316.41" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.36" points="94.43,254.32 152.4,199.27 210.37,163.85 268.34,120.77 326.31,108.21 384.28,92.35 442.25,80.99 500.22,122.86 558.19,197.66 616.17,266.19 674.14,293.52 732.11,280.84 790.08,270.01 848.05,265.31 906.02,304.66" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.37" points="94.43,332.54 152.4,284.73 210.37,235.37 268.34,200.19 326.31,176.71 384.28,170.77 442.25,176.98 500.22,213.45 558.19,303.22 616.17,349.29 674.14,380.2 732.11,366.31 790.08,353.99 848.05,347.69 906.02,387.82" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.38" points="94.43,284.69 152.4,228.98 210.37,188.86 268.34,140.68 326.31,116.12 384.28,102.16 442.25,103.78 500.22,148.33 558.19,210.48 616.17,267.35 674.14,293.04 732.11,287.08 790.08,265.12 848.05,273.56 906.02,318.56" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.39" points="94.43,343.74 152.4,293.98 210.37,244.47 268.34,200.91 326.31,186.15 384.28,170.4 442.25,174.3 500.22,202.22 558.19,281.55 616.17,342 674.14,371.9 732.11,354.8 790.08,348.64 848.05,346.76 906.02,386.08" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.40" points="94.43,311.33 152.4,258.03 210.37,214.42 268.34,177.66 326.31,167.55 384.28,148.68 442.25,141.5 500.22,185.38 558.19,252.31 616.17,312.41 674.14,342.66 732.11,330.46 790.08,324.27 848.05,313.65 906.02,358.75" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.41" points="94.43,311.11 152.4,262.14 210.37,215.59 268.34,156.87 326.31,137.72 384.28,119.9 442.25,127.86 500.22,161.33 558.19,233.7 616.17,296.94 674.14,322.51 732.11,307.43 790.08,297.21 848.05,293.35 906.02,342.29" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.42" points="94.43,323.36 152.4,273.07 210.37,230.65 268.34,189.25 326.31,169.36 384.28,154.03 442.25,160.04 500.22,191.27 558.19,275.8 616.17,319.65 674.14,358.4 732.11,343.43 790.08,334.98 848.05,329.41 906.02,370.34" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.43" points="94.43,297.23 152.4,244.41 210.37,212.37 268.34,167.88 326.31,146.44 384.28,140.33 442.25,148.24 500.22,172.17 558.19,246.66 616.17,302.66 674.14,337.45 732.11,324.91 790.08,310.96 848.05,304.11 906.02,349.66" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.44" points="94.43,310.57 152.4,245.35 210.37,215.99 268.34,168.75 326.31,151.78 384.28,145.66 442.25,137.62 500.22,177.68 558.19,257.8 616.17,325.52 674.14,342.92 732.11,328.86 790.08,310.78 848.05,306.45 906.02,354.52" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.45" points="94.43,285.64 152.4,238.06 210.37,198.21 268.34,153.05 326.31,139.21 384.28,118.44 442.25,126.76 500.22,172.77 558.19,257.68 616.17,317.4 674.14,332.9 732.11,333.56 790.08,313.57 848.05,300.35 906.02,344.87" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.46" points="94.43,310.15 152.4,257.13 210.37,210.59 268.34,185.95 326.31,152.72 384.28,141.08 442.25,141.83 500.22,178.08 558.19,257.55 616.17,314.13 674.14,340.13 732.11,345.65 790.08,323.8 848.05,323.86 906.02,358.93" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.47" points="94.43,286.43 152.4,223.43 210.37,181.14 268.34,140.66 326.31,126.84 384.28,117.92 442.25,117.59 500.22,149.5 558.19,253.45 616.17,287.92 674.14,317.92 732.11,316.65 790.08,300.59 848.05,291.69 906.02,332.38" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.48" points="94.43,318.96 152.4,260.26 210.37,221.87 268.34,171.15 326.31,167.1 384.28,152.2 442.25,155.65 500.22,182.06 558.19,260.97 616.17,321.81 674.14,343.97 732.11,327.86 790.08,314.94 848.05,316.38 906.02,361.25" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.49" points="94.43,272.24 152.4,225.65 210.37,185.03 268.34,148.01 326.31,137.06 384.28,111.9 442.25,121.98 500.22,146.95 558.19,223.8 616.17,307.21 674.14,327.7 732.11,305.23 790.08,304.85 848.05,290.15 906.02,331.6" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.50" points="94.43,291.7 152.4,257.64 210.37,218.24 268.34,169.14 326.31,159.62 384.28,139.63 442.25,131.83 500.22,178.73 558.19,247.74 616.17,326.23 674.14,353.19 732.11,336.46 790.08,319.76 848.05,313.36 906.02,356.03" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.51" points="94.43,246.59 152.4,197.41 210.37,146.51 268.34,118.53 326.31,93.05 384.28,79.78 442.25,84.6 500.22,111.48 558.19,192.7 616.17,264.36 674.14,291.4 732.11,267.42 790.08,252.36 848.05,247.45 906.02,296.15" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.52" points="94.43,297.99 152.4,243.15 210.37,202.63 268.34,161.3 326.31,145.44 384.28,129.01 442.25,132.68 500.22,166.11 558.19,245.65 616.17,306.81 674.14,332.58 732.11,320.38 790.08,306.57 848.05,301.82 906.02,345.32" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
              </g>
              <g id="GRID.polyline.12.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.12.1.1" points="94.43,297.99 152.4,243.15 210.37,202.63 268.34,161.3 326.31,145.44 384.28,129.01 442.25,132.68 500.22,166.11 558.19,245.65 616.17,306.81 674.14,332.58 732.11,320.38 790.08,306.57 848.05,301.82 906.02,345.32" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
              </g>
              <g id="geom_point.points.14.1" class="points grob gDesc">
                <use id="geom_point.points.14.1.1" xlink:href="#gridSVG.pch16" x="906.02" y="345.32" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.2" xlink:href="#gridSVG.pch16" x="94.43" y="297.99" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.3" xlink:href="#gridSVG.pch16" x="152.4" y="243.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.4" xlink:href="#gridSVG.pch16" x="210.37" y="202.63" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.5" xlink:href="#gridSVG.pch16" x="268.34" y="161.3" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.6" xlink:href="#gridSVG.pch16" x="326.31" y="145.44" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.7" xlink:href="#gridSVG.pch16" x="384.28" y="129.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.8" xlink:href="#gridSVG.pch16" x="442.25" y="132.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.9" xlink:href="#gridSVG.pch16" x="500.22" y="166.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.10" xlink:href="#gridSVG.pch16" x="558.19" y="245.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.11" xlink:href="#gridSVG.pch16" x="616.17" y="306.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.12" xlink:href="#gridSVG.pch16" x="674.14" y="332.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.13" xlink:href="#gridSVG.pch16" x="732.11" y="320.38" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.14" xlink:href="#gridSVG.pch16" x="790.08" y="306.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.15" xlink:href="#gridSVG.pch16" x="848.05" y="301.82" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
              </g>
              <g id="GRID.polyline.15.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.15.1.1" points="94.43,346.99 152.4,304.28 210.37,266.17 268.34,235.38 326.31,231.19 384.28,226.71 442.25,240.25 500.22,259.36 558.19,337.03 616.17,380.69 674.14,413.31 732.11,408.96 790.08,433.51 848.05,430.11 906.02,347.9" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.2" points="94.43,348.07 152.4,299.24 210.37,268.41 268.34,245.04 326.31,224.95 384.28,221.04 442.25,240.81 500.22,275.37 558.19,346.08 616.17,395 674.14,421.66 732.11,411.93 790.08,430.25 848.05,438.85 906.02,339.01" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.3" points="94.43,321.84 152.4,291.92 210.37,238.08 268.34,218.07 326.31,208.53 384.28,200.47 442.25,214.65 500.22,239.1 558.19,301.11 616.17,356.2 674.14,372.85 732.11,382.26 790.08,387.99 848.05,385.64 906.02,330.62" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.4" points="94.43,345.6 152.4,308.39 210.37,267.08 268.34,245.64 326.31,241.04 384.28,226.84 442.25,238.2 500.22,258.62 558.19,332.86 616.17,397.42 674.14,423.46 732.11,430.48 790.08,442.21 848.05,436.83 906.02,357.64" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.5" points="94.43,346.04 152.4,300.23 210.37,263.3 268.34,241.13 326.31,229.64 384.28,240.25 442.25,237.87 500.22,263.44 558.19,341.79 616.17,388.67 674.14,406.3 732.11,410.97 790.08,431.91 848.05,417.6 906.02,347.97" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.6" points="94.43,375.6 152.4,343.56 210.37,299.77 268.34,275.65 326.31,252.1 384.28,262.21 442.25,278.36 500.22,309.71 558.19,373.87 616.17,417.99 674.14,435.64 732.11,444.51 790.08,453.97 848.05,462.41 906.02,387.25" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.7" points="94.43,343.93 152.4,288.45 210.37,255.56 268.34,235.04 326.31,210.09 384.28,213.72 442.25,227.18 500.22,252.23 558.19,322.57 616.17,374.5 674.14,386.81 732.11,391.92 790.08,410.74 848.05,407.32 906.02,345.13" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.8" points="94.43,284.77 152.4,253.42 210.37,210.67 268.34,185.68 326.31,169.23 384.28,170.51 442.25,177.5 500.22,211.22 558.19,276.48 616.17,331.47 674.14,356.06 732.11,358.32 790.08,373.91 848.05,368.26 906.02,292.71" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.9" points="94.43,262.87 152.4,229.08 210.37,182.08 268.34,173.99 326.31,143.57 384.28,145.14 442.25,160.62 500.22,194.5 558.19,262.07 616.17,322.7 674.14,337.66 732.11,343.88 790.08,356.79 848.05,359.32 906.02,279.58" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.10" points="94.43,297.29 152.4,259.18 210.37,220.57 268.34,191.31 326.31,189.27 384.28,183.6 442.25,184.77 500.22,222.4 558.19,287.12 616.17,348.88 674.14,361.24 732.11,371.16 790.08,380.03 848.05,391.04 906.02,316.1" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.11" points="94.43,344.47 152.4,310.75 210.37,263.7 268.34,244.56 326.31,222.46 384.28,224.85 442.25,235.42 500.22,266.17 558.19,329.16 616.17,388.77 674.14,406.26 732.11,410.8 790.08,426.59 848.05,426.23 906.02,348.43" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.12" points="94.43,312.52 152.4,268.11 210.37,234.78 268.34,207.26 326.31,188.47 384.28,180.75 442.25,186.95 500.22,222.49 558.19,277.28 616.17,342.39 674.14,371.29 732.11,371.05 790.08,380.89 848.05,394.29 906.02,316.21" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.13" points="94.43,318.79 152.4,272.26 210.37,236.8 268.34,212.84 326.31,201.19 384.28,185.99 442.25,194.6 500.22,227.74 558.19,292.88 616.17,347.42 674.14,367.25 732.11,379.58 790.08,396.88 848.05,399.96 906.02,317.18" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.14" points="94.43,403.63 152.4,360.87 210.37,313.25 268.34,304.53 326.31,277.62 384.28,284.65 442.25,290.26 500.22,327.52 558.19,381.87 616.17,432.09 674.14,464.39 732.11,464.96 790.08,487.76 848.05,488.07 906.02,397.56" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.15" points="94.43,325.67 152.4,274.23 210.37,237.08 268.34,217.36 326.31,213.72 384.28,215.63 442.25,223.96 500.22,248.54 558.19,302.17 616.17,360.95 674.14,384.52 732.11,394.65 790.08,409.96 848.05,400.15 906.02,350.08" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.16" points="94.43,301.09 152.4,260.4 210.37,220.77 268.34,206.67 326.31,209.74 384.28,183.28 442.25,192.15 500.22,234.19 558.19,305.45 616.17,352.14 674.14,374.93 732.11,378.82 790.08,390.26 848.05,379.87 906.02,313.88" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.17" points="94.43,282.39 152.4,249.26 210.37,216.99 268.34,190.32 326.31,170.57 384.28,155.51 442.25,182.55 500.22,192.57 558.19,272.61 616.17,329.38 674.14,349.63 732.11,358.09 790.08,383.29 848.05,375.94 906.02,299.74" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.18" points="94.43,278.09 152.4,231.96 210.37,191.19 268.34,171.3 326.31,145.15 384.28,154.03 442.25,165.88 500.22,204.91 558.19,284.59 616.17,341.03 674.14,362.76 732.11,364.83 790.08,368.53 848.05,377.09 906.02,295.93" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.19" points="94.43,319.54 152.4,274.2 210.37,239.84 268.34,207.09 326.31,204.06 384.28,202.74 442.25,217.3 500.22,233.86 558.19,305.18 616.17,360.85 674.14,381.54 732.11,383.31 790.08,399.52 848.05,404.7 906.02,340.88" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.20" points="94.43,369.18 152.4,321.44 210.37,286.41 268.34,267.61 326.31,263.14 384.28,253.31 442.25,267.05 500.22,294.26 558.19,360.97 616.17,407.43 674.14,432.83 732.11,432.29 790.08,455.89 848.05,456.87 906.02,355.54" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.21" points="94.43,298.85 152.4,247.77 210.37,218.59 268.34,186.46 326.31,174.94 384.28,173.14 442.25,178.16 500.22,208.42 558.19,290.42 616.17,326.83 674.14,357.71 732.11,365.34 790.08,376.93 848.05,375.91 906.02,299.15" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.22" points="94.43,348.26 152.4,305.85 210.37,277.67 268.34,249.86 326.31,231.82 384.28,226.07 442.25,254.94 500.22,270.06 558.19,331.17 616.17,379.58 674.14,397.61 732.11,414.91 790.08,421.96 848.05,420.53 906.02,358.13" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.23" points="94.43,283.52 152.4,256.14 210.37,204.6 268.34,167.25 326.31,168.62 384.28,165.24 442.25,170.87 500.22,196.05 558.19,250.04 616.17,312.8 674.14,324.34 732.11,326.82 790.08,342.12 848.05,356.84 906.02,295.8" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.24" points="94.43,299.5 152.4,251.65 210.37,211.1 268.34,195.15 326.31,181.07 384.28,174.68 442.25,196.81 500.22,228.1 558.19,301.84 616.17,341.02 674.14,352.92 732.11,362.44 790.08,384.55 848.05,385.04 906.02,301.37" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.25" points="94.43,300.23 152.4,252.74 210.37,228.86 268.34,192.37 326.31,192.79 384.28,194.95 442.25,209.07 500.22,228.22 558.19,296.71 616.17,353.98 674.14,372.9 732.11,367.51 790.08,383.2 848.05,385.55 906.02,320.21" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.26" points="94.43,279.79 152.4,236.07 210.37,216.74 268.34,199.2 326.31,174.62 384.28,171.71 442.25,168.85 500.22,204.07 558.19,272.08 616.17,314.09 674.14,348.63 732.11,353.79 790.08,366.12 848.05,357.44 906.02,297" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.27" points="94.43,345.18 152.4,289.72 210.37,259.29 268.34,238.37 326.31,221.97 384.28,231.29 442.25,238.73 500.22,256.84 558.19,320.5 616.17,374.4 674.14,389.07 732.11,394.19 790.08,410.95 848.05,416.41 906.02,335.06" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.28" points="94.43,265.99 152.4,219.67 210.37,196.02 268.34,162.25 326.31,156.85 384.28,144.91 442.25,152.46 500.22,178.62 558.19,257.15 616.17,294.97 674.14,328.84 732.11,317.44 790.08,342.62 848.05,338.36 906.02,281.2" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.29" points="94.43,334.28 152.4,288.41 210.37,258.81 268.34,244.17 326.31,212.72 384.28,218.9 442.25,219.75 500.22,247.24 558.19,325 616.17,389.08 674.14,399.21 732.11,395.45 790.08,409.39 848.05,421.01 906.02,335.67" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.30" points="94.43,302.5 152.4,262.97 210.37,222.13 268.34,188.94 326.31,177.68 384.28,176.8 442.25,192.39 500.22,211.97 558.19,282.13 616.17,330.22 674.14,342.45 732.11,347.62 790.08,356.51 848.05,371.48 906.02,309.58" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.31" points="94.43,279.98 152.4,239.36 210.37,191.46 268.34,182.17 326.31,162.53 384.28,152.75 442.25,169.27 500.22,194.68 558.19,275.1 616.17,326.54 674.14,351.39 732.11,365.86 790.08,379.62 848.05,367.36 906.02,302.88" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.32" points="94.43,357.2 152.4,321.55 210.37,272.98 268.34,257.42 326.31,251.51 384.28,238.45 442.25,240.68 500.22,277.52 558.19,340.09 616.17,408.06 674.14,422.69 732.11,434.95 790.08,440 848.05,437.28 906.02,370.42" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.33" points="94.43,310.81 152.4,278.43 210.37,224.06 268.34,218.68 326.31,198.94 384.28,192.51 442.25,196.39 500.22,219.71 558.19,295.06 616.17,349.6 674.14,366.95 732.11,369.22 790.08,389.86 848.05,388.41 906.02,327.7" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.34" points="94.43,330.84 152.4,281.89 210.37,255.06 268.34,232.18 326.31,214.23 384.28,213.01 442.25,220.5 500.22,255.5 558.19,324.73 616.17,380.99 674.14,385 732.11,401.72 790.08,410.7 848.05,419.25 906.02,348.82" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.35" points="94.43,296.59 152.4,245.17 210.37,213.9 268.34,192.75 326.31,173.36 384.28,169.96 442.25,176.42 500.22,196.32 558.19,289.76 616.17,327.55 674.14,368.19 732.11,359.86 790.08,362.73 848.05,365.4 906.02,292.37" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.36" points="94.43,275.4 152.4,234.22 210.37,201.31 268.34,177.17 326.31,166.05 384.28,164.68 442.25,157.64 500.22,195.25 558.19,259.62 616.17,318.92 674.14,341.85 732.11,345.95 790.08,363.57 848.05,364.37 906.02,277.66" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.37" points="94.43,353.28 152.4,319.63 210.37,272.27 268.34,256.3 326.31,233.89 384.28,241.56 442.25,253 500.22,287.08 558.19,365.56 616.17,402.4 674.14,429.08 732.11,431.81 790.08,447.65 848.05,447.21 906.02,351" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.38" points="94.43,306.27 152.4,264.82 210.37,226.53 268.34,196.98 326.31,172.92 384.28,174.36 442.25,181.25 500.22,221.9 558.19,271.99 616.17,320.09 674.14,341.21 732.11,353.01 790.08,358.59 848.05,372.93 906.02,316.93" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.39" points="94.43,365.16 152.4,329.89 210.37,282.11 268.34,256.85 326.31,243.13 384.28,241.52 442.25,251.55 500.22,274.23 558.19,343.1 616.17,394.58 674.14,420.24 732.11,419.78 790.08,442.81 848.05,446.26 906.02,352.36" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.40" points="94.43,332.23 152.4,293.76 210.37,251.61 268.34,233.76 326.31,224.34 384.28,220.07 442.25,218.08 500.22,258 558.19,314.85 616.17,366.29 674.14,391.2 732.11,395.49 790.08,418.51 848.05,413.15 906.02,343.8" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.41" points="94.43,332.7 152.4,297.87 210.37,253.62 268.34,213.6 326.31,194.7 384.28,191.1 442.25,204.92 500.22,234.36 558.19,295.26 616.17,349.92 674.14,371.58 732.11,372.66 790.08,390.8 848.05,392.56 906.02,337.04" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.42" points="94.43,344.36 152.4,308.2 210.37,268.66 268.34,245.57 326.31,226.51 384.28,225.93 442.25,237.24 500.22,263.51 558.19,338.05 616.17,372.09 674.14,406.38 732.11,408.71 790.08,429.07 848.05,428.89 906.02,340.59" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.43" points="94.43,317.82 152.4,279.34 210.37,249.79 268.34,224.17 326.31,203.92 384.28,212.49 442.25,226.1 500.22,244.32 558.19,308.74 616.17,356.08 674.14,386.57 732.11,390.04 790.08,404.93 848.05,403.15 906.02,337.7" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.44" points="94.43,331.88 152.4,280.35 210.37,253.66 268.34,224.79 326.31,208.25 384.28,217.86 442.25,214.45 500.22,250.16 558.19,320.15 616.17,379.5 674.14,391.74 732.11,394.15 790.08,404.61 848.05,405.51 906.02,336.45" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.45" points="94.43,306.02 152.4,272.99 210.37,234.88 268.34,209.19 326.31,196.81 384.28,190.24 442.25,203.24 500.22,246.34 558.19,321.03 616.17,370.98 674.14,380.61 732.11,399.7 790.08,408.73 848.05,399.03 906.02,339.55" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.46" points="94.43,331.24 152.4,292.37 210.37,248.14 268.34,242.64 326.31,209.74 384.28,212.16 442.25,218.83 500.22,250.99 558.19,319.57 616.17,366.69 674.14,388.64 732.11,411.49 790.08,417.72 848.05,423.35 906.02,338.96" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.47" points="94.43,307.88 152.4,258.34 210.37,218.6 268.34,196.42 326.31,183.96 384.28,189.72 442.25,194.99 500.22,221.86 558.19,316.5 616.17,340.59 674.14,366.19 732.11,382.11 790.08,394.86 848.05,391.25 906.02,318.74" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.48" points="94.43,340.17 152.4,295.02 210.37,259.84 268.34,226.64 326.31,224.25 384.28,224.13 442.25,233.68 500.22,254.83 558.19,322.84 616.17,375.09 674.14,392.27 732.11,393.28 790.08,408.32 848.05,416.05 906.02,340.52" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.49" points="94.43,292.99 152.4,259.84 210.37,222.35 268.34,204.49 326.31,194.57 384.28,183.65 442.25,199.39 500.22,218.63 558.19,285.53 616.17,361.18 674.14,377.89 732.11,370.49 790.08,398.83 848.05,390.08 906.02,315.8" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.50" points="94.43,311.99 152.4,294.02 210.37,255.73 268.34,225.51 326.31,217.13 384.28,211.53 442.25,208.39 500.22,251.41 558.19,308.58 616.17,379.62 674.14,403.15 732.11,401.64 790.08,413.65 848.05,412.97 906.02,346.02" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.51" points="94.43,267.58 152.4,232.82 210.37,183.96 268.34,174.72 326.31,150.93 384.28,150.87 442.25,162.56 500.22,183.85 558.19,254.34 616.17,318 674.14,340.19 732.11,332.56 790.08,345.81 848.05,346.3 906.02,278.92" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.52" points="94.43,319.19 152.4,278.28 210.37,240.13 268.34,217.5 326.31,202.76 384.28,200.54 442.25,209.94 500.22,238.59 558.19,307.66 616.17,359.95 674.14,381.32 732.11,385.74 790.08,400.52 848.05,401.17 906.02,327.98" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
              </g>
              <g id="GRID.polyline.16.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.16.1.1" points="94.43,319.19 152.4,278.28 210.37,240.13 268.34,217.5 326.31,202.76 384.28,200.54 442.25,209.94 500.22,238.59 558.19,307.66 616.17,359.95 674.14,381.32 732.11,385.74 790.08,400.52 848.05,401.17 906.02,327.98" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
              </g>
              <g id="geom_point.points.18.1" class="points grob gDesc">
                <use id="geom_point.points.18.1.1" xlink:href="#gridSVG.pch16" x="906.02" y="327.98" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.2" xlink:href="#gridSVG.pch16" x="94.43" y="319.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.3" xlink:href="#gridSVG.pch16" x="152.4" y="278.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.4" xlink:href="#gridSVG.pch16" x="210.37" y="240.13" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.5" xlink:href="#gridSVG.pch16" x="268.34" y="217.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.6" xlink:href="#gridSVG.pch16" x="326.31" y="202.76" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.7" xlink:href="#gridSVG.pch16" x="384.28" y="200.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.8" xlink:href="#gridSVG.pch16" x="442.25" y="209.94" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.9" xlink:href="#gridSVG.pch16" x="500.22" y="238.59" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.10" xlink:href="#gridSVG.pch16" x="558.19" y="307.66" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.11" xlink:href="#gridSVG.pch16" x="616.17" y="359.95" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.12" xlink:href="#gridSVG.pch16" x="674.14" y="381.32" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.13" xlink:href="#gridSVG.pch16" x="732.11" y="385.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.14" xlink:href="#gridSVG.pch16" x="790.08" y="400.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.15" xlink:href="#gridSVG.pch16" x="848.05" y="401.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
              </g>
              <g id="GRID.text.19.1" class="text grob gDesc">
                <g id="GRID.text.19.1.1" transform="translate(384.28, 325.29)" stroke-width="0.1">
                  <g id="GRID.text.19.1.1.scale" transform="scale(1, -1)">
                    <text x="0" y="0" id="GRID.text.19.1.1.text" text-anchor="middle" stroke="rgb(255,0,0)" font-size="18.9" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(255,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                      <tspan id="GRID.text.19.1.1.tspan.1" dy="7.5" x="0">Female</tspan>
                    </text>
                  </g>
                </g>
              </g>
              <g id="GRID.text.20.1" class="text grob gDesc">
                <g id="GRID.text.20.1.1" transform="translate(732.11, 188.33)" stroke-width="0.1">
                  <g id="GRID.text.20.1.1.scale" transform="scale(1, -1)">
                    <text x="0" y="0" id="GRID.text.20.1.1.text" text-anchor="middle" stroke="rgb(0,255,0)" font-size="18.9" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,255,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                      <tspan id="GRID.text.20.1.1.tspan.1" dy="7.5" x="0">Male</tspan>
                    </text>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-l.3-3-3-3.1" class="pushedvp viewport">
            <g id="layout::axis-l.3-3-3-3::GRID.VP.2.1" class="pushedvp viewport">
              <g id="axis-l.3-3-3-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-l.3-3-3-3::GRID.VP.2::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.60.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-l.3-3-3-3::GRID.VP.2::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                        <g id="axis.1-1-1-1.1.1" transform="translate(50.2, 188.33)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">0.3</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.2" transform="translate(50.2, 325.29)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">0.4</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.3" transform="translate(50.2, 462.25)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">0.5</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                    <g id="layout::axis-l.3-3-3-3::GRID.VP.2::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                      <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-2-1-2.1.1" points="53.98,188.33 59.65,188.33" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.2" points="53.98,325.29 59.65,325.29" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.3" points="53.98,462.25 59.65,462.25" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-b.4-4-4-4.1" class="pushedvp viewport">
            <g id="layout::axis-b.4-4-4-4::GRID.VP.1.1" class="pushedvp viewport">
              <g id="axis-b.4-4-4-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-b.4-4-4-4::GRID.VP.1::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.65.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-b.4-4-4-4::GRID.VP.1::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.2" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-1-1-1.2.1" points="94.43,46.98 94.43,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.2" points="152.4,46.98 152.4,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.3" points="210.37,46.98 210.37,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.4" points="268.34,46.98 268.34,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.5" points="326.31,46.98 326.31,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.6" points="384.28,46.98 384.28,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.7" points="442.25,46.98 442.25,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.8" points="500.22,46.98 500.22,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.9" points="558.19,46.98 558.19,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.10" points="616.17,46.98 616.17,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.11" points="674.14,46.98 674.14,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.12" points="732.11,46.98 732.11,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.13" points="790.08,46.98 790.08,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.14" points="848.05,46.98 848.05,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.15" points="906.02,46.98 906.02,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                    <g id="layout::axis-b.4-4-4-4::GRID.VP.1::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                      <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                        <g id="axis.2-1-2-1.1.1" transform="translate(94.43, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">18-19</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.2" transform="translate(152.4, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">20-24</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.3" transform="translate(210.37, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">25-29</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.4" transform="translate(268.34, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.4.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.4.tspan.1" dy="11" x="0">30-34</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.5" transform="translate(326.31, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.5.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.5.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.5.tspan.1" dy="11" x="0">35-39</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.6" transform="translate(384.28, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.6.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.6.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.6.tspan.1" dy="11" x="0">40-44</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.7" transform="translate(442.25, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.7.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.7.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.7.tspan.1" dy="11" x="0">45-49</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.8" transform="translate(500.22, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.8.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.8.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.8.tspan.1" dy="11" x="0">50-54</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.9" transform="translate(558.19, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.9.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.9.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.9.tspan.1" dy="11" x="0">55-59</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.10" transform="translate(616.17, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.10.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.10.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.10.tspan.1" dy="11" x="0">60-64</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.11" transform="translate(674.14, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.11.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.11.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.11.tspan.1" dy="11" x="0">65-69</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.12" transform="translate(732.11, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.12.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.12.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.12.tspan.1" dy="11" x="0">70-74</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.13" transform="translate(790.08, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.13.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.13.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.13.tspan.1" dy="11" x="0">75-79</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.14" transform="translate(848.05, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.14.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.14.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.14.tspan.1" dy="11" x="0">80-84</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.15" transform="translate(906.02, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.15.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.15.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.15.tspan.1" dy="11" x="0">85+</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::xlab.5-4-5-4.1" class="pushedvp viewport">
            <g id="xlab.5-4-5-4.1" class="gTableChild text grob gDesc">
              <g id="xlab.5-4-5-4.1.1" transform="translate(500.22, 20.9)" stroke-width="0.1">
                <g id="xlab.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="xlab.5-4-5-4.1.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="xlab.5-4-5-4.1.1.tspan.1" dy="6.5" x="0">Age</tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::ylab.3-2-3-2.1" class="pushedvp viewport">
            <g id="ylab.3-2-3-2.1" class="gTableChild text grob gDesc">
              <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 280.72)" stroke-width="0.1">
                <g id="ylab.3-2-3-2.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="ylab.3-2-3-2.1.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="ylab.3-2-3-2.1.1.tspan.1" dy="6.5" x="0">Percent Satisfied</tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::title.2-4-2-4.1" class="pushedvp viewport">
            <g id="title.2-4-2-4.1" class="gTableChild text grob gDesc">
              <g id="title.2-4-2-4.1.1" transform="translate(500.22, 508.8)" stroke-width="0.1">
                <g id="title.2-4-2-4.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="title.2-4-2-4.1.1.text" text-anchor="middle" font-size="19.2" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="title.2-4-2-4.1.1.tspan.1" dy="7.5" x="0"> </tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
        </g>
      </g>
    </g>
  </g>
</svg>



---

### Income and Children Effects by State

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="960px" height="528px" viewBox="0 0 960 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-10-25 17:38:42"/>
    <gridsvg:argument name="name" value="erase_me.svg"/>
    <gridsvg:argument name="exportCoords" value="none"/>
    <gridsvg:argument name="exportMappings" value="none"/>
    <gridsvg:argument name="exportJS" value="none"/>
    <gridsvg:argument name="res" value="96"/>
    <gridsvg:argument name="prefix" value=""/>
    <gridsvg:argument name="addClasses" value="TRUE"/>
    <gridsvg:argument name="indent" value="TRUE"/>
    <gridsvg:argument name="htmlWrapper" value="FALSE"/>
    <gridsvg:argument name="usePaths" value="vpPaths"/>
    <gridsvg:argument name="uniqueNames" value="TRUE"/>
    <gridsvg:separator name="id.sep" value="."/>
    <gridsvg:separator name="gPath.sep" value="::"/>
    <gridsvg:separator name="vpPath.sep" value="::"/>
  </metadata>
  <g transform="translate(0, 528) scale(1, -1)">
    <g id="gridSVG" fill="none" stroke="rgb(0,0,0)" stroke-dasharray="none" stroke-width="1" font-size="16" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" opacity="1" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-opacity="1" fill-opacity="0" font-weight="normal" font-style="normal">
      <g id="GRID.VP.33.1" class="pushedvp viewport">
        <g id="GRID.VP.33::GRID.VP.34.1" class="pushedvp viewport">
          <g id="GRID.VP.33::GRID.VP.34::layout.1" class="pushedvp viewport">
            <g id="GRID.gTableParent.127.1" class="gTableParent gTree grob gDesc">
              <defs>
                <clipPath id="GRID.VP.33::GRID.VP.34::layout::background.1-5-6-1.1.clipPath">
                  <rect x="0" y="0" width="480" height="528" fill="none" stroke="none"/>
                </clipPath>
              </defs>
              <g id="GRID.VP.33::GRID.VP.34::layout::background.1-5-6-1.1" clip-path="url(#GRID.VP.33::GRID.VP.34::layout::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
                  <rect id="background.1-5-6-1.1.1" x="0" y="0" width="480" height="528" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.34::layout::spacer.4-3-4-3.1" class="pushedvp viewport"/>
              <defs>
                <clipPath id="GRID.VP.33::GRID.VP.34::layout::panel.3-4-3-4.1.clipPath">
                  <rect x="59.65" y="52.65" width="401.15" height="431.55" fill="none" stroke="none"/>
                </clipPath>
              </defs>
              <g id="GRID.VP.33::GRID.VP.34::layout::panel.3-4-3-4.1" clip-path="url(#GRID.VP.33::GRID.VP.34::layout::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
                  <g id="grill.gTree.105.1" class="gTree grob gDesc">
                    <g id="panel.background.rect.98.1" class="rect grob gDesc">
                      <rect id="panel.background.rect.98.1.1" x="59.65" y="52.65" width="401.15" height="431.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                    </g>
                    <g id="panel.grid.minor.y.polyline.100.1" class="polyline grob gDesc">
                      <polyline id="panel.grid.minor.y.polyline.100.1.1" points="59.65,143.74 460.8,143.74" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.minor.y.polyline.100.1.2" points="59.65,248.34 460.8,248.34" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.minor.y.polyline.100.1.3" points="59.65,352.94 460.8,352.94" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.minor.y.polyline.100.1.4" points="59.65,457.54 460.8,457.54" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                    </g>
                    <g id="panel.grid.major.y.polyline.102.1" class="polyline grob gDesc">
                      <polyline id="panel.grid.major.y.polyline.102.1.1" points="59.65,91.43 460.8,91.43" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.y.polyline.102.1.2" points="59.65,196.04 460.8,196.04" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.y.polyline.102.1.3" points="59.65,300.64 460.8,300.64" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.y.polyline.102.1.4" points="59.65,405.24 460.8,405.24" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                    </g>
                    <g id="panel.grid.major.x.polyline.104.1" class="polyline grob gDesc">
                      <polyline id="panel.grid.major.x.polyline.104.1.1" points="93.08,52.65 93.08,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.104.1.2" points="148.79,52.65 148.79,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.104.1.3" points="204.51,52.65 204.51,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.104.1.4" points="260.22,52.65 260.22,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.104.1.5" points="315.94,52.65 315.94,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.104.1.6" points="371.66,52.65 371.66,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.104.1.7" points="427.37,52.65 427.37,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                    </g>
                  </g>
                  <g id="GRID.polyline.90.1" class="polyline grob gDesc">
                    <polyline id="GRID.polyline.90.1.1" points="93.08,102.77 148.79,129.74 204.51,160.83 260.22,202.07 315.94,259.62 371.66,326.64 427.37,432.41" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                  </g>
                  <g id="GRID.polyline.91.1" class="polyline grob gDesc">
                    <polyline id="GRID.polyline.91.1.1" points="93.08,100.99 148.79,140.77 204.51,166.33 260.22,199.92 315.94,263.29 371.66,322.13 427.37,426.44" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.2" points="93.08,109.33 148.79,122.2 204.51,149.36 260.22,201.28 315.94,261.02 371.66,313.65 427.37,429.86" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.3" points="93.08,113.4 148.79,140.59 204.51,170.26 260.22,205.53 315.94,253.99 371.66,305.24 427.37,416.29" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.4" points="93.08,100.08 148.79,129.45 204.51,163.77 260.22,208.05 315.94,270.98 371.66,343.32 427.37,442.92" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.5" points="93.08,110.49 148.79,133.9 204.51,154.21 260.22,201.03 315.94,257.71 371.66,332.24 427.37,434.75" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.6" points="93.08,97.41 148.79,137.61 204.51,173.92 260.22,207.56 315.94,267.74 371.66,328.24 427.37,418" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.7" points="93.08,98.3 148.79,121.07 204.51,158.71 260.22,199.48 315.94,265.66 371.66,335.56 427.37,449.68" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.8" points="93.08,112.77 148.79,139.88 204.51,154.64 260.22,206.15 315.94,255.78 371.66,305.72 427.37,424.59" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.9" points="93.08,95.84 148.79,126.21 204.51,164.65 260.22,208.06 315.94,246.57 371.66,328.18 427.37,440.65" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.10" points="93.08,98.83 148.79,128.98 204.51,148.19 260.22,202.27 315.94,255.73 371.66,337.23 427.37,436.21" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.11" points="93.08,114.28 148.79,127.66 204.51,163.02 260.22,208.98 315.94,263.75 371.66,322.87 427.37,415.5" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.12" points="93.08,113.79 148.79,131.3 204.51,147.87 260.22,196.65 315.94,257.59 371.66,321.6 427.37,430.86" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.13" points="93.08,90.81 148.79,124.34 204.51,155.93 260.22,213.69 315.94,266.37 371.66,334.46 427.37,444.66" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.14" points="93.08,105.98 148.79,141.06 204.51,164.44 260.22,206.99 315.94,268.23 371.66,314.64 427.37,418.17" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.15" points="93.08,101.54 148.79,122.83 204.51,158.59 260.22,208.31 315.94,260.86 371.66,340.59 427.37,439.12" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.16" points="93.08,96.03 148.79,142.19 204.51,162.78 260.22,207.23 315.94,250.03 371.66,315.9 427.37,421.73" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.17" points="93.08,107.12 148.79,131.92 204.51,159.78 260.22,194.29 315.94,246.09 371.66,322.03 427.37,435.03" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.18" points="93.08,112.21 148.79,126.58 204.51,162.69 260.22,198.23 315.94,251.61 371.66,317.39 427.37,424.94" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.19" points="93.08,92.75 148.79,134.8 204.51,156.07 260.22,209.63 315.94,250.94 371.66,331.02 427.37,438.87" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.20" points="93.08,96.02 148.79,132.35 204.51,159.95 260.22,199.5 315.94,258.24 371.66,324.93 427.37,434.21" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.21" points="93.08,109.23 148.79,130.05 204.51,156.74 260.22,207.78 315.94,261.81 371.66,328.19 427.37,421.66" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.22" points="93.08,96.28 148.79,127.06 204.51,166.14 260.22,207.4 315.94,258.83 371.66,340.29 427.37,428.5" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.23" points="93.08,97.34 148.79,120.89 204.51,151.83 260.22,201.4 315.94,255.82 371.66,331.61 427.37,438.72" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.24" points="93.08,95.37 148.79,131.61 204.51,161.59 260.22,201.52 315.94,258.28 371.66,327.52 427.37,436.68" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.25" points="93.08,100.05 148.79,120.02 204.51,163.45 260.22,201.18 315.94,262.08 371.66,330.99 427.37,445.06" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.26" points="93.08,112.11 148.79,135.92 204.51,165.88 260.22,190.67 315.94,248.06 371.66,303.82 427.37,431.25" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.27" points="93.08,97.26 148.79,130.08 204.51,172.45 260.22,199.68 315.94,267.62 371.66,343.06 427.37,428.13" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.28" points="93.08,116.93 148.79,139.17 204.51,168.77 260.22,201.28 315.94,249.82 371.66,304.24 427.37,411.35" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.29" points="93.08,96.71 148.79,132.69 204.51,159.93 260.22,207.83 315.94,267.65 371.66,336.63 427.37,446.01" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.30" points="93.08,104.17 148.79,115.93 204.51,157.33 260.22,191.49 315.94,267.42 371.66,331.18 427.37,438.29" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.31" points="93.08,97.02 148.79,129.17 204.51,154.96 260.22,187.64 315.94,261.28 371.66,327.48 427.37,450.08" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.32" points="93.08,99.81 148.79,131.41 204.51,162.77 260.22,203.69 315.94,270.48 371.66,336.74 427.37,430.98" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.33" points="93.08,91.49 148.79,125.99 204.51,162.52 260.22,200.74 315.94,272.58 371.66,338.67 427.37,438.29" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.34" points="93.08,107.65 148.79,122.05 204.51,153.22 260.22,195.82 315.94,267.32 371.66,332.12 427.37,436.76" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.35" points="93.08,98.22 148.79,120.33 204.51,160.84 260.22,196.67 315.94,257.83 371.66,323.6 427.37,438.76" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.36" points="93.08,110.33 148.79,130.75 204.51,163.78 260.22,195.54 315.94,248.58 371.66,321.24 427.37,439.69" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.37" points="93.08,99.21 148.79,126.73 204.51,159.35 260.22,206.54 315.94,254.86 371.66,328.43 427.37,435.08" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.38" points="93.08,104.32 148.79,123.26 204.51,147.71 260.22,202.33 315.94,258.47 371.66,340.44 427.37,436.61" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.39" points="93.08,93.03 148.79,115.81 204.51,182.6 260.22,210.58 315.94,264.97 371.66,342.96 427.37,438.08" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.40" points="93.08,104.75 148.79,139.97 204.51,163.57 260.22,198.21 315.94,264.81 371.66,326.03 427.37,424.31" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.41" points="93.08,100.85 148.79,120.74 204.51,158.43 260.22,204.45 315.94,259.24 371.66,321.67 427.37,445.18" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.42" points="93.08,89.74 148.79,128.07 204.51,171.15 260.22,203.02 315.94,264.17 371.66,330.81 427.37,435.71" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.43" points="93.08,100.65 148.79,129.9 204.51,155.19 260.22,197.68 315.94,254 371.66,335.67 427.37,439.52" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.44" points="93.08,100.65 148.79,123.26 204.51,161.85 260.22,212.21 315.94,258.6 371.66,326.13 427.37,433.3" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.45" points="93.08,109.11 148.79,137.14 204.51,155.29 260.22,202.33 315.94,261.42 371.66,330.63 427.37,420.08" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.46" points="93.08,96.25 148.79,128.01 204.51,159.81 260.22,200.34 315.94,275.83 371.66,337.04 427.37,431.86" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.47" points="93.08,94.34 148.79,123.25 204.51,154.09 260.22,200.7 315.94,262.18 371.66,335.05 427.37,439.23" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.48" points="93.08,103.16 148.79,130.02 204.51,159.14 260.22,204.93 315.94,270.05 371.66,328.4 427.37,421.64" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.49" points="93.08,124.6 148.79,146.56 204.51,175.44 260.22,194.63 315.94,233.36 371.66,286.9 427.37,400.18" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.50" points="93.08,111.17 148.79,127.69 204.51,162.13 260.22,196.86 315.94,258 371.66,320.54 427.37,438.56" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.51" points="93.08,111.7 148.79,137.38 204.51,159.11 260.22,197.42 315.94,253.05 371.66,313.66 427.37,430.78" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.91.1.52" points="93.08,102.77 148.79,129.74 204.51,160.83 260.22,202.07 315.94,259.62 371.66,326.64 427.37,432.41" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                  </g>
                  <g id="hlines.gTree.94.1" class="gTree grob gDesc">
                    <g id="GRID.segments.92.1" class="segments grob gDesc">
                      <polyline id="GRID.segments.92.1.1" points="59.65,91.43 460.8,91.43" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.34::layout::axis-l.3-3-3-3.1" class="pushedvp viewport">
                <g id="GRID.VP.33::GRID.VP.34::layout::axis-l.3-3-3-3::GRID.VP.36.1" class="pushedvp viewport">
                  <g id="axis-l.3-3-3-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                    <g id="GRID.VP.33::GRID.VP.34::layout::axis-l.3-3-3-3::GRID.VP.36::axis.1" class="pushedvp viewport">
                      <g id="GRID.gTableParent.176.1" class="gTableParent gTree grob gDesc">
                        <g id="GRID.VP.33::GRID.VP.34::layout::axis-l.3-3-3-3::GRID.VP.36::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                          <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                            <g id="axis.1-1-1-1.1.1" transform="translate(50.2, 91.43)" stroke-width="0.1">
                              <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">0.0</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.1-1-1-1.1.2" transform="translate(50.2, 196.04)" stroke-width="0.1">
                              <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">0.1</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.1-1-1-1.1.3" transform="translate(50.2, 300.64)" stroke-width="0.1">
                              <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">0.2</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.1-1-1-1.1.4" transform="translate(50.2, 405.24)" stroke-width="0.1">
                              <g id="axis.1-1-1-1.1.4.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.1-1-1-1.1.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.1-1-1-1.1.4.tspan.1" dy="5.5" x="0">0.3</tspan>
                                </text>
                              </g>
                            </g>
                          </g>
                        </g>
                        <g id="GRID.VP.33::GRID.VP.34::layout::axis-l.3-3-3-3::GRID.VP.36::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                          <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                            <polyline id="axis.1-2-1-2.1.1" points="53.98,91.43 59.65,91.43" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-2-1-2.1.2" points="53.98,196.04 59.65,196.04" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-2-1-2.1.3" points="53.98,300.64 59.65,300.64" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-2-1-2.1.4" points="53.98,405.24 59.65,405.24" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.34::layout::axis-b.4-4-4-4.1" class="pushedvp viewport">
                <g id="GRID.VP.33::GRID.VP.34::layout::axis-b.4-4-4-4::GRID.VP.35.1" class="pushedvp viewport">
                  <g id="axis-b.4-4-4-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
                    <g id="GRID.VP.33::GRID.VP.34::layout::axis-b.4-4-4-4::GRID.VP.35::axis.1" class="pushedvp viewport">
                      <g id="GRID.gTableParent.182.1" class="gTableParent gTree grob gDesc">
                        <g id="GRID.VP.33::GRID.VP.34::layout::axis-b.4-4-4-4::GRID.VP.35::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                          <g id="axis.1-1-1-1.2" class="gTableChild polyline grob gDesc">
                            <polyline id="axis.1-1-1-1.2.1" points="93.08,46.98 93.08,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.2.2" points="148.79,46.98 148.79,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.2.3" points="204.51,46.98 204.51,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.2.4" points="260.22,46.98 260.22,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.2.5" points="315.94,46.98 315.94,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.2.6" points="371.66,46.98 371.66,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.2.7" points="427.37,46.98 427.37,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          </g>
                        </g>
                        <g id="GRID.VP.33::GRID.VP.34::layout::axis-b.4-4-4-4::GRID.VP.35::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                          <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                            <g id="axis.2-1-2-1.1.1" transform="translate(93.08, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">INC2</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.1.2" transform="translate(148.79, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">INC3</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.1.3" transform="translate(204.51, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">INC4</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.1.4" transform="translate(260.22, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.1.4.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.1.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.1.4.tspan.1" dy="11" x="0">INC5</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.1.5" transform="translate(315.94, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.1.5.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.1.5.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.1.5.tspan.1" dy="11" x="0">INC6</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.1.6" transform="translate(371.66, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.1.6.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.1.6.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.1.6.tspan.1" dy="11" x="0">INC7</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.1.7" transform="translate(427.37, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.1.7.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.1.7.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.1.7.tspan.1" dy="11" x="0">INC8</tspan>
                                </text>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.34::layout::xlab.5-4-5-4.1" class="pushedvp viewport">
                <g id="xlab.5-4-5-4.1" class="gTableChild text grob gDesc">
                  <g id="xlab.5-4-5-4.1.1" transform="translate(260.22, 20.9)" stroke-width="0.1">
                    <g id="xlab.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                      <text x="0" y="0" id="xlab.5-4-5-4.1.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                        <tspan id="xlab.5-4-5-4.1.1.tspan.1" dy="6.5" x="0">Income</tspan>
                      </text>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.34::layout::ylab.3-2-3-2.1" class="pushedvp viewport">
                <g id="ylab.3-2-3-2.1" class="gTableChild text grob gDesc">
                  <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 268.42)" stroke-width="0.1">
                    <g id="ylab.3-2-3-2.1.1.scale" transform="scale(1, -1)">
                      <text x="0" y="0" id="ylab.3-2-3-2.1.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                        <tspan id="ylab.3-2-3-2.1.1.tspan.1" dy="6.5" x="0">Life Satisfaction</tspan>
                      </text>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.34::layout::title.2-4-2-4.1" class="pushedvp viewport">
                <g id="title.2-4-2-4.1" class="gTableChild text grob gDesc">
                  <g id="title.2-4-2-4.1.1" transform="translate(260.22, 496.5)" stroke-width="0.1">
                    <g id="title.2-4-2-4.1.1.scale" transform="scale(1, -1)">
                      <text x="0" y="0" id="title.2-4-2-4.1.1.text" text-anchor="middle" font-size="19.2" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                        <tspan id="title.2-4-2-4.1.1.tspan.1" dy="7.5" x="0">Income Effects (base=INC1)</tspan>
                      </text>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
        </g>
        <g id="GRID.VP.33::GRID.VP.37.1" class="pushedvp viewport">
          <g id="GRID.VP.33::GRID.VP.37::layout.1" class="pushedvp viewport">
            <g id="GRID.gTableParent.167.1" class="gTableParent gTree grob gDesc">
              <defs>
                <clipPath id="GRID.VP.33::GRID.VP.37::layout::background.1-5-6-1.1.clipPath">
                  <rect x="480" y="0" width="480" height="528" fill="none" stroke="none"/>
                </clipPath>
              </defs>
              <g id="GRID.VP.33::GRID.VP.37::layout::background.1-5-6-1.1" clip-path="url(#GRID.VP.33::GRID.VP.37::layout::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                <g id="background.1-5-6-1.2" class="gTableChild rect grob gDesc">
                  <rect id="background.1-5-6-1.2.1" x="480" y="0" width="480" height="528" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.37::layout::spacer.4-3-4-3.1" class="pushedvp viewport"/>
              <defs>
                <clipPath id="GRID.VP.33::GRID.VP.37::layout::panel.3-4-3-4.1.clipPath">
                  <rect x="546.65" y="52.65" width="394.15" height="431.55" fill="none" stroke="none"/>
                </clipPath>
              </defs>
              <g id="GRID.VP.33::GRID.VP.37::layout::panel.3-4-3-4.1" clip-path="url(#GRID.VP.33::GRID.VP.37::layout::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                <g id="panel.3-4-3-4.2" class="gTableChild gTree grob gDesc">
                  <g id="grill.gTree.145.1" class="gTree grob gDesc">
                    <g id="panel.background.rect.138.1" class="rect grob gDesc">
                      <rect id="panel.background.rect.138.1.1" x="546.65" y="52.65" width="394.15" height="431.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                    </g>
                    <g id="panel.grid.minor.y.polyline.140.1" class="polyline grob gDesc">
                      <polyline id="panel.grid.minor.y.polyline.140.1.1" points="546.65,124.93 940.8,124.93" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.minor.y.polyline.140.1.2" points="546.65,282.21 940.8,282.21" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.minor.y.polyline.140.1.3" points="546.65,439.49 940.8,439.49" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                    </g>
                    <g id="panel.grid.major.y.polyline.142.1" class="polyline grob gDesc">
                      <polyline id="panel.grid.major.y.polyline.142.1.1" points="546.65,203.57 940.8,203.57" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.y.polyline.142.1.2" points="546.65,360.85 940.8,360.85" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                    </g>
                    <g id="panel.grid.major.x.polyline.144.1" class="polyline grob gDesc">
                      <polyline id="panel.grid.major.x.polyline.144.1.1" points="584.79,52.65 584.79,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.144.1.2" points="648.37,52.65 648.37,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.144.1.3" points="711.94,52.65 711.94,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.144.1.4" points="775.51,52.65 775.51,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.144.1.5" points="839.08,52.65 839.08,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      <polyline id="panel.grid.major.x.polyline.144.1.6" points="902.66,52.65 902.66,484.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                    </g>
                  </g>
                  <g id="GRID.polyline.130.1" class="polyline grob gDesc">
                    <polyline id="GRID.polyline.130.1.1" points="584.79,148.88 648.37,191.98 711.94,203.63 775.51,251.03 839.08,263.92 902.66,401.94" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.2" points="584.79,141.89 648.37,173.03 711.94,199.59 775.51,251.29 839.08,267.93 902.66,403.17" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.3" points="584.79,144.16 648.37,191.33 711.94,209.59 775.51,248.59 839.08,266.97 902.66,402.95" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.4" points="584.79,139.67 648.37,193.37 711.94,199.99 775.51,249.91 839.08,259.39 902.66,403.77" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.5" points="584.79,145.98 648.37,192.59 711.94,207.77 775.51,251.69 839.08,264.39 902.66,404.37" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.6" points="584.79,134.47 648.37,182.96 711.94,208.26 775.51,250.7 839.08,262.86 902.66,404.54" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.7" points="584.79,141.71 648.37,186.85 711.94,215.21 775.51,254.03 839.08,269.51 902.66,403.58" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.8" points="584.79,132.03 648.37,179.72 711.94,213.68 775.51,253.03 839.08,263.5 902.66,403.08" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.9" points="584.79,122.9 648.37,177.93 711.94,205.5 775.51,257.19 839.08,265.63 902.66,404.2" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.10" points="584.79,124.65 648.37,176.55 711.94,209.51 775.51,255.67 839.08,264.79 902.66,404.44" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.11" points="584.79,126.41 648.37,190.83 711.94,212.1 775.51,253.36 839.08,265.35 902.66,403.99" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.12" points="584.79,145.07 648.37,185.98 711.94,216.52 775.51,255.47 839.08,265.63 902.66,404.09" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.13" points="584.79,145.92 648.37,193.15 711.94,198.27 775.51,258.35 839.08,268.29 902.66,404.34" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.14" points="584.79,131.43 648.37,181.13 711.94,209.39 775.51,250.71 839.08,262.91 902.66,401.07" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.15" points="584.79,129.11 648.37,197.71 711.94,206.96 775.51,256.18 839.08,268.04 902.66,405.64" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.16" points="584.79,137.79 648.37,194.53 711.94,207.45 775.51,252.93 839.08,270.12 902.66,404.35" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.17" points="584.79,137.84 648.37,186.29 711.94,208.68 775.51,260.13 839.08,262.64 902.66,401.49" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.18" points="584.79,107.69 648.37,170.75 711.94,206.86 775.51,248.61 839.08,266.15 902.66,401.2" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.19" points="584.79,131.48 648.37,182.13 711.94,204.8 775.51,255.98 839.08,268.97 902.66,404.7" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.20" points="584.79,137.88 648.37,181.87 711.94,200.59 775.51,250.51 839.08,265.35 902.66,403.12" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.21" points="584.79,129.99 648.37,190.24 711.94,202.92 775.51,249.54 839.08,266.58 902.66,400.32" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.22" points="584.79,140.45 648.37,193.33 711.94,213.27 775.51,251.71 839.08,269.22 902.66,403.59" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.23" points="584.79,136.21 648.37,196.65 711.94,221.91 775.51,258.28 839.08,261.94 902.66,404.48" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.24" points="584.79,139.74 648.37,179.1 711.94,204.71 775.51,252.52 839.08,268.45 902.66,402.85" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.25" points="584.79,132.45 648.37,182.26 711.94,193.94 775.51,250.43 839.08,267.82 902.66,404.16" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.26" points="584.79,134.81 648.37,188.33 711.94,211.89 775.51,256.77 839.08,270.42 902.66,406.29" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.27" points="584.79,136.16 648.37,200.39 711.94,204.46 775.51,250.44 839.08,264.55 902.66,403.39" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.28" points="584.79,139.01 648.37,199.48 711.94,215.62 775.51,254.5 839.08,270.79 902.66,407.41" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.29" points="584.79,145.57 648.37,204.52 711.94,213.78 775.51,250.93 839.08,262.23 902.66,403.61" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.30" points="584.79,134.26 648.37,195.77 711.94,212.28 775.51,255.92 839.08,267.1 902.66,404.34" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.31" points="584.79,140.82 648.37,181.93 711.94,205.87 775.51,245.56 839.08,265.17 902.66,406.28" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.32" points="584.79,127 648.37,189.81 711.94,211.94 775.51,251.99 839.08,265.83 902.66,402.09" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.33" points="584.79,149.9 648.37,192.82 711.94,202.29 775.51,253.22 839.08,262.64 902.66,402.44" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.34" points="584.79,142.04 648.37,188.14 711.94,206.04 775.51,254.75 839.08,268.23 902.66,401.97" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.35" points="584.79,125.63 648.37,189.75 711.94,209.66 775.51,247.96 839.08,264.29 902.66,402.61" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.36" points="584.79,131.35 648.37,192.67 711.94,220.21 775.51,250.95 839.08,266.05 902.66,404.05" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.37" points="584.79,136.06 648.37,165.25 711.94,196.82 775.51,242.84 839.08,266.53 902.66,404.65" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.38" points="584.79,137.89 648.37,193.88 711.94,224.02 775.51,256.54 839.08,265.88 902.66,404.55" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.39" points="584.79,144.21 648.37,185.29 711.94,211.92 775.51,248.61 839.08,268.19 902.66,403.09" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.40" points="584.79,142.99 648.37,185.55 711.94,195.37 775.51,250.03 839.08,264.2 902.66,403.97" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.41" points="584.79,138.21 648.37,194.89 711.94,220.34 775.51,264.77 839.08,275.79 902.66,406.77" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.42" points="584.79,139.82 648.37,178.49 711.94,204.13 775.51,251.1 839.08,268.47 902.66,400.02" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.43" points="584.79,138.35 648.37,177.18 711.94,208.11 775.51,256.43 839.08,267.73 902.66,404.02" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.44" points="584.79,140.88 648.37,200.55 711.94,201.01 775.51,256.42 839.08,268.4 902.66,404.85" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.45" points="584.79,114.42 648.37,182.9 711.94,211.87 775.51,253.51 839.08,270.52 902.66,405.95" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.46" points="584.79,145.44 648.37,187.31 711.94,205.19 775.51,251.14 839.08,264.67 902.66,404.43" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.47" points="584.79,131.09 648.37,186.6 711.94,203.95 775.51,255.73 839.08,265.01 902.66,403.79" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.48" points="584.79,144.37 648.37,180.44 711.94,207.31 775.51,250.38 839.08,269.67 902.66,408.08" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.49" points="584.79,129.89 648.37,174.8 711.94,218.32 775.51,249.86 839.08,266.53 902.66,403.5" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.50" points="584.79,132.97 648.37,182.27 711.94,205.57 775.51,249.88 839.08,263.02 902.66,403.91" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.51" points="584.79,135.96 648.37,186.59 711.94,219.27 775.51,254.29 839.08,266.64 902.66,403.82" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                    <polyline id="GRID.polyline.130.1.52" points="584.79,136.18 648.37,187.02 711.94,208.4 775.51,252.79 839.08,266.37 902.66,403.83" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                  </g>
                  <g id="hlines.gTree.133.1" class="gTree grob gDesc">
                    <g id="GRID.segments.131.1" class="segments grob gDesc">
                      <polyline id="GRID.segments.131.1.1" points="546.65,203.57 940.8,203.57" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="GRID.polyline.134.1" class="polyline grob gDesc">
                    <polyline id="GRID.polyline.134.1.1" points="584.79,136.18 648.37,187.02 711.94,208.4 775.51,252.79 839.08,266.37 902.66,403.83" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.37::layout::axis-l.3-3-3-3.1" class="pushedvp viewport">
                <g id="GRID.VP.33::GRID.VP.37::layout::axis-l.3-3-3-3::GRID.VP.39.1" class="pushedvp viewport">
                  <g id="axis-l.3-3-3-3.2" class="gTableChild absoluteGrob gTree grob gDesc">
                    <g id="GRID.VP.33::GRID.VP.37::layout::axis-l.3-3-3-3::GRID.VP.39::axis.1" class="pushedvp viewport">
                      <g id="GRID.gTableParent.197.1" class="gTableParent gTree grob gDesc">
                        <g id="GRID.VP.33::GRID.VP.37::layout::axis-l.3-3-3-3::GRID.VP.39::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                          <g id="axis.1-1-1-1.3" class="gTableChild text grob gDesc">
                            <g id="axis.1-1-1-1.3.1" transform="translate(537.2, 203.57)" stroke-width="0.1">
                              <g id="axis.1-1-1-1.3.1.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.1-1-1-1.3.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.1-1-1-1.3.1.tspan.1" dy="5.5" x="0">0.00</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.1-1-1-1.3.2" transform="translate(537.2, 360.85)" stroke-width="0.1">
                              <g id="axis.1-1-1-1.3.2.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.1-1-1-1.3.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.1-1-1-1.3.2.tspan.1" dy="5.5" x="0">0.05</tspan>
                                </text>
                              </g>
                            </g>
                          </g>
                        </g>
                        <g id="GRID.VP.33::GRID.VP.37::layout::axis-l.3-3-3-3::GRID.VP.39::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                          <g id="axis.1-2-1-2.2" class="gTableChild polyline grob gDesc">
                            <polyline id="axis.1-2-1-2.2.1" points="540.98,203.57 546.65,203.57" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-2-1-2.2.2" points="540.98,360.85 546.65,360.85" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.37::layout::axis-b.4-4-4-4.1" class="pushedvp viewport">
                <g id="GRID.VP.33::GRID.VP.37::layout::axis-b.4-4-4-4::GRID.VP.38.1" class="pushedvp viewport">
                  <g id="axis-b.4-4-4-4.2" class="gTableChild absoluteGrob gTree grob gDesc">
                    <g id="GRID.VP.33::GRID.VP.37::layout::axis-b.4-4-4-4::GRID.VP.38::axis.1" class="pushedvp viewport">
                      <g id="GRID.gTableParent.201.1" class="gTableParent gTree grob gDesc">
                        <g id="GRID.VP.33::GRID.VP.37::layout::axis-b.4-4-4-4::GRID.VP.38::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                          <g id="axis.1-1-1-1.4" class="gTableChild polyline grob gDesc">
                            <polyline id="axis.1-1-1-1.4.1" points="584.79,46.98 584.79,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.4.2" points="648.37,46.98 648.37,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.4.3" points="711.94,46.98 711.94,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.4.4" points="775.51,46.98 775.51,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.4.5" points="839.08,46.98 839.08,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                            <polyline id="axis.1-1-1-1.4.6" points="902.66,46.98 902.66,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          </g>
                        </g>
                        <g id="GRID.VP.33::GRID.VP.37::layout::axis-b.4-4-4-4::GRID.VP.38::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                          <g id="axis.2-1-2-1.2" class="gTableChild text grob gDesc">
                            <g id="axis.2-1-2-1.2.1" transform="translate(584.79, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.2.1.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.2.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.2.1.tspan.1" dy="11" x="0">1</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.2.2" transform="translate(648.37, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.2.2.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.2.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.2.2.tspan.1" dy="11" x="0">2</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.2.3" transform="translate(711.94, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.2.3.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.2.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.2.3.tspan.1" dy="11" x="0">3</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.2.4" transform="translate(775.51, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.2.4.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.2.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.2.4.tspan.1" dy="11" x="0">4</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.2.5" transform="translate(839.08, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.2.5.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.2.5.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.2.5.tspan.1" dy="11" x="0">5</tspan>
                                </text>
                              </g>
                            </g>
                            <g id="axis.2-1-2-1.2.6" transform="translate(902.66, 43.2)" stroke-width="0.1">
                              <g id="axis.2-1-2-1.2.6.scale" transform="scale(1, -1)">
                                <text x="0" y="0" id="axis.2-1-2-1.2.6.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                  <tspan id="axis.2-1-2-1.2.6.tspan.1" dy="11" x="0">6+</tspan>
                                </text>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.37::layout::xlab.5-4-5-4.1" class="pushedvp viewport">
                <g id="xlab.5-4-5-4.2" class="gTableChild text grob gDesc">
                  <g id="xlab.5-4-5-4.2.1" transform="translate(743.72, 20.9)" stroke-width="0.1">
                    <g id="xlab.5-4-5-4.2.1.scale" transform="scale(1, -1)">
                      <text x="0" y="0" id="xlab.5-4-5-4.2.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                        <tspan id="xlab.5-4-5-4.2.1.tspan.1" dy="6.5" x="0">Number of Children</tspan>
                      </text>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.37::layout::ylab.3-2-3-2.1" class="pushedvp viewport">
                <g id="ylab.3-2-3-2.2" class="gTableChild text grob gDesc">
                  <g id="ylab.3-2-3-2.2.1" transform="translate(500.9, 268.42)" stroke-width="0.1">
                    <g id="ylab.3-2-3-2.2.1.scale" transform="scale(1, -1)">
                      <text x="0" y="0" id="ylab.3-2-3-2.2.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                        <tspan id="ylab.3-2-3-2.2.1.tspan.1" dy="6.5" x="0">Life Satisfaction</tspan>
                      </text>
                    </g>
                  </g>
                </g>
              </g>
              <g id="GRID.VP.33::GRID.VP.37::layout::title.2-4-2-4.1" class="pushedvp viewport">
                <g id="title.2-4-2-4.2" class="gTableChild text grob gDesc">
                  <g id="title.2-4-2-4.2.1" transform="translate(743.72, 496.5)" stroke-width="0.1">
                    <g id="title.2-4-2-4.2.1.scale" transform="scale(1, -1)">
                      <text x="0" y="0" id="title.2-4-2-4.2.1.text" text-anchor="middle" font-size="19.2" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                        <tspan id="title.2-4-2-4.2.1.tspan.1" dy="7.5" x="0">Children Effects (base=No Children)</tspan>
                      </text>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
        </g>
      </g>
    </g>
  </g>
</svg>


---

### Income and Children Effects by State

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="864px" height="480px" viewBox="0 0 864 480" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-10-25 17:38:49"/>
    <gridsvg:argument name="name" value="erase_me.svg"/>
    <gridsvg:argument name="exportCoords" value="none"/>
    <gridsvg:argument name="exportMappings" value="none"/>
    <gridsvg:argument name="exportJS" value="none"/>
    <gridsvg:argument name="res" value="96"/>
    <gridsvg:argument name="prefix" value=""/>
    <gridsvg:argument name="addClasses" value="TRUE"/>
    <gridsvg:argument name="indent" value="TRUE"/>
    <gridsvg:argument name="htmlWrapper" value="FALSE"/>
    <gridsvg:argument name="usePaths" value="vpPaths"/>
    <gridsvg:argument name="uniqueNames" value="TRUE"/>
    <gridsvg:separator name="id.sep" value="."/>
    <gridsvg:separator name="gPath.sep" value="::"/>
    <gridsvg:separator name="vpPath.sep" value="::"/>
  </metadata>
  <g transform="translate(0, 480) scale(1, -1)">
    <g id="gridSVG" fill="none" stroke="rgb(0,0,0)" stroke-dasharray="none" stroke-width="1" font-size="16" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" opacity="1" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-opacity="1" fill-opacity="0" font-weight="normal" font-style="normal">
      <defs>
        <symbol id="gridSVG.pch16" viewBox="-5 -5 10 10" overflow="visible">
          <circle cx="0" cy="0" r="3.75"/>
        </symbol>
      </defs>
      <g id="layout.1" class="pushedvp viewport">
        <g id="GRID.gTableParent.260.1" class="gTableParent gTree grob gDesc">
          <defs>
            <clipPath id="layout::background.1-5-6-1.1.clipPath">
              <rect x="0" y="0" width="864" height="480" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::background.1-5-6-1.1" clip-path="url(#layout::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
            <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
              <rect id="background.1-5-6-1.1.1" x="0" y="0" width="864" height="480" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
            </g>
          </g>
          <g id="layout::spacer.4-3-4-3.1" class="pushedvp viewport"/>
          <defs>
            <clipPath id="layout::panel.3-4-3-4.1.clipPath">
              <rect x="70.65" y="52.65" width="774.15" height="383.55" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::panel.3-4-3-4.1" clip-path="url(#layout::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
            <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
              <g id="grill.gTree.238.1" class="gTree grob gDesc">
                <g id="panel.background.rect.231.1" class="rect grob gDesc">
                  <rect id="panel.background.rect.231.1.1" x="70.65" y="52.65" width="774.15" height="383.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                </g>
                <g id="panel.grid.minor.y.polyline.233.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.minor.y.polyline.233.1.1" points="70.65,131.38 844.8,131.38" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.233.1.2" points="70.65,213.49 844.8,213.49" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.233.1.3" points="70.65,295.6 844.8,295.6" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.233.1.4" points="70.65,377.71 844.8,377.71" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.y.polyline.235.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.y.polyline.235.1.1" points="70.65,90.33 844.8,90.33" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.235.1.2" points="70.65,172.44 844.8,172.44" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.235.1.3" points="70.65,254.55 844.8,254.55" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.235.1.4" points="70.65,336.66 844.8,336.66" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.235.1.5" points="70.65,418.77 844.8,418.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.x.polyline.237.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.x.polyline.237.1.1" points="159.97,52.65 159.97,436.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.237.1.2" points="308.85,52.65 308.85,436.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.237.1.3" points="457.72,52.65 457.72,436.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.237.1.4" points="606.6,52.65 606.6,436.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.237.1.5" points="755.47,52.65 755.47,436.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
              </g>
              <g id="geom_point.points.220.1" class="points grob gDesc">
                <use id="geom_point.points.220.1.1" xlink:href="#gridSVG.pch16" x="159.97" y="215.47" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.2" xlink:href="#gridSVG.pch16" x="159.97" y="223.66" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.3" xlink:href="#gridSVG.pch16" x="159.97" y="223.55" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.4" xlink:href="#gridSVG.pch16" x="159.97" y="228.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.5" xlink:href="#gridSVG.pch16" x="159.97" y="225.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.6" xlink:href="#gridSVG.pch16" x="159.97" y="258.18" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.7" xlink:href="#gridSVG.pch16" x="159.97" y="209.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.8" xlink:href="#gridSVG.pch16" x="159.97" y="220.18" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.9" xlink:href="#gridSVG.pch16" x="159.97" y="220.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.10" xlink:href="#gridSVG.pch16" x="159.97" y="205.13" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.11" xlink:href="#gridSVG.pch16" x="159.97" y="228.4" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.12" xlink:href="#gridSVG.pch16" x="159.97" y="208.87" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.13" xlink:href="#gridSVG.pch16" x="159.97" y="200.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.14" xlink:href="#gridSVG.pch16" x="159.97" y="225.1" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.15" xlink:href="#gridSVG.pch16" x="159.97" y="227.44" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.16" xlink:href="#gridSVG.pch16" x="159.97" y="225.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.17" xlink:href="#gridSVG.pch16" x="159.97" y="224.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.18" xlink:href="#gridSVG.pch16" x="159.97" y="228.39" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.19" xlink:href="#gridSVG.pch16" x="159.97" y="216.55" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.20" xlink:href="#gridSVG.pch16" x="159.97" y="227.24" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.21" xlink:href="#gridSVG.pch16" x="159.97" y="216.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.22" xlink:href="#gridSVG.pch16" x="159.97" y="216.36" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.23" xlink:href="#gridSVG.pch16" x="159.97" y="223.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.24" xlink:href="#gridSVG.pch16" x="159.97" y="230.21" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.25" xlink:href="#gridSVG.pch16" x="159.97" y="230.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.26" xlink:href="#gridSVG.pch16" x="159.97" y="243.39" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.27" xlink:href="#gridSVG.pch16" x="159.97" y="248.94" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.28" xlink:href="#gridSVG.pch16" x="159.97" y="234.69" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.29" xlink:href="#gridSVG.pch16" x="159.97" y="234.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.30" xlink:href="#gridSVG.pch16" x="159.97" y="226.32" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.31" xlink:href="#gridSVG.pch16" x="159.97" y="206.71" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.32" xlink:href="#gridSVG.pch16" x="159.97" y="234.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.33" xlink:href="#gridSVG.pch16" x="159.97" y="204.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.34" xlink:href="#gridSVG.pch16" x="159.97" y="200.2" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.35" xlink:href="#gridSVG.pch16" x="159.97" y="221.1" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.36" xlink:href="#gridSVG.pch16" x="159.97" y="232.99" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.37" xlink:href="#gridSVG.pch16" x="159.97" y="228.94" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.38" xlink:href="#gridSVG.pch16" x="159.97" y="227.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.39" xlink:href="#gridSVG.pch16" x="159.97" y="219.97" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.40" xlink:href="#gridSVG.pch16" x="159.97" y="220.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.41" xlink:href="#gridSVG.pch16" x="159.97" y="207.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.42" xlink:href="#gridSVG.pch16" x="159.97" y="210.73" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.43" xlink:href="#gridSVG.pch16" x="159.97" y="234.13" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.44" xlink:href="#gridSVG.pch16" x="159.97" y="233.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.45" xlink:href="#gridSVG.pch16" x="159.97" y="213.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.46" xlink:href="#gridSVG.pch16" x="159.97" y="203.67" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.47" xlink:href="#gridSVG.pch16" x="159.97" y="223.42" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.48" xlink:href="#gridSVG.pch16" x="159.97" y="210.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.49" xlink:href="#gridSVG.pch16" x="159.97" y="216.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.50" xlink:href="#gridSVG.pch16" x="159.97" y="229.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.51" xlink:href="#gridSVG.pch16" x="159.97" y="224.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.52" xlink:href="#gridSVG.pch16" x="159.97" y="222.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.53" xlink:href="#gridSVG.pch16" x="308.85" y="245.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.54" xlink:href="#gridSVG.pch16" x="308.85" y="205.93" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.55" xlink:href="#gridSVG.pch16" x="308.85" y="169.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.56" xlink:href="#gridSVG.pch16" x="308.85" y="218.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.57" xlink:href="#gridSVG.pch16" x="308.85" y="207.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.58" xlink:href="#gridSVG.pch16" x="308.85" y="223.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.59" xlink:href="#gridSVG.pch16" x="308.85" y="215.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.60" xlink:href="#gridSVG.pch16" x="308.85" y="204.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.61" xlink:href="#gridSVG.pch16" x="308.85" y="212.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.62" xlink:href="#gridSVG.pch16" x="308.85" y="207.51" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.63" xlink:href="#gridSVG.pch16" x="308.85" y="193.7" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.64" xlink:href="#gridSVG.pch16" x="308.85" y="200.08" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.65" xlink:href="#gridSVG.pch16" x="308.85" y="199.27" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.66" xlink:href="#gridSVG.pch16" x="308.85" y="229.36" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.67" xlink:href="#gridSVG.pch16" x="308.85" y="203.89" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.68" xlink:href="#gridSVG.pch16" x="308.85" y="195.89" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.69" xlink:href="#gridSVG.pch16" x="308.85" y="202.75" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.70" xlink:href="#gridSVG.pch16" x="308.85" y="211.21" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.71" xlink:href="#gridSVG.pch16" x="308.85" y="193.39" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.72" xlink:href="#gridSVG.pch16" x="308.85" y="230.21" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.73" xlink:href="#gridSVG.pch16" x="308.85" y="221.95" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.74" xlink:href="#gridSVG.pch16" x="308.85" y="220.44" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.75" xlink:href="#gridSVG.pch16" x="308.85" y="223.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.76" xlink:href="#gridSVG.pch16" x="308.85" y="186.92" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.77" xlink:href="#gridSVG.pch16" x="308.85" y="194.33" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.78" xlink:href="#gridSVG.pch16" x="308.85" y="211.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.79" xlink:href="#gridSVG.pch16" x="308.85" y="217.85" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.80" xlink:href="#gridSVG.pch16" x="308.85" y="180.86" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.81" xlink:href="#gridSVG.pch16" x="308.85" y="215.23" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.82" xlink:href="#gridSVG.pch16" x="308.85" y="234.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.83" xlink:href="#gridSVG.pch16" x="308.85" y="203.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.84" xlink:href="#gridSVG.pch16" x="308.85" y="205.79" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.85" xlink:href="#gridSVG.pch16" x="308.85" y="226.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.86" xlink:href="#gridSVG.pch16" x="308.85" y="168.37" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.87" xlink:href="#gridSVG.pch16" x="308.85" y="220.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.88" xlink:href="#gridSVG.pch16" x="308.85" y="208.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.89" xlink:href="#gridSVG.pch16" x="308.85" y="243.39" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.90" xlink:href="#gridSVG.pch16" x="308.85" y="213.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.91" xlink:href="#gridSVG.pch16" x="308.85" y="215.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.92" xlink:href="#gridSVG.pch16" x="308.85" y="228.49" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.93" xlink:href="#gridSVG.pch16" x="308.85" y="211.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.94" xlink:href="#gridSVG.pch16" x="308.85" y="216.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.95" xlink:href="#gridSVG.pch16" x="308.85" y="205.96" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.96" xlink:href="#gridSVG.pch16" x="308.85" y="195.49" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.97" xlink:href="#gridSVG.pch16" x="308.85" y="162.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.98" xlink:href="#gridSVG.pch16" x="308.85" y="206.8" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.99" xlink:href="#gridSVG.pch16" x="308.85" y="209.51" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.100" xlink:href="#gridSVG.pch16" x="308.85" y="212.23" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.101" xlink:href="#gridSVG.pch16" x="308.85" y="187.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.102" xlink:href="#gridSVG.pch16" x="308.85" y="185.42" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.103" xlink:href="#gridSVG.pch16" x="308.85" y="206.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.104" xlink:href="#gridSVG.pch16" x="308.85" y="208.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.105" xlink:href="#gridSVG.pch16" x="457.72" y="145.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.106" xlink:href="#gridSVG.pch16" x="457.72" y="136.08" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.107" xlink:href="#gridSVG.pch16" x="457.72" y="142.22" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.108" xlink:href="#gridSVG.pch16" x="457.72" y="137.18" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.109" xlink:href="#gridSVG.pch16" x="457.72" y="142.22" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.110" xlink:href="#gridSVG.pch16" x="457.72" y="119.86" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.111" xlink:href="#gridSVG.pch16" x="457.72" y="122.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.112" xlink:href="#gridSVG.pch16" x="457.72" y="129.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.113" xlink:href="#gridSVG.pch16" x="457.72" y="137.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.114" xlink:href="#gridSVG.pch16" x="457.72" y="127.12" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.115" xlink:href="#gridSVG.pch16" x="457.72" y="131.78" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.116" xlink:href="#gridSVG.pch16" x="457.72" y="136.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.117" xlink:href="#gridSVG.pch16" x="457.72" y="133.93" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.118" xlink:href="#gridSVG.pch16" x="457.72" y="139.79" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.119" xlink:href="#gridSVG.pch16" x="457.72" y="112.64" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.120" xlink:href="#gridSVG.pch16" x="457.72" y="133.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.121" xlink:href="#gridSVG.pch16" x="457.72" y="149.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.122" xlink:href="#gridSVG.pch16" x="457.72" y="143.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.123" xlink:href="#gridSVG.pch16" x="457.72" y="127.38" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.124" xlink:href="#gridSVG.pch16" x="457.72" y="167.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.125" xlink:href="#gridSVG.pch16" x="457.72" y="129.97" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.126" xlink:href="#gridSVG.pch16" x="457.72" y="130.88" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.127" xlink:href="#gridSVG.pch16" x="457.72" y="121.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.128" xlink:href="#gridSVG.pch16" x="457.72" y="143.22" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.129" xlink:href="#gridSVG.pch16" x="457.72" y="124.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.130" xlink:href="#gridSVG.pch16" x="457.72" y="153.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.131" xlink:href="#gridSVG.pch16" x="457.72" y="134.79" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.132" xlink:href="#gridSVG.pch16" x="457.72" y="151.83" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.133" xlink:href="#gridSVG.pch16" x="457.72" y="141.4" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.134" xlink:href="#gridSVG.pch16" x="457.72" y="122.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.135" xlink:href="#gridSVG.pch16" x="457.72" y="132.76" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.136" xlink:href="#gridSVG.pch16" x="457.72" y="128.66" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.137" xlink:href="#gridSVG.pch16" x="457.72" y="130.02" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.138" xlink:href="#gridSVG.pch16" x="457.72" y="125.82" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.139" xlink:href="#gridSVG.pch16" x="457.72" y="135.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.140" xlink:href="#gridSVG.pch16" x="457.72" y="141.37" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.141" xlink:href="#gridSVG.pch16" x="457.72" y="157.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.142" xlink:href="#gridSVG.pch16" x="457.72" y="122.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.143" xlink:href="#gridSVG.pch16" x="457.72" y="153.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.144" xlink:href="#gridSVG.pch16" x="457.72" y="146.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.145" xlink:href="#gridSVG.pch16" x="457.72" y="106.82" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.146" xlink:href="#gridSVG.pch16" x="457.72" y="118.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.147" xlink:href="#gridSVG.pch16" x="457.72" y="117.02" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.148" xlink:href="#gridSVG.pch16" x="457.72" y="132.78" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.149" xlink:href="#gridSVG.pch16" x="457.72" y="105.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.150" xlink:href="#gridSVG.pch16" x="457.72" y="142.04" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.151" xlink:href="#gridSVG.pch16" x="457.72" y="119" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.152" xlink:href="#gridSVG.pch16" x="457.72" y="114.49" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.153" xlink:href="#gridSVG.pch16" x="457.72" y="153.37" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.154" xlink:href="#gridSVG.pch16" x="457.72" y="109.85" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.155" xlink:href="#gridSVG.pch16" x="457.72" y="130.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.156" xlink:href="#gridSVG.pch16" x="457.72" y="133.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.157" xlink:href="#gridSVG.pch16" x="606.6" y="257.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.158" xlink:href="#gridSVG.pch16" x="606.6" y="257.37" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.159" xlink:href="#gridSVG.pch16" x="606.6" y="280.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.160" xlink:href="#gridSVG.pch16" x="606.6" y="257.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.161" xlink:href="#gridSVG.pch16" x="606.6" y="237.56" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.162" xlink:href="#gridSVG.pch16" x="606.6" y="251.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.163" xlink:href="#gridSVG.pch16" x="606.6" y="252.85" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.164" xlink:href="#gridSVG.pch16" x="606.6" y="256.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.165" xlink:href="#gridSVG.pch16" x="606.6" y="255.33" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.166" xlink:href="#gridSVG.pch16" x="606.6" y="261.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.167" xlink:href="#gridSVG.pch16" x="606.6" y="268.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.168" xlink:href="#gridSVG.pch16" x="606.6" y="257.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.169" xlink:href="#gridSVG.pch16" x="606.6" y="259.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.170" xlink:href="#gridSVG.pch16" x="606.6" y="251.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.171" xlink:href="#gridSVG.pch16" x="606.6" y="280.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.172" xlink:href="#gridSVG.pch16" x="606.6" y="250.73" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.173" xlink:href="#gridSVG.pch16" x="606.6" y="256.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.174" xlink:href="#gridSVG.pch16" x="606.6" y="253.53" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.175" xlink:href="#gridSVG.pch16" x="606.6" y="265.63" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.176" xlink:href="#gridSVG.pch16" x="606.6" y="249.97" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.177" xlink:href="#gridSVG.pch16" x="606.6" y="243.86" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.178" xlink:href="#gridSVG.pch16" x="606.6" y="269.12" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.179" xlink:href="#gridSVG.pch16" x="606.6" y="264.73" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.180" xlink:href="#gridSVG.pch16" x="606.6" y="273.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.181" xlink:href="#gridSVG.pch16" x="606.6" y="271.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.182" xlink:href="#gridSVG.pch16" x="606.6" y="261.26" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.183" xlink:href="#gridSVG.pch16" x="606.6" y="270.8" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.184" xlink:href="#gridSVG.pch16" x="606.6" y="278.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.185" xlink:href="#gridSVG.pch16" x="606.6" y="245.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.186" xlink:href="#gridSVG.pch16" x="606.6" y="268.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.187" xlink:href="#gridSVG.pch16" x="606.6" y="262.96" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.188" xlink:href="#gridSVG.pch16" x="606.6" y="270.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.189" xlink:href="#gridSVG.pch16" x="606.6" y="258.08" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.190" xlink:href="#gridSVG.pch16" x="606.6" y="268.22" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.191" xlink:href="#gridSVG.pch16" x="606.6" y="258.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.192" xlink:href="#gridSVG.pch16" x="606.6" y="278.79" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.193" xlink:href="#gridSVG.pch16" x="606.6" y="246.22" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.194" xlink:href="#gridSVG.pch16" x="606.6" y="255.85" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.195" xlink:href="#gridSVG.pch16" x="606.6" y="259.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.196" xlink:href="#gridSVG.pch16" x="606.6" y="266.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.197" xlink:href="#gridSVG.pch16" x="606.6" y="249.18" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.198" xlink:href="#gridSVG.pch16" x="606.6" y="239.73" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.199" xlink:href="#gridSVG.pch16" x="606.6" y="280.55" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.200" xlink:href="#gridSVG.pch16" x="606.6" y="266.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.201" xlink:href="#gridSVG.pch16" x="606.6" y="268.98" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.202" xlink:href="#gridSVG.pch16" x="606.6" y="261.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.203" xlink:href="#gridSVG.pch16" x="606.6" y="264.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.204" xlink:href="#gridSVG.pch16" x="606.6" y="269.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.205" xlink:href="#gridSVG.pch16" x="606.6" y="274.72" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.206" xlink:href="#gridSVG.pch16" x="606.6" y="273.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.207" xlink:href="#gridSVG.pch16" x="606.6" y="275.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.208" xlink:href="#gridSVG.pch16" x="606.6" y="261.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.209" xlink:href="#gridSVG.pch16" x="755.47" y="271.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.210" xlink:href="#gridSVG.pch16" x="755.47" y="256.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.211" xlink:href="#gridSVG.pch16" x="755.47" y="264.38" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.212" xlink:href="#gridSVG.pch16" x="755.47" y="257.24" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.213" xlink:href="#gridSVG.pch16" x="755.47" y="253.07" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.214" xlink:href="#gridSVG.pch16" x="755.47" y="238.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.215" xlink:href="#gridSVG.pch16" x="755.47" y="224.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.216" xlink:href="#gridSVG.pch16" x="755.47" y="232.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.217" xlink:href="#gridSVG.pch16" x="755.47" y="254.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.218" xlink:href="#gridSVG.pch16" x="755.47" y="216.63" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.219" xlink:href="#gridSVG.pch16" x="755.47" y="236.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.220" xlink:href="#gridSVG.pch16" x="755.47" y="237.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.221" xlink:href="#gridSVG.pch16" x="755.47" y="234.13" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.222" xlink:href="#gridSVG.pch16" x="755.47" y="269.47" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.223" xlink:href="#gridSVG.pch16" x="755.47" y="233.61" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.224" xlink:href="#gridSVG.pch16" x="755.47" y="243.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.225" xlink:href="#gridSVG.pch16" x="755.47" y="240.78" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.226" xlink:href="#gridSVG.pch16" x="755.47" y="264.33" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.227" xlink:href="#gridSVG.pch16" x="755.47" y="257.53" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.228" xlink:href="#gridSVG.pch16" x="755.47" y="259.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.229" xlink:href="#gridSVG.pch16" x="755.47" y="250.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.230" xlink:href="#gridSVG.pch16" x="755.47" y="224.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.231" xlink:href="#gridSVG.pch16" x="755.47" y="247.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.232" xlink:href="#gridSVG.pch16" x="755.47" y="245.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.233" xlink:href="#gridSVG.pch16" x="755.47" y="252.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.234" xlink:href="#gridSVG.pch16" x="755.47" y="238.64" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.235" xlink:href="#gridSVG.pch16" x="755.47" y="248.88" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.236" xlink:href="#gridSVG.pch16" x="755.47" y="239.26" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.237" xlink:href="#gridSVG.pch16" x="755.47" y="256.27" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.238" xlink:href="#gridSVG.pch16" x="755.47" y="230.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.239" xlink:href="#gridSVG.pch16" x="755.47" y="255.96" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.240" xlink:href="#gridSVG.pch16" x="755.47" y="233.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.241" xlink:href="#gridSVG.pch16" x="755.47" y="231.41" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.242" xlink:href="#gridSVG.pch16" x="755.47" y="221.93" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.243" xlink:href="#gridSVG.pch16" x="755.47" y="243.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.244" xlink:href="#gridSVG.pch16" x="755.47" y="225.72" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.245" xlink:href="#gridSVG.pch16" x="755.47" y="258.69" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.246" xlink:href="#gridSVG.pch16" x="755.47" y="259.7" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.247" xlink:href="#gridSVG.pch16" x="755.47" y="243.7" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.248" xlink:href="#gridSVG.pch16" x="755.47" y="262.78" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.249" xlink:href="#gridSVG.pch16" x="755.47" y="211.76" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.250" xlink:href="#gridSVG.pch16" x="755.47" y="241" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.251" xlink:href="#gridSVG.pch16" x="755.47" y="236.41" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.252" xlink:href="#gridSVG.pch16" x="755.47" y="236.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.253" xlink:href="#gridSVG.pch16" x="755.47" y="220.88" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.254" xlink:href="#gridSVG.pch16" x="755.47" y="234.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.255" xlink:href="#gridSVG.pch16" x="755.47" y="247.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.256" xlink:href="#gridSVG.pch16" x="755.47" y="240.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.257" xlink:href="#gridSVG.pch16" x="755.47" y="249.99" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.258" xlink:href="#gridSVG.pch16" x="755.47" y="248.41" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.259" xlink:href="#gridSVG.pch16" x="755.47" y="224.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
                <use id="geom_point.points.220.1.260" xlink:href="#gridSVG.pch16" x="755.47" y="243.26" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="0.3"/>
              </g>
              <g id="GRID.polyline.221.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.221.1.1" points="159.97,215.47 308.85,245.09 457.72,145.03 606.6,257.35 755.47,271.14" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.2" points="159.97,223.66 308.85,205.93 457.72,136.08 606.6,257.37 755.47,256.19" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.3" points="159.97,223.55 308.85,169.15 457.72,142.22 606.6,280.52 755.47,264.38" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.4" points="159.97,228.65 308.85,218.46 457.72,137.18 606.6,257.6 755.47,257.24" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.5" points="159.97,225.09 308.85,207.74 457.72,142.22 606.6,237.56 755.47,253.07" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.6" points="159.97,258.18 308.85,223.52 457.72,119.86 606.6,251.52 755.47,238.57" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.7" points="159.97,209.74 308.85,215.84 457.72,122.14 606.6,252.85 755.47,224.14" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.8" points="159.97,220.18 308.85,204.77 457.72,129.03 606.6,256.65 755.47,232.14" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.9" points="159.97,220.52 308.85,212.43 457.72,137.74 606.6,255.33 755.47,254.84" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.10" points="159.97,205.13 308.85,207.51 457.72,127.12 606.6,261.5 755.47,216.63" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.11" points="159.97,228.4 308.85,193.7 457.72,131.78 606.6,268.6 755.47,236.01" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.12" points="159.97,208.87 308.85,200.08 457.72,136.11 606.6,257.34 755.47,237.29" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.13" points="159.97,200.06 308.85,199.27 457.72,133.93 606.6,259.01 755.47,234.13" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.14" points="159.97,225.1 308.85,229.36 457.72,139.79 606.6,251.14 755.47,269.47" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.15" points="159.97,227.44 308.85,203.89 457.72,112.64 606.6,280.68 755.47,233.61" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.16" points="159.97,225.45 308.85,195.89 457.72,133.57 606.6,250.73 755.47,243.34" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.17" points="159.97,224.09 308.85,202.75 457.72,149.15 606.6,256.84 755.47,240.78" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.18" points="159.97,228.39 308.85,211.21 457.72,143.28 606.6,253.53 755.47,264.33" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.19" points="159.97,216.55 308.85,193.39 457.72,127.38 606.6,265.63 755.47,257.53" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.20" points="159.97,227.24 308.85,230.21 457.72,167.06 606.6,249.97 755.47,259.9" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.21" points="159.97,216.03 308.85,221.95 457.72,129.97 606.6,243.86 755.47,250.31" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.22" points="159.97,216.36 308.85,220.44 457.72,130.88 606.6,269.12 755.47,224.57" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.23" points="159.97,223.74 308.85,223.31 457.72,121.31 606.6,264.73 755.47,247.28" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.24" points="159.97,230.21 308.85,186.92 457.72,143.22 606.6,273.35 755.47,245.17" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.25" points="159.97,230.19 308.85,194.33 457.72,124.35 606.6,271.77 755.47,252.77" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.26" points="159.97,243.39 308.85,211.14 457.72,153.43 606.6,261.26 755.47,238.64" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.27" points="159.97,248.94 308.85,217.85 457.72,134.79 606.6,270.8 755.47,248.88" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.28" points="159.97,234.69 308.85,180.86 457.72,151.83 606.6,278.77 755.47,239.26" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.29" points="159.97,234.14 308.85,215.23 457.72,141.4 606.6,245.29 755.47,256.27" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.30" points="159.97,226.32 308.85,234.29 457.72,122.09 606.6,268.45 755.47,230.09" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.31" points="159.97,206.71 308.85,203.09 457.72,132.76 606.6,262.96 755.47,255.96" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.32" points="159.97,234.15 308.85,205.79 457.72,128.66 606.6,270.57 755.47,233.74" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.33" points="159.97,204.9 308.85,226.15 457.72,130.02 606.6,258.08 755.47,231.41" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.34" points="159.97,200.2 308.85,168.37 457.72,125.82 606.6,268.22 755.47,221.93" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.35" points="159.97,221.1 308.85,220.54 457.72,135.14 606.6,258.31 755.47,243.68" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.36" points="159.97,232.99 308.85,208.11 457.72,141.37 606.6,278.79 755.47,225.72" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.37" points="159.97,228.94 308.85,243.39 457.72,157.28 606.6,246.22 755.47,258.69" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.38" points="159.97,227.57 308.85,213.03 457.72,122.43 606.6,255.85 755.47,259.7" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.39" points="159.97,219.97 308.85,215.45 457.72,153.52 606.6,259.28 755.47,243.7" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.40" points="159.97,220.91 308.85,228.49 457.72,146.6 606.6,266.84 755.47,262.78" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.41" points="159.97,207.15 308.85,211.45 457.72,106.82 606.6,249.18 755.47,211.76" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.42" points="159.97,210.73 308.85,216.84 457.72,118.68 606.6,239.73 755.47,241" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.43" points="159.97,234.13 308.85,205.96 457.72,117.02 606.6,280.55 755.47,236.41" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.44" points="159.97,233.46 308.85,195.49 457.72,132.78 606.6,266.58 755.47,236.43" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.45" points="159.97,213.14 308.85,162.17 457.72,105.65 606.6,268.98 755.47,220.88" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.46" points="159.97,203.67 308.85,206.8 457.72,142.04 606.6,261.48 755.47,234.54" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.47" points="159.97,223.42 308.85,209.51 457.72,119 606.6,264.06 755.47,247.31" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.48" points="159.97,210.84 308.85,212.23 457.72,114.49 606.6,269.17 755.47,240.16" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.49" points="159.97,216.9 308.85,187.15 457.72,153.37 606.6,274.72 755.47,249.99" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.50" points="159.97,229.03 308.85,185.42 457.72,109.85 606.6,273.45 755.47,248.41" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.51" points="159.97,224.11 308.85,206.81 457.72,130.68 606.6,275.06 755.47,224.11" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.221.1.52" points="159.97,222.54 308.85,208.01 457.72,133.15 606.6,261.91 755.47,243.26" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
              </g>
              <g id="GRID.polyline.222.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.222.1.1" points="159.97,222.54 308.85,208.01 457.72,133.15 606.6,261.91 755.47,243.26" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
              </g>
              <g id="geom_point.points.224.1" class="points grob gDesc">
                <use id="geom_point.points.224.1.1" xlink:href="#gridSVG.pch16" x="159.97" y="222.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.224.1.2" xlink:href="#gridSVG.pch16" x="308.85" y="208.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.224.1.3" xlink:href="#gridSVG.pch16" x="457.72" y="133.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.224.1.4" xlink:href="#gridSVG.pch16" x="606.6" y="261.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.224.1.5" xlink:href="#gridSVG.pch16" x="755.47" y="243.26" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
              </g>
              <g id="hlines.gTree.227.1" class="gTree grob gDesc">
                <g id="GRID.segments.225.1" class="segments grob gDesc">
                  <polyline id="GRID.segments.225.1.1" points="70.65,418.77 844.8,418.77" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-l.3-3-3-3.1" class="pushedvp viewport">
            <g id="layout::axis-l.3-3-3-3::GRID.VP.41.1" class="pushedvp viewport">
              <g id="axis-l.3-3-3-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-l.3-3-3-3::GRID.VP.41::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.263.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-l.3-3-3-3::GRID.VP.41::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                        <g id="axis.1-1-1-1.1.1" transform="translate(61.2, 90.33)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">-0.20</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.2" transform="translate(61.2, 172.44)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">-0.15</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.3" transform="translate(61.2, 254.55)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">-0.10</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.4" transform="translate(61.2, 336.66)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.4.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.4.tspan.1" dy="5.5" x="0">-0.05</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.5" transform="translate(61.2, 418.77)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.5.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.5.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.5.tspan.1" dy="5.5" x="0">0.00</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                    <g id="layout::axis-l.3-3-3-3::GRID.VP.41::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                      <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-2-1-2.1.1" points="64.98,90.33 70.65,90.33" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.2" points="64.98,172.44 70.65,172.44" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.3" points="64.98,254.55 70.65,254.55" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.4" points="64.98,336.66 70.65,336.66" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.5" points="64.98,418.77 70.65,418.77" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-b.4-4-4-4.1" class="pushedvp viewport">
            <g id="layout::axis-b.4-4-4-4::GRID.VP.40.1" class="pushedvp viewport">
              <g id="axis-b.4-4-4-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-b.4-4-4-4::GRID.VP.40::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.270.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-b.4-4-4-4::GRID.VP.40::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.2" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-1-1-1.2.1" points="159.97,46.98 159.97,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.2" points="308.85,46.98 308.85,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.3" points="457.72,46.98 457.72,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.4" points="606.6,46.98 606.6,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.5" points="755.47,46.98 755.47,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                    <g id="layout::axis-b.4-4-4-4::GRID.VP.40::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                      <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                        <g id="axis.2-1-2-1.1.1" transform="translate(159.97, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">Divorced</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.2" transform="translate(308.85, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">Never Married</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.3" transform="translate(457.72, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">Separated</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.4" transform="translate(606.6, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.4.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.4.tspan.1" dy="11" x="0">Unmarried Couple</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.5" transform="translate(755.47, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.5.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.5.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.5.tspan.1" dy="11" x="0">Widowed</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::xlab.5-4-5-4.1" class="pushedvp viewport">
            <g id="xlab.5-4-5-4.1" class="gTableChild text grob gDesc">
              <g id="xlab.5-4-5-4.1.1" transform="translate(457.72, 20.9)" stroke-width="0.1">
                <g id="xlab.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="xlab.5-4-5-4.1.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="xlab.5-4-5-4.1.1.tspan.1" dy="6.5" x="0">  </tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::ylab.3-2-3-2.1" class="pushedvp viewport">
            <g id="ylab.3-2-3-2.1" class="gTableChild text grob gDesc">
              <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 244.42)" stroke-width="0.1">
                <g id="ylab.3-2-3-2.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="ylab.3-2-3-2.1.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="ylab.3-2-3-2.1.1.tspan.1" dy="6.5" x="0">Life Satisfaction</tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::title.2-4-2-4.1" class="pushedvp viewport">
            <g id="title.2-4-2-4.1" class="gTableChild text grob gDesc">
              <g id="title.2-4-2-4.1.1" transform="translate(457.72, 448.5)" stroke-width="0.1">
                <g id="title.2-4-2-4.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="title.2-4-2-4.1.1.text" text-anchor="middle" font-size="19.2" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="title.2-4-2-4.1.1.tspan.1" dy="7.5" x="0">Marital Status (base=Married)</tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
        </g>
      </g>
    </g>
  </g>
</svg>


