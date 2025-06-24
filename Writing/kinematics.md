# Part A [Procedure Description]

### Given Items
- Long Ramp
- Marble

### Tools Student Could Have Used:
- Video Recording Device (Most Likely a Phone)
- Ruler (To measure position in centimeters)
- Video Editing Software (Measures time and greatly assists with measuring position)
  - Slow down video
  - See exact timestamp of a single moment of the video

Prior to sending the ball down the ramp, we measure the length of the ramp with the ruler. The ruler will be kept in frame, ensuring accurate measurements in future steps.

We then place the ball on top of the ramp. We will release and start recording at the same time. Video stops recording once the ball finishes going down the ramp.

Then we import the video into a video editing software. Here, we can stop the video at an exact time and see where the ball is at that exact moment. 

We can use our knowledge of the length of the ramp to measure the position. To prevent any errors from humans eyeballing the position, the ruler will be kept in frame of the video.

# Part B [Graphing]

Using the given table, here is a time-position graph made with Desmos.
![desmos-scatter-plot](https://github.com/user-attachments/assets/392b6b44-06cf-4a01-b7a9-dee67c6266d7)

Using Desmos, we can generate a quadratic regression, a curve of best fit for our data points. The equation for this curve is $y = 1.2919x^{2}-0.120714x+0.0466667$
![desmos-with-regression](https://github.com/user-attachments/assets/a5408696-d990-4885-b8cb-9592d2de5039)


# Part C [Determining Acceleration]
The equation of our best fit curve for our time-position graph is $y = 1.2919x^{2}-0.120714x+0.0466667$. 

We can replace $y$ with $f(x)$, making our best-fit curve's equation $f(x) = 1.2919x^{2}-0.120714x+0.0466667$. 

This curve represents position as a function of time. Using basic calculus, we know that the derivative of position is velocity.

Therefore, our equation for velocity is the derivative of our equation. This can be shown as $f'(x) = 2.5838x-0.120714$. 

However, do not want the equation to determine the value's velocity. We the equation to determine the value's acceleration. 

We know that the derivative of velocity is acceleration. Therefore, our equation for velocity is the derivative of the derivative our original time-position equation. In other words, the equation for acceleration is the second derivative of our original time-position equation. This can be shown as $f''(x) = 2.5838$. 

Therefore, the acceleration of the marble is $2.5838$ centimeters per second per second.

# Part D [Determining the Ramp's Length]
We are given the fact that the marble arrives at the end of the ramp at a time of 4.2 seconds.

We want to know the length of the ramp.

If we set our initial position (where the marble starts) to zero, then all we need is the final position to determine the length of our ramp.

Luckily, we have an equation that we can use to solve for final position. $x = x_0 + \bar v t$ (Final Position equals Initial Position plus Average Velocity multiplied by Time).

Since Initial Position equals zero, our equation is now $x = \bar v t$.

We know that our time is 4.2 seconds. Our equation is now $x = \bar v 4.2$, or $x = 4.2 \bar v$

However, we do not know the average velocity.

Luckily, we have an equation that we can use to get average velocity. $\bar v = \frac{v_f + v_0}{2}$ (Average Velocity equals Final Velocity plus Initial Velocity all divided by 2).

To get Final Velocity and Initial Velocity, we must use our equation for velocity from Part C. $f'(x) = 2.5838x-0.120714$

Let's plug in time = 0 and time = 4.2 to get our Final and Initial Velocities.

$v_0 =f'(0) = 2.5838(0)-0.120714 = -0.120714$ \
$v_f =f'(4.2) = 2.5838(4.2)-0.120714 = 10.731246$

Now we can plug these values in to get our average velocity.

$\bar v = \frac{v_f + v_0}{2} = \frac{10.731246 + (-0.120714)}{2} = \frac{10.610532}{2} = 5.305266$

Our average velocity is 5.305266 centimeters per second.

Now that we have our average velocity, we can now solve for final position.

$x = 4.2 \bar v = 4.2(5.305266) = 22.2821172$

Rounding to the correct amount of significant figures, our final position is 22 centimeters.

Since we made our initial position 0, our final position is the same as our total length.

Therefore, the total length of the ramp is **22 centimeters**.
