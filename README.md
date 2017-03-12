# Aljosa Musikic Portfolio Website

As our final project for the first term, it was our task to make a personal website/portfolio/presentation.

##### Requirements

- Thoughtfully written bio
- Portfolio section of your projects
- A way to contact you
- Attitute

My personal website is devided in 5 sections:
- Home
- About me
- Skills
- Projects
- Contact

It has a side navigation bar on the left, and quick contact links on the right.

#### Home

Home section is a welcome page containing my photo and a welcoming message. The full screen photo has a gradient effect which displays smooth transitions between orange and blue. The gradient effect was achieved through CSS.

#### About me

The interesting part in About me section are the three flipping cards.

#### Skills

In this part we hav a second parallax with a photo of my website code in Atom.

#### Projects

Projects field has six blue flexboxes and six white flexboxes inside the blue ones. For the first projects (Temperature App) there is a gif file which shows how it is executed. Each project box is a link that directs the user to the GitHub repositories.

#### Contact

The three icons were made with Gimp and they are a link to GitHub and LinkedIn.


### Design Changes

The structure of the website was the same from the very beginning. The changes occurred in the process of making the website in order to make it more responsive and more aesthetically appealing.
The first major change was the frame. The first version of the website had a black frame on both sides. After adding parallax I really liked the wide borders and decided to remove the black frame.
In the beginning I used only three colors: black, white and dull blue. After adding the photo I added more colors and the website seemed more personalized.


### Difficulties

After I inseted the side navigation bar, it was not working at all. After a while I discovered that turbolinks was blocking it so I removed "require-turbolinks" from app/assets/javascripts/application.js.

In the beginning every page had a height of 100vh and it looked nice on the computer screen. Afterwards I realized that it didn't work well on the phone and I had to change it. Discovering the right height was a long process.

When I tried to add the gradient to the second parallax and assign an opacity of 0.5, the text was not visible and there was no way to change it. I had to edit the photo with Gimp and insert the graient directly.

### Problems

The flipping cards sometimes show a ghost line which doesn't always show I'm still trying to figure out what it is as it is not registered at all when I inspect it.
