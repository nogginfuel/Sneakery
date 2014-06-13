# Sneakery

Sneakery is aimed at being a low profile / low visibility barrier for websites. I created it with the intent of using it as a way to launch a discrete login modal.

**This is currently a work in progress (WIP).**

#### Roadmap Future:

+ Integrated with Cheet.js - Done as of 06/12/2014

#### How it was Created:

+ CSS
+ [namuol / Cheet.js][1] - easy easter eggs (konami code, etc) for your website.
+ [zurb / foundation][2] - The Most Advanced Responsive Front-End Framework In The World.


#### Documentation:
The main class to call is `.sneakery`. This sets up the container. You can make the container and size or shape you need. I have it defaulted to a 10 x 10 pixel square. Obviously the smaller you make the container the smaller the click target will be so keep that in mind.
You may want to make the `background-color` or `border` color something visible to ensure you have placed the container exactly as desired.

I have also supplied a 'hover' class so you can back the container a bit more obvious when you've found it. Again you may want the container to always be the color of the page background to keep it hidden.

I have also supplied 4 classes for different layout configurations. You can use one or many on the same page. I've tried to name the classes as intuitively as possible, `topright`, `topleft`, `bottomright` and `bottomleft`.
You can also call the modal by typing `sneakery` when the focus is anywhere on the page.

For **Cheet.js** Questions please see the documentation provided by Namuol on their repo.
For **Foundation** Questions please see the documentation provided by Zurb on their respective repos and websites.

#### Feedback:
If you have feedback or issues with what I have specifically put together, please bring it up on this repo.

#### License:
Sneakery is [MIT-licensed][3] and absolutely free to use. Sneakery without brilliance of the other projects listed above (sincere thanks).

[1]: https://github.com/namuol/cheet.js
[2]: https://github.com/zurb/foundation
[3]: http://opensource.org/licenses/mit-license.php "MIT License"