1. Based on how much work and effort it takes to make something as standard as web development work on all platforms, 
I think making platform specific interface could be either way more or way less work. If we are making something for 
one specific platform, then that sounds like it'd be a lot easier on us, but if we need to make a specific thing for 
each program then I can see it becoming a hassle very fast.

2. Media Queries allow us to have special rulesets depending on the device that is accessing our page. One example of 
how this can be used is by checking "@media only print" and then using the color feature to limit the colors shown on 
the page to be more printer friendly. Another example could be to use the scripting feature to see if the user is enabling 
javascript, and if they aren't, you can adjust your layout to avoid fancy javascript-requiring elements.

3. I think it's smarter to define Breakpoints based on the content of my site rather than specific device sizes. 
First of all, not only would it be way more work to find every single device resolution you want to directly 
support and make breakpoint changes to that size, but you'll also be missing the ball on a lot of sizes for less 
popular devices. I also beleive that if you base your site off of specific phone sizes rather than basing it off 
the actual content on the page, you could possibly run into issues.