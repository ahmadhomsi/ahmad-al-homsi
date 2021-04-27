
* project 

Aristotle’s researchers began by reviewing a half-century of academic studies looking at how teams worked. Were the best teams made up of people with similar interests? Or did it matter more whether everyone was motivated by the same kinds of rewards? Based on those studies, the researchers scrutinized the composition of groups inside Google: How often did teammates socialize outside the office? Did they have the same hobbies? Were their educational backgrounds similar? Was it better for all teammates to be outgoing or for all of them to be shy? They drew diagrams showing which teams had overlapping memberships and which groups had exceeded their departments’ goals. They studied how long teams stuck together and if gender balance seemed to have an impact on a team’s success.

No matter how researchers arranged the data, though, it was almost impossible to find patterns — or any evidence that the composition of a team made any difference. ‘‘We looked at 180 teams from all over the company,’’ Dubey said. ‘‘We had lots of data, but there was nothing showing that a mix of specific personality types or skills or backgrounds made any difference. The ‘who’ part of the equation didn’t seem to matter.’’

Some groups that were ranked among Google’s most effective teams, for instance, were composed of friends who socialized outside work. Others were made up of people who were basically strangers away from the conference room. Some groups sought strong managers. Others preferred a less hierarchical structure. Most confounding of all, two teams might have nearly identical makeups, with overlapping memberships, but radically different levels of effectiveness. ‘‘At Google, we’re good at finding patterns,’’ Dubey said. ‘‘There weren’t strong patterns here.’’

As they struggled to figure out what made a team successful, Rozovsky and her colleagues kept coming across research by psychologists and sociologists that focused on what are known as ‘‘group norms.’’ Norms are the traditions, behavioral standards and unwritten rules that govern how we function when we gather: One team may come to a consensus that avoiding disagreement is more valuable than debate; another team might develop a culture that encourages vigorous arguments and spurns groupthink. Norms can be unspoken or openly acknowledged, but their influence is often profound. Team members may behave in certain ways as individuals — they may chafe against authority or prefer working independently — but when they gather, the group’s norms typically override individual proclivities and encourage deference to the team.




* imagine you have been invited to join one of two groups.

Team A is composed of people who are all exceptionally smart and successful. When you watch a video of this group working, you see professionals who wait until a topic arises in which they are expert, and then they speak at length, explaining what the group ought to do. When someone makes a side comment, the speaker stops, reminds everyone of the agenda and pushes the meeting back on track. This team is efficient. There is no idle chitchat or long debates. The meeting ends as scheduled and disbands so everyone can get back to their desks.



With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

Within this lesson we’ll take a look at both two-dimensional and three-dimensional transforms. Generally speaking, browser support for the transform property isn’t great, but it is getting better every day. For the best support vendor prefixes are encouraged, however you may need to download the nightly version of Chrome to see all of these transforms in action.

Transform Syntax
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.




Notice how the transform property includes multiple vendor prefixes to gain the best support across all browsers. The un-prefixed declaration comes last to overwrite the prefixed versions, should a browser fully support the transform property.

In the interest of brevity, the remainder of this lesson will not include vendor prefixes. They are, however, strongly encouraged for any code in a production environment. Over time we will be able to remove these prefixes, however keeping them in is the safest approach for the time being.

2D Transforms
Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.

2D Rotate
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.





One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.

With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

Transitions
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

In the example below the box will change its background color over the course of 1 second in a linear fashion.


1. Fade in
Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.

2. Change color
Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them.

3. Grow & Shrink
To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.

4. Square to circle
A really popular effect at the moment is transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the border-radius property.

5. 3D shadow
3D shadows were frowned upon for a year or so, because they weren’t seen as compatible with flat design, which is of course nonsense, they work fantastically well to give a user feedback on their interactions and work with flat, or fake 3D interfaces

6. Swing
Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration.

