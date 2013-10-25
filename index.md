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


















--- 

### Model: 2nd Stage

- We let $\beta$ and ${\rm Var}[\varepsilon]$ vary by category.
- We model variation in $\beta$ as 
$$
\beta_{cj} \sim {\rm N}(\pi_j + \pi^m_j D_c^m, \tau_j),\qquad j=1,\dots,K,
$$


---

### Age and Gender Effects

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="960px" height="528px" viewBox="0 0 960 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-10-25 14:59:37"/>
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
        <g id="GRID.gTableParent.51.1" class="gTableParent gTree grob gDesc">
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
              <g id="grill.gTree.29.1" class="gTree grob gDesc">
                <g id="panel.background.rect.22.1" class="rect grob gDesc">
                  <rect id="panel.background.rect.22.1.1" x="59.65" y="52.65" width="881.15" height="456.15" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                </g>
                <g id="panel.grid.minor.y.polyline.24.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.minor.y.polyline.24.1.1" points="59.65,118.51 940.8,118.51" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.24.1.2" points="59.65,248.76 940.8,248.76" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.24.1.3" points="59.65,379.01 940.8,379.01" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.y.polyline.26.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.y.polyline.26.1.1" points="59.65,53.38 940.8,53.38" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.26.1.2" points="59.65,183.63 940.8,183.63" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.26.1.3" points="59.65,313.88 940.8,313.88" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.26.1.4" points="59.65,444.13 940.8,444.13" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.x.polyline.28.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.x.polyline.28.1.1" points="94.43,52.65 94.43,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.2" points="152.4,52.65 152.4,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.3" points="210.37,52.65 210.37,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.4" points="268.34,52.65 268.34,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.5" points="326.31,52.65 326.31,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.6" points="384.28,52.65 384.28,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.7" points="442.25,52.65 442.25,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.8" points="500.22,52.65 500.22,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.9" points="558.19,52.65 558.19,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.10" points="616.17,52.65 616.17,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.11" points="674.14,52.65 674.14,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.12" points="732.11,52.65 732.11,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.13" points="790.08,52.65 790.08,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.14" points="848.05,52.65 848.05,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.28.1.15" points="906.02,52.65 906.02,508.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
              </g>
              <g id="GRID.polyline.11.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.11.1.1" points="94.43,309.79 152.4,258.03 210.37,218.53 268.34,172.32 326.31,168.87 384.28,154.11 442.25,160.58 500.22,184.14 558.19,261.43 616.17,311.29 674.14,346.52 732.11,327.11 790.08,328.26 848.05,317.39 906.02,355.8" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.2" points="94.43,326.61 152.4,264.88 210.37,235.07 268.34,194.67 326.31,169.44 384.28,155.28 442.25,174.13 500.22,213.52 558.19,286.19 616.17,343.73 674.14,373.08 732.11,341.42 790.08,334.75 848.05,344.26 906.02,372.66" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.3" points="94.43,298.16 152.4,262.73 210.37,204.4 268.34,162.98 326.31,155.98 384.28,134.27 442.25,140.96 500.22,167.5 558.19,231.09 616.17,292.67 674.14,308.85 732.11,306.06 790.08,281.79 848.05,268.75 906.02,334.23" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.4" points="94.43,299.53 152.4,260.01 210.37,215.14 268.34,179.42 326.31,169.55 384.28,144.02 442.25,156.15 500.22,180.24 558.19,253.44 616.17,327.14 674.14,359.27 732.11,348.73 790.08,328.55 848.05,326.52 906.02,357.59" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.5" points="94.43,310.13 152.4,251.23 210.37,213.45 268.34,182.87 326.31,171.05 384.28,163.98 442.25,153.49 500.22,184.54 558.19,269.35 616.17,324.79 674.14,346.8 732.11,331.67 790.08,330.63 848.05,295.9 906.02,355.85" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.6" points="94.43,343.12 152.4,305.33 210.37,257 268.34,219.98 326.31,189.88 384.28,189.77 442.25,202.23 500.22,237.14 558.19,307.91 616.17,357.53 674.14,371.26 732.11,363.31 790.08,343.39 848.05,354.2 906.02,392.23" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.7" points="94.43,314.47 152.4,236.81 210.37,210.75 268.34,171.06 326.31,142.71 384.28,139.5 442.25,141.84 500.22,168.55 558.19,253.8 616.17,308.06 674.14,318.99 732.11,308.92 790.08,298.98 848.05,290.43 906.02,340.66" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.8" points="94.43,258.12 152.4,222.99 210.37,176.73 268.34,133.5 326.31,114.19 384.28,108.01 442.25,108.4 500.22,144.31 558.19,210.3 616.17,274.18 674.14,301.66 732.11,294.19 790.08,278.3 848.05,265.78 906.02,311.06" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.9" points="94.43,227.17 152.4,188.51 210.37,138.72 268.34,120.23 326.31,83.74 384.28,73.4 442.25,82.72 500.22,114.97 558.19,195.93 616.17,265.02 674.14,276.41 732.11,269.17 790.08,255.37 848.05,255.61 906.02,287.53" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.10" points="94.43,268.99 152.4,222.97 210.37,176.28 268.34,132.12 326.31,137.91 384.28,113.72 442.25,103.87 500.22,149.65 558.19,219.47 616.17,287.48 674.14,303.51 732.11,303.18 790.08,278.37 848.05,289.16 906.02,318.3" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.11" points="94.43,321.45 152.4,281.66 210.37,227.61 268.34,194.72 326.31,165.92 384.28,161.38 442.25,164.33 500.22,197.5 558.19,265.5 616.17,332.86 674.14,351.76 732.11,340.06 790.08,329.65 848.05,323.56 906.02,364.88" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.12" points="94.43,286.74 152.4,228.64 210.37,194.09 268.34,149.68 326.31,134.42 384.28,103.34 442.25,113.69 500.22,150.69 558.19,205.86 616.17,281.79 674.14,316.49 732.11,295.64 790.08,277.79 848.05,290.12 906.02,321.21" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.13" points="94.43,290.37 152.4,228.82 210.37,194.45 268.34,147.5 326.31,141.91 384.28,113.37 442.25,114.84 500.22,149.09 558.19,225.1 616.17,280.66 674.14,310 732.11,306.17 790.08,292.11 848.05,293.65 906.02,325.75" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.14" points="94.43,375.46 152.4,318.99 210.37,268.23 268.34,251.27 326.31,221.21 384.28,214.93 442.25,219.74 500.22,252.4 558.19,311.01 616.17,362.78 674.14,400.63 732.11,383.34 790.08,384.39 848.05,381.01 906.02,414.44" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.15" points="94.43,287.74 152.4,216.79 210.37,181.18 268.34,145.62 326.31,146.46 384.28,137.55 442.25,136.86 500.22,165.37 558.19,226.71 616.17,295.65 674.14,314.02 732.11,314.13 790.08,299.59 848.05,280.08 906.02,330.07" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.16" points="94.43,265.76 152.4,217.71 210.37,178.35 268.34,146.86 326.31,154.83 384.28,118.64 442.25,109.27 500.22,165.17 558.19,243.4 616.17,293.51 674.14,318.08 732.11,302.95 790.08,286.6 848.05,266.19 906.02,322.75" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.17" points="94.43,255.68 152.4,212.04 210.37,174.06 268.34,128.47 326.31,113.58 384.28,84.02 442.25,104.83 500.22,111.59 558.19,209.71 616.17,269.06 674.14,291.16 732.11,286.33 790.08,282.25 848.05,275.5 906.02,305.45" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.18" points="94.43,247.76 152.4,192.47 210.37,150.05 268.34,120.11 326.31,87.58 384.28,85 442.25,82.51 500.22,136.69 558.19,217.53 616.17,286.03 674.14,313.34 732.11,297.29 790.08,276.65 848.05,277.63 906.02,301.91" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.19" points="94.43,288.22 152.4,228.26 210.37,195.33 268.34,149.43 326.31,143.57 384.28,124.86 442.25,133.55 500.22,152.71 558.19,233.79 616.17,295.75 674.14,317.78 732.11,303.76 790.08,294.07 848.05,294.86 906.02,330.06" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.20" points="94.43,340.48 152.4,283.06 210.37,246.51 268.34,213.75 326.31,205.94 384.28,185.56 442.25,193.32 500.22,224.6 558.19,297.18 616.17,344.23 674.14,371.5 732.11,357.85 790.08,352.14 848.05,352.27 906.02,387.41" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.21" points="94.43,273.23 152.4,202.92 210.37,180.33 268.34,129.78 326.31,116.63 384.28,100.79 442.25,98.61 500.22,131.59 558.19,223.86 616.17,267.65 674.14,298.77 732.11,291.64 790.08,276.04 848.05,268.78 906.02,309.16" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.22" points="94.43,313.14 152.4,255.49 210.37,233.2 268.34,189.74 326.31,170.64 384.28,155.54 442.25,169.92 500.22,191.11 558.19,255.54 616.17,310.77 674.14,330.52 732.11,334.51 790.08,310.11 848.05,305.02 906.02,356.66" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.23" points="94.43,259.23 152.4,214.67 210.37,161.17 268.34,103.84 326.31,116.86 384.28,88.73 442.25,94.14 500.22,121.7 558.19,183.86 616.17,253.39 674.14,256.97 732.11,248.13 790.08,233.91 848.05,244.14 906.02,289.98" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.24" points="94.43,270.67 152.4,208.73 210.37,166.73 268.34,134.09 326.31,120.64 384.28,100.23 442.25,121.7 500.22,156.45 558.19,244.36 616.17,276.67 674.14,288.36 732.11,282.81 790.08,286.3 848.05,280.86 906.02,314.91" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.25" points="94.43,264.83 152.4,201.72 210.37,187 268.34,132.17 326.31,138.54 384.28,120.49 442.25,127.46 500.22,147.77 558.19,219.57 616.17,291.31 674.14,312.57 732.11,290.41 790.08,274.3 848.05,273.19 906.02,317.81" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.26" points="94.43,249.76 152.4,197.77 210.37,175.99 268.34,144.27 326.31,119.53 384.28,102.78 442.25,92.87 500.22,135.87 558.19,206.89 616.17,252.39 674.14,297.71 732.11,281.1 790.08,264.79 848.05,248.64 906.02,302.41" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.27" points="94.43,314.71 152.4,241.15 210.37,214.33 268.34,182.97 326.31,160.74 384.28,160.05 442.25,153.76 500.22,180.83 558.19,238.1 616.17,308.69 674.14,321.23 732.11,309.48 790.08,298.52 848.05,298.43 906.02,345.83" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.28" points="94.43,241.58 152.4,178.86 210.37,161.81 268.34,103.58 326.31,98.53 384.28,76.22 442.25,73.38 500.22,111.59 558.19,191.13 616.17,234.79 674.14,272.59 732.11,244.34 790.08,241.09 848.05,226.6 906.02,281.21" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.29" points="94.43,296.97 152.4,240.22 210.37,212.81 268.34,176.12 326.31,138.71 384.28,135.5 442.25,132.98 500.22,166.57 558.19,254.02 616.17,322.83 674.14,328.12 732.11,319.42 790.08,304.85 848.05,302.86 906.02,342.6" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.30" points="94.43,274.02 152.4,222.11 210.37,178.84 268.34,126 326.31,116.6 384.28,104.63 442.25,112.74 500.22,130.64 558.19,204.54 616.17,259.82 674.14,274.83 732.11,261.77 790.08,238.53 848.05,253.82 906.02,302.23" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.31" points="94.43,241.68 152.4,192.18 210.37,143.99 268.34,114.05 326.31,96.48 384.28,78.53 442.25,93.81 500.22,118.98 558.19,202.94 616.17,267.75 674.14,291.84 732.11,287.76 790.08,281.33 848.05,261.25 906.02,296.15" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.32" points="94.43,320.36 152.4,275.61 210.37,223.1 268.34,194.23 326.31,187.43 384.28,166.3 442.25,152.04 500.22,201.96 558.19,270.05 616.17,336.41 674.14,354.41 732.11,354.94 790.08,330.36 848.05,322.43 906.02,367.33" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.33" points="94.43,275.17 152.4,232.21 210.37,175.65 268.34,155.4 326.31,138.47 384.28,114.91 442.25,116.52 500.22,140.15 558.19,223.7 616.17,273.92 674.14,296.26 732.11,287.56 790.08,279.9 848.05,270.2 906.02,318.73" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.34" points="94.43,300.13 152.4,236.11 210.37,209.35 268.34,174.48 326.31,150.94 384.28,141.47 442.25,139.57 500.22,175.16 558.19,260 616.17,314.55 674.14,327.56 732.11,329.69 790.08,307.38 848.05,312.45 906.02,345.88" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.35" points="94.43,268.75 152.4,206.76 210.37,168.65 268.34,137.94 326.31,114.91 384.28,98.45 442.25,96 500.22,125.92 558.19,227.3 616.17,270.79 674.14,321.24 732.11,284.54 790.08,266.99 848.05,258.08 906.02,307.81" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.36" points="94.43,243.7 152.4,191.55 210.37,161.15 268.34,116.21 326.31,105.16 384.28,89.43 442.25,77.54 500.22,120.37 558.19,188.43 616.17,261.18 674.14,287.82 732.11,274.85 790.08,268.19 848.05,263.56 906.02,294.66" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.37" points="94.43,319.41 152.4,280.6 210.37,232.35 268.34,200.09 326.31,173.09 384.28,175.85 442.25,183.92 500.22,204.31 558.19,299.79 616.17,338.91 674.14,370.11 732.11,356.93 790.08,349.99 848.05,340.68 906.02,377.47" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.38" points="94.43,282.45 152.4,221.96 210.37,184.82 268.34,134.36 326.31,109.61 384.28,92.18 442.25,95.86 500.22,139.87 558.19,197.95 616.17,248.07 674.14,272.32 732.11,263.19 790.08,242.95 848.05,256.32 906.02,301.6" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.39" points="94.43,336.21 152.4,288.52 210.37,236.06 268.34,195.7 326.31,182.17 384.28,168.54 442.25,168.91 500.22,195.71 558.19,270.18 616.17,328.1 674.14,358.04 732.11,337.84 790.08,336.09 848.05,338.7 906.02,372.32" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.40" points="94.43,300.77 152.4,246.22 210.37,210.12 268.34,177.17 326.31,171.58 384.28,149.55 442.25,140.34 500.22,181.66 558.19,236.94 616.17,291.19 674.14,328.28 732.11,317.52 790.08,312.54 848.05,299.44 906.02,344.9" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.41" points="94.43,309.49 152.4,260.37 210.37,208.9 268.34,143.36 326.31,129.3 384.28,113.61 442.25,123.4 500.22,151.7 558.19,223.2 616.17,282.15 674.14,302.29 732.11,287.32 790.08,281.73 848.05,276.18 906.02,326.52" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.42" points="94.43,318.27 152.4,274.44 210.37,229.11 268.34,193.43 326.31,171.91 384.28,152.74 442.25,162.27 500.22,191.87 558.19,272.17 616.17,308.03 674.14,353.59 732.11,333.68 790.08,329.58 848.05,324.08 906.02,361.28" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.43" points="94.43,283.95 152.4,235.25 210.37,211.7 268.34,166.67 326.31,141.58 384.28,138.42 442.25,147.02 500.22,170.53 558.19,236.97 616.17,284.71 674.14,322.65 732.11,314.59 790.08,300.44 848.05,292.51 906.02,336.13" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.44" points="94.43,300.16 152.4,228.37 210.37,208.7 268.34,161.36 326.31,148.07 384.28,140.66 442.25,133.64 500.22,173.15 558.19,248.11 616.17,313.93 674.14,329.55 732.11,315.48 790.08,294.51 848.05,290.36 906.02,338.69" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.45" points="94.43,276.39 152.4,231.31 210.37,198.37 268.34,149.33 326.31,135.64 384.28,115.05 442.25,129.44 500.22,167.58 558.19,248.58 616.17,309.22 674.14,328.88 732.11,325.02 790.08,300.94 848.05,297.01 906.02,333.9" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.46" points="94.43,297.29 152.4,247.08 210.37,198.04 268.34,186.33 326.31,145.11 384.28,138.81 442.25,136.56 500.22,169.26 558.19,247.44 616.17,301.74 674.14,324 732.11,340.68 790.08,317.31 848.05,321.76 906.02,345.61" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.47" points="94.43,275.9 152.4,210.31 210.37,168.41 268.34,133.75 326.31,121.22 384.28,115.04 442.25,111.86 500.22,143.93 558.19,250.11 616.17,275.75 674.14,306.69 732.11,311.32 790.08,295.02 848.05,282.9 906.02,318.86" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.48" points="94.43,314.46 152.4,257.09 210.37,218.15 268.34,171.47 326.31,171.35 384.28,154.2 442.25,153.59 500.22,177.67 558.19,255.57 616.17,310.25 674.14,332.79 732.11,310.28 790.08,302.61 848.05,304.26 906.02,350.01" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.49" points="94.43,264.38 152.4,230.76 210.37,187.7 268.34,152.78 326.31,145.57 384.28,117.67 442.25,129.78 500.22,155.71 558.19,224.57 616.17,307.72 674.14,319.62 732.11,303.35 790.08,311.19 848.05,286.36 906.02,327.27" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.50" points="94.43,272.34 152.4,245.74 210.37,217.3 268.34,166.09 326.31,159.51 384.28,137.47 442.25,130.11 500.22,174.98 558.19,243.86 616.17,318.23 674.14,339 732.11,330.01 790.08,311.92 848.05,302.87 906.02,343.86" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.51" points="94.43,237.56 152.4,192.92 210.37,138.59 268.34,121.24 326.31,86.44 384.28,84.18 442.25,81.34 500.22,108.63 558.19,189.39 616.17,257.52 674.14,287.7 732.11,258.05 790.08,244.52 848.05,238.39 906.02,286.39" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.11.1.52" points="94.43,288.48 152.4,235.9 210.37,197.22 268.34,158.52 326.31,143.17 384.28,128.09 442.25,130.95 500.22,163.01 558.19,238.51 616.17,296.33 674.14,320.54 732.11,309.21 790.08,296.62 848.05,291.86 906.02,333.1" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
              </g>
              <g id="GRID.polyline.12.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.12.1.1" points="94.43,288.48 152.4,235.9 210.37,197.22 268.34,158.52 326.31,143.17 384.28,128.09 442.25,130.95 500.22,163.01 558.19,238.51 616.17,296.33 674.14,320.54 732.11,309.21 790.08,296.62 848.05,291.86 906.02,333.1" stroke="rgb(0,255,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
              </g>
              <g id="geom_point.points.14.1" class="points grob gDesc">
                <use id="geom_point.points.14.1.1" xlink:href="#gridSVG.pch16" x="906.02" y="333.1" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.2" xlink:href="#gridSVG.pch16" x="94.43" y="288.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.3" xlink:href="#gridSVG.pch16" x="152.4" y="235.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.4" xlink:href="#gridSVG.pch16" x="210.37" y="197.22" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.5" xlink:href="#gridSVG.pch16" x="268.34" y="158.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.6" xlink:href="#gridSVG.pch16" x="326.31" y="143.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.7" xlink:href="#gridSVG.pch16" x="384.28" y="128.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.8" xlink:href="#gridSVG.pch16" x="442.25" y="130.95" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.9" xlink:href="#gridSVG.pch16" x="500.22" y="163.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.10" xlink:href="#gridSVG.pch16" x="558.19" y="238.51" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.11" xlink:href="#gridSVG.pch16" x="616.17" y="296.33" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.12" xlink:href="#gridSVG.pch16" x="674.14" y="320.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.13" xlink:href="#gridSVG.pch16" x="732.11" y="309.21" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.14" xlink:href="#gridSVG.pch16" x="790.08" y="296.62" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.14.1.15" xlink:href="#gridSVG.pch16" x="848.05" y="291.86" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,255,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
              </g>
              <g id="GRID.polyline.15.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.15.1.1" points="94.43,336.34 152.4,286.1 210.37,252.6 268.34,212.26 326.31,218.95 384.28,211.02 442.25,231.17 500.22,241.32 558.19,330.26 616.17,362.92 674.14,407.7 732.11,389.65 790.08,426.78 848.05,422.76 906.02,330.3" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.2" points="94.43,341.83 152.4,281.85 210.37,272.04 268.34,251.11 326.31,229.56 384.28,216.44 442.25,239.82 500.22,277.69 558.19,353.05 616.17,391.96 674.14,427.88 732.11,402.28 790.08,422.22 848.05,450.65 906.02,327.63" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.3" points="94.43,322.53 152.4,304.32 210.37,229.92 268.34,222.47 326.31,216.36 384.28,199.79 442.25,221.83 500.22,241.36 558.19,296.61 616.17,349.75 674.14,357.76 732.11,369.53 790.08,348.77 848.05,344.16 906.02,321.4" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.4" points="94.43,329.5 152.4,288.61 210.37,251.28 268.34,229.59 326.31,232.27 384.28,213.37 442.25,220.44 500.22,237.91 558.19,315.43 616.17,378.02 674.14,402.45 732.11,412.81 790.08,428.4 848.05,412.09 906.02,339.74" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.5" points="94.43,338.45 152.4,286.32 210.37,253.76 268.34,224.12 326.31,216.88 384.28,242.89 442.25,234.53 500.22,255.73 558.19,338 616.17,374.42 674.14,384.25 732.11,392.36 790.08,413.3 848.05,387.58 906.02,328.88" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.6" points="94.43,358.84 152.4,349.23 210.37,298.19 268.34,264.77 326.31,235.33 384.28,263.73 442.25,280.52 500.22,312.09 558.19,366.17 616.17,392.39 674.14,412.43 732.11,439.98 790.08,431 848.05,449 906.02,373.89" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.7" points="94.43,350.8 152.4,276.47 210.37,240.25 268.34,226.94 326.31,195.28 384.28,199.07 442.25,222.78 500.22,246.05 558.19,304.34 616.17,358.45 674.14,364.34 732.11,367.35 790.08,394.75 848.05,377.29 906.02,330.36" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.8" points="94.43,277.22 152.4,255.79 210.37,212.05 268.34,187.94 326.31,173.67 384.28,171.93 442.25,176.05 500.22,212.75 558.19,277.42 616.17,328.8 674.14,356.88 732.11,347.15 790.08,370.33 848.05,353.22 906.02,286.97" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.9" points="94.43,243.07 152.4,219.52 210.37,168.27 268.34,169.24 326.31,132.96 384.28,136.4 442.25,154.01 500.22,194.47 558.19,250.64 616.17,313.41 674.14,331.39 732.11,338.1 790.08,348.82 848.05,353.39 906.02,271.18" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.10" points="94.43,278.61 152.4,248.67 210.37,224.67 268.34,185.91 326.31,188.79 384.28,184.89 442.25,180.38 500.22,216.67 558.19,276.1 616.17,346.64 674.14,347.24 732.11,358.59 790.08,368.35 848.05,393.82 906.02,311.21" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.11" points="94.43,339.25 152.4,316.74 210.37,259.13 268.34,245.72 326.31,220.16 384.28,223 442.25,238.12 500.22,272.61 558.19,315.48 616.17,393.47 674.14,398.27 732.11,406.03 790.08,424.5 848.05,418.04 906.02,339" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.12" points="94.43,316.54 152.4,263.31 210.37,233.71 268.34,203.44 326.31,179 384.28,179.13 442.25,175.56 500.22,214.81 558.19,265.27 616.17,329.02 674.14,359.02 732.11,360.09 790.08,364.58 848.05,389.12 906.02,309.36" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.13" points="94.43,321.48 152.4,264.81 210.37,230.94 268.34,212.58 326.31,196.03 384.28,171.76 442.25,181.36 500.22,217.86 558.19,273.81 616.17,331.5 674.14,341.88 732.11,362.12 790.08,390.11 848.05,397.81 906.02,307.5" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.14" points="94.43,394.75 152.4,353.94 210.37,301.67 268.34,299.59 326.31,264.72 384.28,278.77 442.25,274.73 500.22,323.06 558.19,365.15 616.17,413.53 674.14,453.41 732.11,452.07 790.08,483.23 848.05,488.07 906.02,384.02" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.15" points="94.43,311.5 152.4,251.19 210.37,215.5 268.34,200.99 326.31,204.47 384.28,208.4 442.25,217.7 500.22,237.92 558.19,276.37 616.17,331.05 674.14,366.39 732.11,375.84 790.08,396.6 848.05,369.95 906.02,336.09" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.16" points="94.43,288.89 152.4,247.54 210.37,209.8 268.34,204.38 326.31,214.04 384.28,171.85 442.25,192.62 500.22,230.66 558.19,300.25 616.17,343.01 674.14,367.27 732.11,375.2 790.08,382.6 848.05,355.25 906.02,302.73" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.17" points="94.43,261.23 152.4,240.51 210.37,217.2 268.34,190.55 326.31,165.66 384.28,148.55 442.25,180.28 500.22,189.2 558.19,260.39 616.17,318.89 674.14,339.12 732.11,347.65 790.08,383.11 848.05,364.39 906.02,290.97" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.18" points="94.43,270.7 152.4,218.31 210.37,183.36 268.34,163.57 326.31,137.27 384.28,152.68 442.25,169.84 500.22,199.63 558.19,286.77 616.17,339.47 674.14,360.88 732.11,365.69 790.08,354.09 848.05,384.34 906.02,290.61" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.19" points="94.43,310.34 152.4,261.73 210.37,234.12 268.34,185.64 326.31,200.76 384.28,204.29 442.25,220.51 500.22,225.29 558.19,290.22 616.17,345.61 674.14,367.55 732.11,364.16 790.08,378.33 848.05,391.9 906.02,330.43" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.20" points="94.43,356.51 152.4,302.72 210.37,279.61 268.34,263.41 326.31,269.38 384.28,249.28 442.25,264.22 500.22,288.4 558.19,350.59 616.17,395.37 674.14,423.53 732.11,414.79 790.08,450.52 848.05,449.72 906.02,340.71" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.21" points="94.43,299.79 152.4,239.7 210.37,217.39 268.34,176.44 326.31,171.53 384.28,170.87 442.25,171.6 500.22,201.57 558.19,288.09 616.17,301.79 674.14,346.95 732.11,358.13 790.08,364.25 848.05,361.27 906.02,289.15" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.22" points="94.43,338.34 152.4,297.53 210.37,275.99 268.34,238.84 326.31,218.52 384.28,207.37 442.25,261.02 500.22,263.5 558.19,318.86 616.17,358.2 674.14,370.88 732.11,400.34 790.08,399.1 848.05,386.42 906.02,342.49" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.23" points="94.43,278.19 152.4,266.78 210.37,200.99 268.34,158.24 326.31,158.92 384.28,166.96 442.25,166.5 500.22,189.91 558.19,232.97 616.17,295.41 674.14,310.43 732.11,305.29 790.08,319.19 848.05,341.94 906.02,286.89" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.24" points="94.43,289.16 152.4,231.01 210.37,192.78 268.34,194.96 326.31,180.16 384.28,167.71 442.25,197.89 500.22,231.71 558.19,295.9 616.17,334.72 674.14,332.16 732.11,350.94 790.08,372.38 848.05,376.39 906.02,287.24" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.25" points="94.43,276.08 152.4,232.05 210.37,225.94 268.34,178.85 326.31,187.28 384.28,197.74 442.25,212.62 500.22,224.51 558.19,292.83 616.17,342.55 674.14,359.51 732.11,340.59 790.08,361.35 848.05,360.68 906.02,306.08" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.26" points="94.43,269.84 152.4,224.83 210.37,226.84 268.34,209.17 326.31,179.12 384.28,176.11 442.25,168.84 500.22,200.49 558.19,267.1 616.17,301.43 674.14,334.41 732.11,345.24 790.08,355.05 848.05,332.84 906.02,287.74" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.27" points="94.43,345.16 152.4,268.98 210.37,247.17 268.34,221.72 326.31,210.68 384.28,226.82 442.25,240.49 500.22,243.95 558.19,314.09 616.17,353.44 674.14,364.79 732.11,368.41 790.08,383.98 848.05,399.87 906.02,315.01" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.28" points="94.43,261.09 152.4,212.91 210.37,199.51 268.34,162.01 326.31,163.83 384.28,143.17 442.25,156.42 500.22,170.8 558.19,257.88 616.17,279.55 674.14,321.58 732.11,290.68 790.08,327.67 848.05,318.66 906.02,274.99" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.29" points="94.43,316.02 152.4,267.08 210.37,240.88 268.34,233.69 326.31,201.72 384.28,210 442.25,208.56 500.22,233.44 558.19,307.84 616.17,374.55 674.14,386.16 732.11,366.85 790.08,377.38 848.05,410.72 906.02,316.15" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.30" points="94.43,307.18 152.4,264.23 210.37,216.36 268.34,170.63 326.31,163.32 384.28,164.68 442.25,189.28 500.22,205.77 558.19,278.48 616.17,314.95 674.14,310.07 732.11,318.31 790.08,318.22 848.05,353.13 906.02,298.6" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.31" points="94.43,270.88 152.4,228.06 210.37,173.81 268.34,181.61 326.31,156.17 384.28,137.03 442.25,152.93 500.22,179.17 558.19,265.29 616.17,308.01 674.14,339.66 732.11,367.25 790.08,375.31 848.05,351.11 906.02,294.98" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.32" points="94.43,340.83 152.4,314.06 210.37,253.38 268.34,245.57 326.31,254.3 384.28,220.87 442.25,227.74 500.22,258.37 558.19,312.08 616.17,403.52 674.14,411 732.11,430.3 790.08,424.54 848.05,412.6 906.02,355.16" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.33" points="94.43,294.37 152.4,273.63 210.37,205.75 268.34,215.84 326.31,186.63 384.28,180.4 442.25,178.04 500.22,200.74 558.19,275.38 616.17,340.14 674.14,351 732.11,345.15 790.08,372.29 848.05,371.21 906.02,315.8" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.34" points="94.43,317.84 152.4,259.64 210.37,253.45 268.34,224.77 326.31,210.92 384.28,205.08 442.25,214.96 500.22,256.83 558.19,313.35 616.17,382.12 674.14,355.53 732.11,388 790.08,392.37 848.05,416.56 906.02,339.46" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.35" points="94.43,303.91 152.4,239.82 210.37,222.39 268.34,196.11 326.31,177.58 384.28,172.96 442.25,178.73 500.22,187.29 558.19,284.69 616.17,313.18 674.14,356.56 732.11,351.93 790.08,336.88 848.05,342.97 906.02,282.97" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.36" points="94.43,261.02 152.4,222.77 210.37,194.8 268.34,174.66 326.31,168.1 384.28,170.95 442.25,147.73 500.22,190.44 558.19,250.7 616.17,304.43 674.14,327.63 732.11,333.04 790.08,350.09 848.05,351.08 906.02,264.36" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.37" points="94.43,333.42 152.4,312.81 210.37,263.87 268.34,256.63 326.31,231.37 384.28,234.11 442.25,241.18 500.22,289.53 558.19,360.28 616.17,390.42 674.14,418.5 732.11,421.25 790.08,432.15 848.05,439.37 906.02,337.66" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.38" points="94.43,308.25 152.4,264.78 210.37,217.65 268.34,184.1 326.31,152.23 384.28,169.66 442.25,172.86 500.22,222.12 558.19,250.65 616.17,294.91 674.14,312.34 732.11,336.39 790.08,324.4 848.05,350.12 906.02,304.01" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.39" points="94.43,360.93 152.4,336.54 210.37,274.98 268.34,244.17 326.31,230.98 384.28,229 442.25,243.56 500.22,259.47 558.19,324.79 616.17,371.26 674.14,398.23 732.11,394.74 790.08,429.87 848.05,436.54 906.02,333.2" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.40" points="94.43,316.43 152.4,290.12 210.37,242.4 268.34,227.93 326.31,216.51 384.28,212.4 442.25,205.44 500.22,249.5 558.19,304.84 616.17,355.25 674.14,371.95 732.11,374.06 790.08,404.26 848.05,395.41 906.02,331.51" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.41" points="94.43,334.05 152.4,295.31 210.37,245.06 268.34,202.2 326.31,176.84 384.28,176.43 442.25,194.7 500.22,230.97 558.19,276.01 616.17,330.73 674.14,357.06 732.11,351.98 790.08,364.78 848.05,369.19 906.02,325.45" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.42" points="94.43,335.75 152.4,308.64 210.37,277.32 268.34,249.1 326.31,224.77 384.28,230.52 442.25,236.15 500.22,257.83 558.19,334.3 616.17,351.46 674.14,386.81 732.11,394.99 790.08,420.45 848.05,421.79 906.02,327.03" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.43" points="94.43,292.52 152.4,266.16 210.37,243.76 268.34,220.39 326.31,200.63 384.28,214.16 442.25,226.56 500.22,234.33 558.19,297.02 616.17,343.87 674.14,377 732.11,372.86 790.08,389.32 848.05,382.57 906.02,324.86" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.44" points="94.43,323.82 152.4,264.16 210.37,245.84 268.34,211.66 326.31,189.42 384.28,217.18 442.25,201.85 500.22,243.24 558.19,312.55 616.17,377.87 674.14,377.61 732.11,377.11 790.08,382.21 848.05,378.04 906.02,320.03" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.45" points="94.43,285.91 152.4,264.01 210.37,223.81 268.34,203.83 326.31,194.64 384.28,188.75 442.25,196.74 500.22,245.36 558.19,317.94 616.17,362.04 674.14,362.76 732.11,393.65 790.08,406.3 848.05,381.2 906.02,329.02" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.46" points="94.43,315.85 152.4,284.15 210.37,237.53 268.34,244.62 326.31,195.17 384.28,198.27 442.25,206.9 500.22,246.08 558.19,307.29 616.17,343.51 674.14,368.98 732.11,409.96 790.08,403.61 848.05,418.15 906.02,325.5" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.47" points="94.43,302.08 152.4,241.71 210.37,206.05 268.34,181.26 326.31,172.48 384.28,184.87 442.25,189.1 500.22,210.25 558.19,321.31 616.17,318.9 674.14,344.89 732.11,373.38 790.08,387.77 848.05,381.86 906.02,307.93" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.48" points="94.43,334.66 152.4,283.91 210.37,261.45 268.34,212.32 326.31,221.23 384.28,225.94 442.25,238.34 500.22,253.39 558.19,312.71 616.17,365.68 674.14,372.08 732.11,377.66 790.08,379.46 848.05,405.35 906.02,327.46" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.49" points="94.43,279.85 152.4,248.76 210.37,221.92 268.34,210.23 326.31,202.01 384.28,190.54 442.25,206.01 500.22,216.02 558.19,282.09 616.17,366.85 674.14,388.69 732.11,364.52 790.08,398.2 848.05,394.09 906.02,311.04" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.50" points="94.43,278.78 152.4,301.78 210.37,251.8 268.34,222.73 326.31,215.41 384.28,209.54 442.25,197.17 500.22,245.04 558.19,287.11 616.17,369.29 674.14,403.14 732.11,386.35 790.08,398.54 848.05,402.13 906.02,336.17" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.51" points="94.43,253.52 152.4,231.28 210.37,174.54 268.34,170.76 326.31,151.87 384.28,143.62 442.25,166.56 500.22,179.16 558.19,243.13 616.17,315.99 674.14,332.59 732.11,317.85 790.08,325.94 848.05,323.55 906.02,269.71" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
                <polyline id="GRID.polyline.15.1.52" points="94.43,309.29 152.4,269.7 210.37,233.4 268.34,211.16 326.31,197.17 384.28,195.51 442.25,205.35 500.22,232.48 558.19,297.64 616.17,347.13 674.14,367.07 732.11,371.54 790.08,385.05 848.05,386.65 906.02,316.09" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.1" fill-opacity="0.1"/>
              </g>
              <g id="GRID.polyline.16.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.16.1.1" points="94.43,309.29 152.4,269.7 210.37,233.4 268.34,211.16 326.31,197.17 384.28,195.51 442.25,205.35 500.22,232.48 558.19,297.64 616.17,347.13 674.14,367.07 732.11,371.54 790.08,385.05 848.05,386.65 906.02,316.09" stroke="rgb(255,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
              </g>
              <g id="geom_point.points.18.1" class="points grob gDesc">
                <use id="geom_point.points.18.1.1" xlink:href="#gridSVG.pch16" x="906.02" y="316.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.2" xlink:href="#gridSVG.pch16" x="94.43" y="309.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.3" xlink:href="#gridSVG.pch16" x="152.4" y="269.7" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.4" xlink:href="#gridSVG.pch16" x="210.37" y="233.4" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.5" xlink:href="#gridSVG.pch16" x="268.34" y="211.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.6" xlink:href="#gridSVG.pch16" x="326.31" y="197.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.7" xlink:href="#gridSVG.pch16" x="384.28" y="195.51" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.8" xlink:href="#gridSVG.pch16" x="442.25" y="205.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.9" xlink:href="#gridSVG.pch16" x="500.22" y="232.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.10" xlink:href="#gridSVG.pch16" x="558.19" y="297.64" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.11" xlink:href="#gridSVG.pch16" x="616.17" y="347.13" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.12" xlink:href="#gridSVG.pch16" x="674.14" y="367.07" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.13" xlink:href="#gridSVG.pch16" x="732.11" y="371.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.14" xlink:href="#gridSVG.pch16" x="790.08" y="385.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                <use id="geom_point.points.18.1.15" xlink:href="#gridSVG.pch16" x="848.05" y="386.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(255,0,0)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
              </g>
            </g>
          </g>
          <g id="layout::axis-l.3-3-3-3.1" class="pushedvp viewport">
            <g id="layout::axis-l.3-3-3-3::GRID.VP.2.1" class="pushedvp viewport">
              <g id="axis-l.3-3-3-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-l.3-3-3-3::GRID.VP.2::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.54.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-l.3-3-3-3::GRID.VP.2::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                        <g id="axis.1-1-1-1.1.1" transform="translate(50.2, 53.38)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">0.2</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.2" transform="translate(50.2, 183.63)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">0.3</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.3" transform="translate(50.2, 313.88)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">0.4</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.4" transform="translate(50.2, 444.13)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.4.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.4.tspan.1" dy="5.5" x="0">0.5</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                    <g id="layout::axis-l.3-3-3-3::GRID.VP.2::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                      <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-2-1-2.1.1" points="53.98,53.38 59.65,53.38" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.2" points="53.98,183.63 59.65,183.63" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.3" points="53.98,313.88 59.65,313.88" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.4" points="53.98,444.13 59.65,444.13" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                  <g id="GRID.gTableParent.60.1" class="gTableParent gTree grob gDesc">
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



