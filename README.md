# Fylo Data Storage Component
![image](https://user-images.githubusercontent.com/47509295/179325895-55bd039e-f400-423c-b9ca-0609106b8230.png)

Hi! Welcome to the repository for my solution to this <a href="https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n" target="_blank">Frontend Mentor challenge</a>!

# Summary
I felt like doing another project this week, so I picked this one up as I was curious about how to achieve the speech bubble on the right card.

For this challenge, I used the following: 
- CSS Grid
- Flexbox

# What I learned
- I learned about the ::before and ::after properties
- How to make background gradients
- How grid areas can be manipulated to overlap elements on the page

# Looking Back
- This time, I gave my custom properties names that were relevant to their color instead of the element they were used on, as it doesn't make sense to name them after the element they're used on if they are used on multiple elements.
- The transition on the buttons sometimes fires on page load or after tabbing out then back on - I'm not sure why that is.
- I will have to look further into having background images fit all screen sizes - I had to set height, min-height and max-height for the mobile layout and I'm not sure if that is the correct approach.
- I originally tried to put margins to space the two cards on the mobile layout, however I found out that this makes the card smaller as it has to fit within the grid areas it is assigned to. I ended up putting an extra row in between the cards instead - I'm not sure if this was the correct way to achieve the spacing.
- In order to hide the ::before element, I had to add the class to my media query and set all of its properties to "unset" - I'm not sure if this is the best way of doing it. I did some searching on Google and it does seem like you have to give those properties a value, otherwise the desktop class will be applied instead, but I'd love to hear about this if I can do it in a better way!

# The End
Thanks for checking out my solution to this challenge! If you have any feedback, I would love if you reached out to me or left a comment on my <a href="https://www.frontendmentor.io/solutions/fylo-data-storage-component-with-css-grid-and-flexbox-kwkKTuuOs-" target="_blank">solution page</a> - I'm always looking to improve!

Happy coding!
