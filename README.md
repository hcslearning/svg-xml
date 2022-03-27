# SVG

Ejemplo de lo básico:

```xml 
<svg width="600" height="600">
<circle cx="50" cy="400" r="40" stroke="green" stroke-width="4" fill="yellow"/>
<rect x="10" y="200" width="300" height="100" style="fill:rgb(0,255,255);stroke-width:3;stroke:rgb(0,0,0)"/>
<rect rx="20" ry="20" width="300" height="100" style="fill:rgb(0,0,255);stroke-width:3;stroke:rgb(0,0,0)"/>
<ellipse cx="450" cy="80" rx="100" ry="50" style="fill:yellow; stroke:purple; stroke-width:2;"/>
<line x1="0" y1="0" x2="200" y2="500" style="stroke:rgb(255,0,0);stroke-width:2"/>
<!--  points="x1,y1 x2,y2 x3,y3"  -->
<polygon points="400,400 450,490 460,410" style="fill:lime;stroke:purple;stroke-width:1"/>
<polyline points="0,0 100,50 0,150 450,500" style="fill:none;stroke:black;stroke-width:3;"/>
<text x="70" y="60" fill="white" style="font-size:3em;">I love SVG</text>
</svg>
```
