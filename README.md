# About

This repo will house my collection of data visualizations that are not made using code, but Affinity Designer. I wanted a low-stakes, on-going project where I worked on incorporating graphical design principles and software skills without having to worry about the overhead of code just yet. Simply put, these are experimental and fun. 

Below I'll include a brief description about what data I recorded and the decisions that went into design choices. 

## 1 Holiday Coffee
I wanted to visualize my coffee consumption, because as is traditional with me, it tends to skyrocket at the end of the semester. 

Data and Encoding: 
* Date - Header 
* Time coffee was made - Angle
* Mug type - Center circle icon (0)
* The cup number - Rings (1+)
* Type of Coffee - Ring Color
* The fate of each cup - Outer Ring Stroke

In my initial sketch, I had the center circle coding mug type, but it was using color. I quickly changed it to icons upon realizing that having two sets of color encodings, though in different locations and with different pairs of colors, would probably still be confusing. 

I choose to use icons over inner-circle line patterning (stripes, crosses, zigzags, etc) because the icons remove a level of decoding. Just by looking at the icon the reader would be able immediately know what decoration was adorning each mug, rather than needing to consult the legend again and cross reference 'zigzags mean TV/Film'. 

The ring gradients were a tough call, and I'm actually not sure I made the right one. I chose to use a gradient fading to white because: a) it represents qualitatively if not quantitatively the idea that caffeine lingers in the system, and b) I didn't want all the rings to be fully saturated and converging on the 4pm/8am line. I thought that having solid blocks of color might prove to be visually distracting. The reason for the doubt is that a friend interpreted the gradient as "the time I was drinking the coffee" and was confused ast to why it took my 8 hours to finish coffee, and why I'd make more having not finished the previous cup. Maybe this could be remedied simply by adding the gradient to the legend with the caption "caffeine present in system" - expect then I feel like it then becomes a Quantitative measurement of caffeine in system (which it's not because I have no actual measurements of this) rather than a visual suggestion. 


## 2 Snowboarding Falls
Due to an ongoing injury, I decided to record my falls during a recent snowboarding trip, just in case I did something that exacerbated my injury. NB: I was doing my best to avoid catastrophic crashes or any behavior that would most likely lead to a fall (e.g. jumping), so this data is not representative of my usual trips - i.e., I usually fall a lot more. 

Data and Encoding: 
* Day - Individual Main Lines
* A fall - A single flair off the main line
* Forward Foot - Whether the flair is coming off to the right of Left
* Edge - Fill of the circle at the end of the flair 
* Difficulty of Run - Color of flair
* Aspect of Fall - Stroke modifications

So, this one was fun to design. It came to me almost fully formed and I did very little in the way of modifications from my initial sketch. 

First, a bit of a primer: In snowboarding, people have a dominant or forward foot and for the majority of the populuation, this is the Right Foot. The Right Foot goes in back and does a lot of the hard work. Consequently, the Left Foot goes up front. This orientation, Right Foot Back & Left Foot Forward, is called Regular. When this orientation is reversed, it is called **Goofy**. I am a Goofy Rider, and so this means I ride predominantly with my Right Foot forward. Of course, the rider is able to voluntarily reverse their orientation so that they are riding with their non-dominant foot in the back. Regardless of whether the rider normally rides Regular or Goofy - when they choose to ride with their feet swapped, it's called riding **Switch**. In the legend, by including only Goofy or Switch, I was hoping to indicate my normal riding style, which is Goofy, through the exclusion of Regular. 

The data, however, is heavily skewed towards riding Goofy. As you can imagine, riding Switch is harder and less intuitive, your body wants to have things flipped. Therefore, when I normally ride Switch, I fall *a lot more frequently*. Since the goal for the trip was to not fall, I didn't ride Switch very often or for very long. I wasn't sure how to indicate this seemlessly into the rest of the visualization, so I left this aspect out for the sake of clarity. 

The flair colors match the run colors used at resorts, except for black, which indicates Difficult runs (green cirle = easy, blue square = intermediate). By coloring the main lines black for that high constrast but making them utterly devoid of actual data themselves, I thought it wouldn't be an issue. Please correct me if I'm mistaken and you interpreted the visualization as me riding prodominatley black diamonds. 

And then of course, there are fun aspects to every fall (moguls, jumps, whether I rolled/flipped when I fell) that I wanted to include because it characterizes the fall itself. And it would be pertinent if it ended up hurting. I hope that by including these details in the flair design themselves, it would take the viewer along for the ride, so to speak, as they visually followed the flair from the main line to the end. 









