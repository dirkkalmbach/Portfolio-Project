# Project: Build a Portfolio Site

This is my second project of the **Udacity Full Stack Web Developer Nanodegree**. The Goal in this project was to replicate the following design mockup in HTML and CSS:

![Design Mockup](images/DesignMockup.png)

The site is also fully responsive, meaning that it renders nicely on any device (smartphones, tablets, desktop).

I added some extra functionality:
- a carousel which changes the pictures every 3s in the main frame
- a modal (=pop-up window) which provides some additional information to my portfolio sites

I used the [Bootstrap 3 Framework](http://getbootstrap.com) for the grid system of the page as well as for the carousel and for the modal.

## How to run it?
Simply click [here](https://cdn.rawgit.com/dirkkalmbach/Portfolio-Project/master/index.html).

## Responsiveness
Bootstrap 3 distinguish between 4 viewports: mobile, tablet, and large and medium desktops.
I replicated the mockup for desktop vievports. For mobile devices I changed these elements:

- the main frame (with the carousel) will be diminished
- the portfolio information are vertically (rather than horizontally) arranged
- instead of explicit links to the portfolio sites the correspondent image is now a link
- minor layout adjustments like a thinner horizontal line

For tablet devices the carousel is replaced by a single image to take account of lower bandwith on mobile devices.

Finally, modals are suppressed on tablets and mobile.

## References

1. [Bootstrap Carousel Tutorial](https://bootstrapbay.com/blog/bootstrap-3-carousel-tutorial/)

2. [Udacity Full Stack Web Developer Nanodegree](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004)