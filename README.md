# stoplight
2-way stoplight system made using Arduino

Stoplight is an Arduino project for a traffic light system. This system alternates the right of way for a 2-way street. There are 5 lights on each side of the "street." Two of the lights are for pedestrians (red and white) and three of them are for drivers (red, yellow, green).

As a pedestrian, there is also a button you can press that will cause the light to change (within three seconds) and allow you to pass. Once a few seconds have elapsed, the light indicating that pedestrians have the right of way changes from a solid white to a blinking red. Once the red light stops blinking (and is just a solid red) pedestrians for that particular side no longer have the right of way. 

As a driver, when the light is green you have the right of way. Once the light turns yellow, you are advised to slow down and proceed with caution. Then when the light turns red, you no longer have the right of way. If a pedestrian presses the button, after three seconds you will no longer have the right of way. 
