# README

This is the course repository for 'CSS to the rescue'.

The goal of this course is to make a responsive, and highly accesable website for someone who has a disability. I was not alowed to use Javascript for the behaviour of the website. I neither was allowed to use classes and id's for styling. Only element selectors and pseudo selectors are alowed. The goal of the course is to learn how powerfull selectors are, and to learn how to make a website for someone with a disability, in this case someone with spasm. This person mainly uses tab and enter to navigate through the website. This means that I don't need to use hover states, but focus states as main interaction.

Live version of the website is on https://rick712.github.io/cssttr

## The website
Since the content of the website didn't matter, I decided to make a website that is all about exposing the truth about chickens. Users of the site can write and read articles that other people wrote. Of course, the website itself doesn't work since the goal of the course is not to make a working web app, but to learn how to style for someone that navigates with tabs.

### Components
Part of the task was to include some components to the website that weren't necessarily usefull for the site, but were quite interesting to work with. The components are:
- A main navigation
- A login form
- A section with a header, an image and text
- A section with a linkable header and an image
- A chat
- A rating system
- And a step indicator

### Terms
There were also a few required techniques. These were:
- A fancy ampersands
- De-emphasize by dimming
- De-emphasize by blurring
- Intrinsic sizing
- Styling by sibling count (optional)
- Vertical centering
- Loading spinner
- Transitions on :hovers and :focus
- Custom cursor on element
- Extending the clickable area
- Custom checkboxes
- (Pseudo)random background
- Validation of a form

All these techniques are based on the book CSS SECRETS: Better solutions to everyday web design problems by Lea Verou.

### Main functions
Of course, the back end of the website does not work, but you can still navigate through the website. The pages you can visit are:
- index.html
- profile.html
- chat.html
- /pages/maanlanding.html

There are also a few hashes that have a particular function:
- #login
- #menu
These are working on every page, and can be triggered by clicking on certain menu items.

When you want to check the website out, be sure to to to these adresses.

## Progress

### Week one
In week one I set up the basic style of the website. I put all the components in a grid, and decided what kind of website I wanted to make. Since Vasilis said he wanted to be amused while reviewing the site, I decided to make a 'chicken awereness' website. The site wants the visitors to know that chickens are highly intelligent creatures that are taking over the world. I chose a few fonts I liked, and decided what kind of colours I wanted to use. I also added the first few components. With most of the components I had an idea what i wanted to do with them, but with some I had no qlue, especially the ``<progress>``. I found the component interesting, but I had no idea where I could implement it. 

For me it was difficult to not use classes and id's for styling. I am used to give a lot of elements a class to make sure that I have no problem with inheritance or what so ever.

### Week two
In week two I began making the first interactions. I really enjoy box shadows, so I put in a few of them. I really like when you get the feeling that a website is a 3 dimensional space, and box shadows enable you to give that feeling to the user. I also added the last components to the website. When the components were working I started to add the requirements from the book CSS SECRETS. I enjoyed most of them, but there were some things I didn't like very much. 

Week two was the week I had a big problem with inheritance. I had two pages in where the main content was in a ``<main>`` element, and it took over the properties that I didn't want on that page. Luckily I found a way to fix this.

In week two I also started experimenting with ``#id:target``. This was new for me, I didn't know you could alter properties of elements by a hash. I found it interesting how the elements take the new properties. I used this for a login form, and the mobile menu. I also used it on a other few small parts of the website.

I also learned a few new selectors, like ``+``, and even the ``>`` was relatively new for me. I did know what it did, but since I wasn't allowed to use classes and id's, the ``>`` selector is really usefull.

### Week three
In the last week I got quite some feedback about the website, mostly for the code. So in week 3 i cleaned up the code. The code was quite chaotic, and there was no logical order in it. When I fixed this I finished the interactions and the components. 

What I learned is the power of selectors. When teachers use to say that selectors are powerfull, I used to think: 'Yeah, right. CLASSES FTW', but they really are. While they are really powerfull, they also are dangerous when you don't really know the structure of your HTML elements. I think I will use selectors a lot more than I used to, but in combination with classes to have the best of both worlds.

I also learned how to use the ``#id:target`` like I said before, so I won't describe this one detailed.

And of course, the main focus of the course, using a keyboard to navigate through the website. When I used to make a website, I didn't really think abouth navigating through a website with tab, but this course was an eye opener for me. Even if you are not handicapped, like Marijn, it can be easier and quicker than using a mouse. When making future projects, I'll be sure to at least check if the website is usable with a keyboard.
