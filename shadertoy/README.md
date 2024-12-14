For this project, I first referenced our last discussion.  I followed up until we coded the red circle in the middle.  Then I decided that I wanted to try to have some shapes move across the screen, since Shadertoy is pure coding and math and modeling more complex shapes would be super difficult as a beginner.  

I watched the first two Shadertoy tutorials by kishimisu and decided to blend elements from both videos.  First, I wanted to see if I could make my red circle more interested, so I tried to get a strobing light effect.  At the center of the screen, imagine there is a black circle pulsing with different inner rings of neon lights because I do not have visuals for the early stages of development.  
> Inspiration:; ![strobelight]()

Great, now I wanted to use SDFs from Inigo Quilez.  I chose to render an ooblong sphere and a 3D rectangle and have them orbiting the flat circle in the center.  While the kishimisu tutorial only showed how to move an object horizontally from left to right, I experimented with cosine and sine at various x, y, and z coordinates.  I was also inspired to have a cool effect once the two SDFs collided with each other and used a smin() function from kishimisu to create a smooth blending and engulfing upon collision.  I attempted to use a subtraction function as well to create an indent upon collision but could not figure it out.  The subtraction function seemed to delete one shape each time, so I abandoned this idea.

At this point, please imagine two gray shapes orbiting a strobe light that meld together upon impact, kinda boring right?  

Next, I wanted to add more visual interest to the scene, so it's time to generate more shapes! I used kishimisu's video to help me use space repetition and tried to fill the background with cubes. At first, I only achieved added a ground for the two shapes to rise and sink into, but this created a nice bright horizon. 
> ![two-shapes-red]()

Eventually, I was able to generate mini cubes into the scene.  Somewhere along the line of development, I lost the rectangle, but instead, I created a diffused cloud which I believe is the sphere. This murky cloud now had this effect of swallowing the little cubes and moving like liquid. 
> A `.gif` would be better sorry.
> ![repetition]()
> Pretend you can see a murky red cloud on the right, moving counter-clockwise. 

At the center of a black circle, you can see a star shape.  Wait, that wasn't there before...You are **not** hallucinating! I also added more subdivisions and contrast to make the lights more intriguing.  Now the black circle in the center has stars and inner rings of light, in addition to everything else I mentioned before. 

--- repetition, currently too much....need less colors in the picture...too much red

-- found another video from the writeup by art of code, experimented with hash() function for randomness and color

--- got the color

-- want one more movememtn -- tried to make cubes jiggle or move randomly....

-- ended up elongated cubes, kinda like pounding a hammer to anvil or something, feels very powerful and creates a cool frame around the black circle of light.  

---- still didn't like the colors so here are aalt versions. 

Final 0 yellow-gray