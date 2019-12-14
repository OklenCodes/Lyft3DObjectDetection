# Lyft3DObjectDetection

My attempt at the Lyft3DObject Detection challenge

Inspired by - https://www.youtube.com/watch?v=enkRALcdPb0
https://www.youtube.com/watch?v=P8aTDusU7dw

'Yaw' is the angle of the volume around the z-axis, making 'yaw' the direction the front of the vehicle / bounding box is pointing at while on the ground.

With LIDAR sensors they are fast, decent range, resolution, works well noturnally as well as in light but the drawbacks are, They do not define colour well, their sensor size/proximity is weak and they cost a lot in comparison. A portion of the weakness is shown on the Center_X and Center_Y diagram where the Y-axis is skewed because the camera finds it difficult to identify objects narrowly ahead or narrowly behind.

I could be completely wrong and this could be because of the road being small and narrow so the camera is likely blocked.
I would like to retry the experiment with Radar, camera and ultrasound sensors

Credit to 
Oscar Beijbom, 2018. and Vladimir Iglovikov 2019. for Lyft Dataset SDK Dev-kit
Xing Hanlu for animation inspired code - https://xinghanlu.com/
