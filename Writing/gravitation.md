# Part A
We are asked to calculate the acceleration due to gravity for an astronaut on board the International Space Station. We are given the following variables:

Earth's Mass (M) = 5.972 x 10<sup>24</sup> kg
Earth's Radius (r) = 6371 km
Altitude of the ISS (h) = 400 km

We know that $g = \frac{GM}{r^2}$

We know that $G = 6.67 * 10^{-11} \frac{Nm^2}{kg^2}$

In this case, what we put for the radius is not actually the Earth's radius, but rather the Earth's Radius plus the Altitude of the ISS. This is because the radius is where the ISS is in relation to the center of the Earth, so we combine the Earth's radius the the ISS's altitude to account for that. 

So our true value for r is 6371 km + 400 km, or 6771 km.

Since one of G's units is meters, we will convert from km to m.

1 km = 1000 m
6771 km = 6771000 m

Now we plug in our values.

$g = \frac{GM}{r^2}$

$g = \frac{G(5.972 * 10^{24})}{(6771000)^2}$

$g = 8.688 \frac{m}{s^2}$ 

# Part B

<img width="800" height="600" alt="fbdiss" src="https://github.com/user-attachments/assets/b95a945a-b64f-4048-bf89-404a477bf1ef" />

The reason why astronauts in the ISS feel like they are in zero gravity is because not only is the astronaut falling towards the Earth, but the ISS itself is also falling towards the Earth. Because the astronauts and their surroundings fall in the same magnitude and direction, it gives the illusion of zero gravity.

# Part C

In order for the ISS for to maintain a constant circular orbit that is 400 km above the surface of the Earth, it's gravitational force must equal the centripetal force.

Assume that $m_1$ is the Earth's mass and that $m_2$ is the ISS's mass.

$\frac{Gm_1m_2}{r^2} = \frac{m_2v^2}{r}$

We are asked to find the speed, so first we must isolate $v$, as the magnitude of velocity is speed.

$\frac{Gm_1m_2}{r^2} = \frac{m_2v^2}{r}$

$Gm_1m_2r = m_2v^2r^2$

$Gm_1r = v^2r^2$

$Gm_1 = v^2r$

$\frac{Gm_1}{r} = v^2$

$v = \sqrt{\frac{Gm_1}{r}}$

Now we plug in our value for r and compute our answer.
$v = \sqrt{\frac{Gm_1}{r}}$

$v = \sqrt{\frac{G(5.972 * 10^{24})}{6771000}}$

$v = 7670$ m/s

# Part D

If the ISS decreased its orbital velocity, then its gravitational force would be greater than its centripetal force. This would result in the ISS to start heading towards the Earth.

If the ISS increases its orbital velocity, then its centripetal force would be greater than its gravitational force. This would result in the ISS to start drifting away from the Earth.

# Part E (1)

We are asked to determine how long it takes the ISS to orbit the Earth, assuming a constant orbital altitude of 400 km.

We know that the ISS's velocity is 7670 meters per second.

One orbit around the Earth is one trip across the orbit. We know that the circumfrence of a circle is $\pi$ times double the radius. 

We know that the radius is 6771000 meters. Therefore, the circumfrence of the ISS's orbit is $6771000 * 2 * \pi$ meters. 

Dividing the circumfrence by the ISS's velocity gives us the expression $\frac{6771000 * 2 * \pi}{7670}$, which give us an answer of **5547 seconds**.

# Part E (2)

We are now asked to determine the number of revolutions that the ISS can make around the Earth in 24 hours, or 1 day.

We know that the ISS takes 5547 seconds to orbit the Earth.

We know that there are 86400 seconds in 1 day.

Divide the number of seconds in a day by the amount of seconds that the ISS takes to orbit the Earth.

$\frac{86400}{5547} = 15.58$

The ISS can make **15 full revolutions** around the Earth in a single day.
