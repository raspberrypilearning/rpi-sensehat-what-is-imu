The Sense HAT has a movement sensor called an IMU, which measures the kinds of movement it experiences. IMU stands for Inertial Measurement Unit. It's actually three sensors in one:

- A gyroscope: measures momentum and rotation
- An accelerometer: measures acceleration forces, can be used to find the direction of gravity
- A magnetometer: measures the Earth's own magnetic field, a bit like a compass

![](images/apollo_imu.jpg)

Why is a movement sensor important? When you're in space, there is one question of absolute importance to which you must always know the answer: "Which way am I pointing?"

If you don't know your orientation, you are in big trouble. So an IMU sensor like the one of the Sense HAT is used on all manned and unmanned spacecraft to track movements and maintain an understanding of orientation. Even the earliest spacecraft had them — ask your grandparents if they remember the [Apollo mission](http://en.wikipedia.org/wiki/Apollo_program){:target="_blank"} that landed humans on the surface of the moon.

Above is a picture of the IMU sensor from the Apollo command module. You'll notice how big it is compared to the tiny black cube on the Astro Pi — that's the difference between 1975 and 2015 technology. Incidentally, the Astro Pi IMU is probably not as accurate as the Apollo one; however, it is a million times cheaper!
