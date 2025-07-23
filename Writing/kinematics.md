# Part A

### Given Items
- Long Ramp
- Marble

### Tools Student Could Have Used:
- Video Recording Device (Most Likely a Phone)
- Ruler (To measure the ball's position)
- Video Editing Software (Measures time and greatly assists with measuring position)
  - Slow down video
  - See exact timestamp of a single moment of the video

Prior to sending the ball down the ramp, we measure the length of the ramp with the ruler. The ruler will be kept in frame, ensuring accurate measurements in future steps.

We then place the ball on top of the ramp. We will release and start recording at the same time. Video stops recording once the ball finishes going down the ramp.

Then we import the video into a video editing software. Here, we can stop the video at an exact time and see where the ball is at that exact moment. 

We can use our knowledge of the length of the ramp to measure the position. To prevent any errors from humans eyeballing the position, the ruler will be kept in frame of the video.

# Part B

## Making a Position vs Time Graph

For reference, here was the table of data that was provided to us.

| Position (cm) | Time (s) |
| ------------- | -------- |
| 0.0           | 0.0      |
| 0.34          | 0.5      |
| 1.29          | 1.0      |
| 2.71          | 1.5      |
| 5.12          | 2.0      |
| 7.55          | 2.5      |
| 11.44         | 3.0      |

Using this data, we can plot these points on a position vs time graph.

<img width="333" height="900" alt="kpt" src="https://github.com/user-attachments/assets/0ea0fb99-adb7-4f1e-a891-b62ed02ed02e" />

Using Graphing Calculator software, we can generate a quadratic regression, a curve of best fit for our data points. The equation for this curve is $y = 1.2919x^{2}-0.120714x+0.0466667$

Placing this curve onto the graph, we get this:

<img width="333" height="900" alt="kpt_bf" src="https://github.com/user-attachments/assets/dfbb6eb5-96a9-494b-93c5-2e0e9a2a3cb2" />

## Gathering Velocity Data

If we want to determine the acceleration of the marble, then we need to gather data points for velocity. This is because acceleration equals change in velocity divided by change in time.

Using the equation best-fit curve, we can get the "instant velocity" of each point.

Let's take $t=0.5$, where t is in seconds.

We know that the marble's position at 0.5 seconds is 0.34 centimeters, but what is the marble's velocity at that specific time?

We know that velocity equals change in position divided by change in time.

What we can do is take two points, one where time is slightly greater than 0.5 seconds and one where time is slightly less than 0.5 seconds. Let's take 0.5+0.01, or 0.51 seconds, and 0.5-0.01, or 0.49 seconds for this example. 

Using our equation for curve of best fit, we will take our two new $t$ values and compute its "position" at those times. In this case, those values are 0.32112505 centimeters for 0.51 seconds and 0.29770133 centimeters for 0.49 seconds.

Now we can compute for velocity. Velocity equals change in position divided by change in time.

$v = \frac{\Delta x}{\Delta t}$

$v = \frac{x_f - x_0}{t_f - t_0}$

$v = \frac{0.32112505 - 0.29770133}{0.51 - 0.49}$

$v = 1.171186$

We will round to three significant figures. This is because the data uses a mix of rounding to two, three, and four significant figures. To provide a fair balance, we take the median number, which is three significant figures.

So our instantaneous velocity for 0.5 seconds is 1.17 centimeters per second.

Now, we repeat this procedure for every time point. Doing this, we get the following data for velocity.

| Time (s) | Velocity (cm/s) |
| -------- | --------------- |
| 0.0      | 0.00            |
| 0.5      | 1.17            |
| 1.0      | 2.46            |
| 1.5      | 3.75            |
| 2.0      | 5.05            |
| 2.5      | 6.34            |
| 3.0      | 7.63            |

Our full table of data is now as follows.

| Position (cm) | Time (s) | Velocity (cm/s) |
| ------------- | -------- | --------------- |
| 0.0           | 0.0      | 0.00            |
| 0.34          | 0.5      | 1.17            |
| 1.29          | 1.0      | 2.46            |
| 2.71          | 1.5      | 3.75            |
| 5.12          | 2.0      | 5.05            |
| 7.55          | 2.5      | 6.34            |
| 11.44         | 3.0      | 7.63            |

## Graphing Our New Data

Let us take the data for time and velocity.

| Time (s) | Velocity (cm/s) |
| -------- | --------------- |
| 0.0      | 0.00            |
| 0.5      | 1.17            |
| 1.0      | 2.46            |
| 1.5      | 3.75            |
| 2.0      | 5.05            |
| 2.5      | 6.34            |
| 3.0      | 7.63            |

Using this data, we can plot these points on a velocity vs time graph.

<img width="333" height="662" alt="vpt" src="https://github.com/user-attachments/assets/95ab89ad-f29e-4de0-9e9a-d2fa1727f49d" />

Using Graphing Calculator software, we can generate a linear regression, a line of best fit for our data points. The equation for this line is $y = 2.55857x-0.0664286$

Placing this line onto the graph, we get this:

<img width="333" height="662" alt="vpt_bf" src="https://github.com/user-attachments/assets/0eb84786-3c2e-4581-8869-5ca59dd41217" />

# Part C

The equation of our best fit line from our velocity-time graph is $y = 2.55857x-0.0664286$

In a velocity-time graph, the slope is acceleration.

In the equation $y = 2.55857x-0.0664286$, the slope is 2.55857.

Therefore, the acceleration of the marble is 2.55857 meters per second per second.

# Part D

We are given the fact that the marble arrives at the end of the ramp at a time of 4.2 seconds.

We want to know the length of the ramp.

If we set our initial position (where the marble starts) to zero, then all we need is the final position to determine the length of our ramp.

Luckily, we have an equation that we can use to solve for final position. $x = x_0 + \bar v t$ (Final Position equals Initial Position plus Average Velocity multiplied by Time).

Since Initial Position equals zero, our equation is now $x = \bar v t$.

We know that our time is 4.2 seconds. Our equation is now $x = \bar v 4.2$, or $x = 4.2 \bar v$

However, we do not know the average velocity.

Luckily, we have an equation that we can use to get average velocity. $\bar v = \frac{v_f + v_0}{2}$ (Average Velocity equals Final Velocity plus Initial Velocity all divided by 2).

From the assignment intructions, the phrasing indicates that the marble was initially at rest. "A team of students is attempting to determine the average acceleration of a marble released from the top of a long ramp". Note the use of the word "released". This word indicates that the marble was being held at rest and started moving once it was released.

Since the marble was initially at rest, its Initial Velocity is zero.

The equation of our best fit line from our velocity-time graph is $y = 2.55857x-0.0664286$. We can use this equation to get our value for Final Velocity.

Let's plug in x = 4.2 to get our Final Velocity.

$y = 2.55857x-0.0664286$

$y = 2.55857(4.2)-0.0664286$

$y = 10.6795654$

We now have our values for Initial Velocity and Final Velocity.

Now we can plug these values in to get our average velocity.

$\bar v = \frac{v_f + v_0}{2}$

$\bar v = \frac{10.6795654 + 0}{2}$

$\bar v = \frac{10.6795654}{2}$

$\bar v = 5.3397827$

Our average velocity is 5.3397827 centimeters per second.

Now that we have our average velocity, we can now solve for final position.

$x = 4.2 \bar v$ 

$x = 4.2(5.33978276)$

$x = 22.42708734$

Rounding to the correct amount of significant figures, our final position is 22 centimeters.

Since we made our initial position 0, our final position is the same as our total length.

Therefore, the total length of the ramp is **22 centimeters**.
