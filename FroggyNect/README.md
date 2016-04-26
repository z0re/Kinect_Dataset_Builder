# FroggyNect
An awesome kinect recorder with elegant performance and friendly user interface

This software can:

1. Monitor any combination of three streams -- color, depth and body(skeleton) drew by the program dynamically
2. Meanwhile storing color, depth, infrared and body index streams as formatted image file (jpg, png, etc)
3. Meanwhile storing body (skeleton) stream datas in text file (txt) which containing 25 skeleton coordinates in three
   spaces (camera, color and depth), orientations of bones as well as floor clip plane.

What's more, the written fps (the fps of writing a whole five streams' data to disk) nearly catches 30 frame per second if you 
arrange your collecting dataset on a solid state disk and run with fast processor(s)

Ultimately, you can exploit this software to build your kinect RGB-D dataset in real time.

Of course, you can use FroggyNect with an xef file generated by kinect studio. It's all up to you ! Have fun !
 

If FroggyNect is helpful, please give it a star. In addition, any useful pull request is welcome.