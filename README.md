# cse4020-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [CSE4020 Lab 4 Solved](https://www.ankitcodinghub.com/product/cse4020-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91687&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE4020 Lab 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Write down a Python program to draw a transformed triangle in a 2D space.

A. Set the window title to your student ID and the window size to (480,480).

B. Complete the render() function below to draw a triangle in the manner described in C.

i. You have to use OpenGL transformation functions. Do not use numpy matrix multiplication for composing transformations.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
def render():

</div>
</div>
<div class="layoutArea">
<div class="column">
glClear(GL_COLOR_BUFFER_BIT)

</div>
</div>
<div class="layoutArea">
<div class="column">
glLoadIdentity()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># draw cooridnates
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
glBegin(GL_LINES)

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 0, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([1.,0.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(0, 255, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([0.,1.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 255, 255)

drawTriangle()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>###########################
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># implement here
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>###########################
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
def drawTriangle():

</div>
</div>
<div class="layoutArea">
<div class="column">
glBegin(GL_TRIANGLES)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,.5])) glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([.5,0.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
C.

</div>
<div class="column">
If you press or repeat a key, the triangle should be transformed as shown in the Table:

Key

Q E

A D 1

􏱀􏰌􏰚􏰂􏰈􏰉􏰘􏰌􏰆􏰚􏰃􏰓􏰘􏰂􏰈 􏰈􏰗􏰘􏰐􏰕􏰊 􏰍􏰖 􏰚􏰛􏰛􏰐􏰆􏰐􏰕􏰚􏰃􏰖􏰊 􏰲􏰛􏰘􏰆􏰠􏰘􏰈􏰖􏰊 􏰪􏰓􏰃􏰗 􏰠􏰌􏰖􏰅􏰓􏰘􏰐􏰈 􏰘􏰂􏰖􏱁 􏰐􏰂􏰕􏰖􏰈􏰈 􏰦􏰘􏰐 􏰠􏰌􏰖􏰈􏰈 􏰧􏰣􏰜􏰫 i. You may need a global variable (like a python list object) to store key inputs.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Transformation

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Translate by -0.1 in x direction

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Translate by 0.1 in x direction

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Rotate by 10 degrees counterclockwise

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Rotate by 10 degrees clockwise

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Reset the triangle with identity matrix

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
D.

</div>
</div>
<div class="layoutArea">
<div class="column">
E. Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)

F. Expected result:

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
When starts E*4 A *3

Q*6 D *2 1

2. Write down a Python program to draw rotating point p1=(0.5, 0), p2=(0, 0.5) and vector v1=(0.5, 0), v2=(0, 0.5) in a 2D space.

A. Set the window title to your student ID and the window size to (480,480).

B. Use the following render() and fill “# your implementation” parts to render p1,p2 and v1,v2.

<ol>
<li>Hint: Render the vector v1, v2 as a line segment starting from the origin (0,0).</li>
<li>Hint2: You need different translation matrix for p1 and p2 to render them correctly.</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
def render(th):

</div>
</div>
<div class="layoutArea">
<div class="column">
glClear(GL_COLOR_BUFFER_BIT)

</div>
</div>
<div class="layoutArea">
<div class="column">
glLoadIdentity()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># draw cooridnate
</pre>
glBegin(GL_LINES)

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 0, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([1.,0.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(0, 255, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([0.,1.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 255, 255)

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># calculate matrix M1, M2 using th
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># your implementation
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
# draw point p

</div>
</div>
<div class="layoutArea">
<div class="column">
glBegin(GL_POINTS)

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># your implementation
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># draw vector v
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
glBegin(GL_LINES)

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># your implementation
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
C. Expected result: Uploaded LabAssignment4-2.mp4 i. Do not mind the initial angle.

<ol start="4">
<li>p1,p2 and v1,v2 should be -t rad rotated when t seconds have elapsed since the program was executed.</li>
<li>You need to somehow combine a rotation matrix and a translation matrix to produce the expected result.</li>
<li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)
‘
</li>
</ol>
</div>
</div>
</div>
