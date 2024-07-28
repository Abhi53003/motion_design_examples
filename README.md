# motion_design_examples
this is all about motion design 

### what is motion_graphics.
this is a way to make our satic items, like image,videos and svgs into motion by animation and dynamic way.

use in 
* film website
* ui design
* advertisment
* visual story telling.

most used things in web-design motion 
* video :-add video,audio and picture to the wb
* animation :- more complex motion as compare to transition
* transition:- a way to show in change of state from one state to another
* svg:- a line base design 


1) video effect applying on website
* WE CAN USE YOU `TUBE EMBEDDED FEATURE` TO GET VIDEO FROM YOU TUBE AND DIRECTLY PLAY ON OUR WEBSITE.*

you can use video tag to put a video inside a div container and put a video using `video tag` here is code to appply a video
```
<video src="https://videos.pexels.com/video-files/17192174/17192174-uhd_2560_1440_30fps.mp4" class="video_" autoplay muted loop></video>
```
#### what is the problem with videos?
*the size of video way more bigger some time that make it hard to load so*

*solution*
`webM`(go online and search webM convertor)  formet is video forment that can use to put video on our website for information as a grpahics
`webM` make video size smaller we can use different forment accorsing to our work to make video ligher and not compromize with their quality.

note :- you can preffer any other forment you like


## transition 

-- The `transition-property` in CSS specifies which CSS properties will undergo a transition effect when their values change. This property is part of the CSS Transitions module, which allows you to create smooth animations without using JavaScript.
e.g.
```
transition-property:background-color
```
we can pass multiple values and time to this and chnage time curve of the transition.
```
transition:all 0.18s ease-in-out;

```
used all keyword to assign same effect to all or you can by following way

e.g:- 
```
btn
{
    trasition: backgound-color 5s ease-in,text-shadow 2s ease-in-out, font-size 1s;
}
.btn:hover
{
    background-color: rgb(105, 47, 240);
    text-shadow: 0px 9px 6px black;
    font-size: 27px;

}
```

in above code use transition keyword to provide the different timimg of transition.