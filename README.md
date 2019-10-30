# 3_Axis_CNC_code
TO make the code work make the connections as shown in the Initializations
What the code can do?
this code will run a 3 axis cnc machine like a conventional CNC machine by drawing lines and circles at given positions
It also uses analog encoders along with stepper motors to compensate for loss in stepper steps
It uses timer interupts to accurately read the position of encoders at fixed interval of time
a line can be drawn by using the function draw_line(x1,y1,x2,y2); from points (x1,y1) to (x2,y2)
a circle can be drawn by using the function draw_circle(x,y,r); which draws a circle with center as (x,y) and radius r
We can position the end effecter accurately to any co-ordinate on the Machine by using the function goto_func(x,y) 
