1. As the ever changing world of web development grows and evolves, it definitely 
would be beneficial to stay on top of it. If you dont keep up then you'll probably 
end up stuck using legacy techniques for years as they add modern and efficient ways 
to do the same things. The way I plan to keep on top of things is going to be by 
having a yearly "relearn" of anything I'm using where I look up how to do all the basics 
from the ground up and learn everything again. I'd also do the same thing if I ever 
decide to pick something back up that I haven't used in a while.

2. There are many limitaions of "float" and this is most likely why it's been phased 
out into a legacy option, though a popular one at that. It maintains its popularity because 
although it has limits, it can still very easily find its place on many site designs, however 
users should keep these limitations in mind. First of all, you can't "float: center;" sadly, and
at least personally, this is the biggest tragedy. Secondly, it's a hassle to make objects that are 
grouped together (siblings) using float to have equal dimensions. Lastly, similarly to the last point, 
it's overall just not meant for grouping objects in any way such as rows or columns and have all the objects
have the same dimensions, which is a very common need for site designers. 

3. Flexbox is built to be language agnostic and it shows that through it's terminology. For example, lets 
take a look at "justify-content". This can affect where and how the objects inside the flexbox are laid out and
organized. However, this property and many otheres are COMPLETELY affected by "flex-direction". The flex direction
defines where the points of reference are for the entire flex box. If you say the right side is the start and the 
left side is the end than it will know and use that for every other property you apply, requiring you to keep track 
of exactly what's going on in your flexbox.