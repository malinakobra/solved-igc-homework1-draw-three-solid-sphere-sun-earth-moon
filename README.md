Download Link: https://assignmentchef.com/product/solved-igc-homework1-draw-three-solid-sphere-sun-earth-moon
<br>



<ul>

 <li>Draw three solid sphere: Sun, Earth, Moon.</li>

</ul>

The Earth should have spin axis, like the picture.

(You can use <strong>gluCylinder(….) </strong>function to draw the axis.)

<ul>

 <li></li>

</ul>

<table>

 <tbody>

  <tr>

   <td width="1148"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>The Sun is located in the center with the Earth rotates around it, and the Moon rotates around the Earth.</li>

 <li>When pressing the key “P”, all the planets should stop moving. When pressing the key “O”, the Earth should switch the slice and stack number.</li>

</ul>

*You can use any mode to draw the planets

(ex. GL_TRIANGLES, GL_TRIANGLE_STRIP, GL_QUADS) But if you use <strong>glutsolidsphere()</strong>, you can’t get the score of this part.

*You should use <strong>glPushMatrix() </strong>and <strong>glPopMatrix() </strong>to implement the rotation and revolution of the planets.

<h1>Spec</h1>

<strong>Global value:</strong>

Degree: X(any value) Radius: Y(any value)

<strong>Camera:</strong>

Position: (0, 30, 50)

Center: (0, 0, 0)

Up vector: (0, 1, 0)

<strong>Light:</strong>

Position: (0, 10, 0)

Diffuse: (1, 1, 1, 1)

Ambient: (0.5, 0.5, 0.5, 1)

<strong>Keyboard:</strong>

“P”: Pause the planets

“O”: Switch the slice and stack number of the Earth




<h1>Spec</h1>

<strong>Sun:                                            Earth:</strong>

Position: (0, 0, 0)            Slice: 360                                                 Slice: 4

Slice: 240                                         Stack: 180                                Stack: 2

Stack: 60                                                &lt;Switch when pressing key “O”&gt;

Rotation: 0

Radius: 7*Y                                    Rotation: X

Diffuse material: any                  Revolution: X/365 Radius: 2*Y

Obliquity: 23.5

Length of rotation axis: 4*Y

Revolution radius(around sun): 18

Diffuse material: any

<strong>Moon:</strong>

Slice: 240

Stack: 60

Rotation: X/28

Revolution: X/28

Radius: Y

Revolution radius(around earth): 3

Diffuse material: any




<h1>Score</h1>

<ol>

 <li>Draw the solid planets (20%)</li>

</ol>

If you use <strong>glutsolidsphere(), </strong>you <strong>can’t </strong>get the score of this part.

<ol start="2">

 <li>Implement the rotation(自轉) and revolution(公轉) (65%)</li>

 <li>Report (15%)</li>

</ol>

Your report should include:

(1). (Briefly) Explain the whole program’s structure.

(2). (Detailed) How do you implement the revolution and rotation by <strong>glPushMatrix() </strong>and <strong>glPopMatrix()</strong>?

(3). (Detailed) How do you draw the planets?( If you don’t use glutsolidsphere() )

<h1>Others</h1>

<ol>

 <li>Use Visual Studio 2017 or 2019 for this homework.</li>

 <li>You can do this homework in the “cpp” file because we had prepared basic framework for you. Remember to rename this cpp file with your own student ID.</li>

 <li>Zip your Visual Studio project into “ StudentID_HW1.zip”, and name your report “StudentID_HW1.pdf”. Then upload both of them separately to New e3.</li>

 <li>The deadline is at 11:55 pm on Octobor 14.</li>

 <li>If you submit your homework late, the score will be discounted.</li>

</ol>

submit between (10/15   ̴ 10/21) : Your final score * 0.9 submit between (10/22   ̴ 10/28) : Your final score * 0.8 submit after 10/29 : Your final score * 0.7

<h1>Result for pressing key ”O”</h1>