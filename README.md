# Lairhaven - website for hideout leasing service

Lairhaven provides hideouts and headquarters for superheroes and villains. This company is neutral, and wont be taking part of any turf wars.
This company leases great locations that are safe and hidden even if they are in the middle of a city,
but also looks for other locations like abandoned bunkers, caves, abandoned fairgrounds, castles, 
abandoned factories and so on, since some customers prefer it that way.
As a bonus this company does the hideout stylings to match the customers brand.

## Design points

Design point: mobile-first. 
- Goal is to make everything as flexible as possible
- Minimum amount of code changes between different viewports

### User goals:
What is their goal? What problem does this product or feature solve for them?
- User needs to find a safe lair. As a bonus this company does the styling and moving for them too.

		
What are some of the actions or operations they are likely to perform?
- Customer meetup (online) to make the contract and if needed on location
- Styling of location
- Moving in (secretly, with ninjas)
- Customer care (24/7, because evil never sleeps)

### User Stories:
- As a customer, I need to be able to easily see what website offers
- As a customer, I need to be able to contact the company
- As a customer, I want to know more about the company
- As a customer, I need the company to be reachable


## Design Choices

- Initial color scheme is from Visme.co, but I changed some colors to darker to make site more accessible, mainly red to a darker shade.


## Features

### In all the pages:

Header:
- Company name is responsive
- Hero image changes size depending of how wide screen it is viewed on

Navigation bar:
- Links to other pages (Main, Help and Application form)
- Active site is in red color, other links are black.
- When hovered over, link changes color

Footer:
- Company's contact information, Social media links

### Main page: What the company has to offer

Main:
- Welcome text

Bulletpoint list:
- List of services the site offers
- Bulletpoint has icons from FontAwesome as bullets
- List is inside a stylized box

Locations:
- Pictures and descriptions of locations
- Each location box has a header, picture and description.
- On screens 499px and under locations are in a column.
- On screens between 500px and 949px locations are showing up two on a row
- on screen 950px and up locations are three in a row

Wrap up:
- Under locations there is a box that has text and links to other pages 



### HELP-page

FAQ:
- Most asked questions and company history

Contact Customer Service
- Information on how to contact

### APPLICATION-page
Fill the form:
- 5 fields where customer can fill their information, which 3 are required
- choose interesting locations (checkbox)
- textarea to tell more of their wishes
- User agreement checkboxes, one required
- Button to send the form

## Possible coming features:
- Articles: Couple of articles with few quick tips and a pictures.
" Dark Gothic is not for villains only!"
- Customer feedback: Couple of opinions from customers (can have some fun here)
- Different color schemes for heroes and villains, can choose by clicking a button in menu
- New locations, like student apartments for minions and sidekicks

 ## TESTING

 Tested with The W3C CSS Validation service. Congratulations! No Error Found.
 Tested with nu HTML checker, all three pages. No errors or warnings to show.
 Tested with Google Chrome developer tool Lighthouse to find any remaining errors and to make page more accessible.

## ISSUES

-

## DEPLOYMENT



## CREDITS
Pictures:
- Photos by from PxHere


### COLOR SCHEME
- 50 Gorgeous Color Schemes From Award-Winning Websites:
Nro 19: Minimal yet warm
https://visme.co/blog/website-color-schemes/

### Code from Love Running:
* {
    margin: 0;
    padding: 0;
    border: none;
}
