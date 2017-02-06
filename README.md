# learnSvg
learn svg
1.矩形 rect
	x 定义矩形左侧位置
	y 定义矩形的顶端位置

2.圆形 circle
	cx  原点的x坐标
	cy  原点的y坐标
	r 半径
3.椭圆形 ellipse
	cx  原点的x坐标
	cy  原点的y坐标
	rx  水平半径
	ry  垂直半径
4.多边形  polygon
	points

5.折线 polyline
	points

6.线条 line
	x1 x轴定义线条的开始
	y1 y轴定义线条的开始
	x2 x轴定义线条的结束
	y2 y轴定义线条的结束

7.路径 
	M = moveto 
L = lineto
H = horizontal lineto
V = vertical lineto
C = curveto
S = smooth curveto
Q = quadratic Belzier curve
T = smooth quadratic Belzier curveto
A = elliptical Arc
Z = closepath
以上所有命令均允许小写字母。大写表示绝对定位，小写表示相对定位。