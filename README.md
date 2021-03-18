# Murmur - The official band website.

## Project Goals

A promotional website for the band Murmur. The site aims to be a one-stop shop for all things related to the band; featuring band news, a catalogue of their discography, a list of tour dates, a contact page, and links to the band’s merch store. The primary goals of the site are to keep new and returning visitors updated, to generate bookings via the contact form, and to generate revenue via ticket sales and by directing potential customers to the merch store.

The business goals of the site are to:
-	Increase awareness of the band/brand.
-	Generate bookings.
-	Generate revenue from tickets and merchandising.

The user goals are to:
-	Check for news about the band.
-	Find out about the band’s back catalogue.
-	Check tour dates & purchase tickets.
-   Book the band for shows.
-	Buy merchandise.

 
## UX
 
### User Stories:
1.	As a new user, I want the site to be easy to navigate, so that I can find my way around without difficulty.
2.	As a new user, I want to find out more about the band, so that I can feel connected to them.
3.	As a fan, I want to be able to explore the band’s back catalogue, so that I can find out about previous releases.
4.	As a fan, I want be able to see the locations, dates and times all upcoming gigs, so that I don’t miss a show.
5.	As a fan, I want to be able to easily access the store, so that I can purchase merchandise.
6.	As a promoter, I want a straightforward contact form, so that I can enquire about booking the band for gigs.
7.	As an interested user (a fan or a promoter), I want to be able to access the band’s social media accounts and streaming platforms, so that I can find out more about them and listen to their music.

### Wireframes:
- [index.html](assets/wireframes/index.pdf)
- [tour.html](assets/wireframes/tour.pdf)
- [discography.html](assets/wireframes/discography.pdf)
- [contact.html](assets/wireframes/contact.pdf)

## Features
### Header:
- Each page features a header, consisting of a brand logo (which doubles as a link to the homepage) and a navbar which provides links to the site's other pages and to an external merch store.
- This header is responsive, and on smaller screen sizes collapes into a list that is toggled with a button. 

### Footer:
- Each page features a footer, consisting of copyright information in the bottom left, and links to the relevant social media sites in the right.
- This header is responsive, and on smaller screen sizes shifts to a centered alignement with the copyright information on top, and the social links below.

### Hero Image:
- Each page features a hero image, featuring an image of a live music performance and a jumbotron prominently displaying the band name.
- This image is intened to invoke the energy and spectacle of live music, and utilizes a color palatte that is consistent with the rest of the site.

### Home: 
- The home page consists of a series of news paragraphs from the band, providing updates to interested parties (fans or promoters) on topics like new releases and upcoming tour dates.
- Each news item is accompanied by an image depicting a live music event, featuring light shows or pyrotechnics. Again, these images are intended to elict a positive response from the user by invoking the atmosphere of a gig or festival.
- On smaller screen sizes, these news items and images display as a list instead, seperated by styled horizontal rules.

### Tour:
- The tour page consists of list of upcoming tour dates.
- Each tour item displays the date, city and venue for each gig, along with an anchor (styled as a button) that links out to a 3rd party ticket website.
- Below these tour items, there is a "Subscribe" button, accompanied by some text serving as a call to action.
- This button triggers a modal that displays over the whole page, and consists of a form that asks users to provided their name and email address in order to subscribe to the mailing list.

### Discography:
- The discography page consists of the album artwork of all the band’s previous releases displayed with the alum title and release year in chronological order.
- On desktop/laptop screens, the album info will be concealed initially and revealed on mouse over, giving a sense of interactivity to the user's experience.

### Contact:
- The contact page consists of a form that allows any prospective booking agents or promoters to reach out to the band regarding potential shows.
- The form asks the user to provide a name, email address, a location (city/venue), and a proposed date. The form also contains a textarea which allows the user to freehand some text explaining their proposal.

### Defensive Design:
- The site utilizes Defensive Design principles to try to preserve the user's experience in the event that something goes wrong. 
- It does this by including a custom 404 error page, consisting of a brief piece of text explaining that there has been an error, and a link allowing the user to easily navigate back home.
- Additionally, the custom 404 page also contains the header and footer from the regular pages, allowing the user to navigate directly to any of the pages on the site, or to the associated social media links. 

### Features Left to Implement:
- Build a custom 500 error page, in the style of the 404 error as described above. - Backend required
- Connect the form elements to the backend by:
    - Utilizing the newsletter signup form on the modal to create a mailing list.
    - Emailing response on the contact form to the band's management.
- Implement an on-site storefront rather than linking out to a 3rd party site. - Backend required

## Technologies Used

- HTML5 - the pages of this site were designed using HTML.
- CSS3 - the pages of this site were styled using CSS.
- [Gitpod](https://www.gitpod.io/) - the site was developed using Gitpod as the development environment.
- [Bootstrap](https://getbootstrap.com/) - Bootstrap 5 was used to structure the layout of the site and make it responsive, as well as providing the JavaScript for the navbar and modal.
- [Font Awesome](https://fontawesome.com/) - Font Awesome icons were used for the social media links in the footer.
- [Google Fonts](https://fonts.google.com/) - Google Fonts were used throughout the project.
- [Hover.CSS](https://ianlunn.github.io/Hover/) - Hover.CSS was used to add hover effects to social media links in the footer and buttons throughout the site.
- [Favicon Generator](https://www.favicongenerator.com/) - Favicon Generator was used to create and size the favicon for the site.
- [Autoprefixer](https://autoprefixer.github.io/) - Autoprefixer was used to ensure cross browser support for the CSS code.

## Testing

 - Code Validators
 - Test User Stories
 - Bugs identified/fixes
 - If this section runs long, consider seperate .md file


## Deployment

- How to deploy code to github
- How to run code locally


## Credits

### Content
- eg wiki pages

### Media
- eg photo credits

### Acknowledgements

- 