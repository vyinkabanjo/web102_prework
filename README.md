# WEB102 Prework - Sea Monster

Submitted by: Victory Yinka-Banjo

Sea Monster is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 14 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] The introduction section explains the background of the company and how many games remain unfunded.
- [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
- [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
- [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

- [ ] A nav bar is included at the top of the page with hyperlinks to the each of the The introduction (Home), Stats and Our Games sections such that if a user wants to use to get to the Our Games or Stats section quickly, without needing to scroll, they can.
- [ ] A smooth scroll implemented using CSS improves the flow of the page between sections as the user navigates through the page.
- [ ] Buttons and clickable text have additional CSS hover featurs that scale and/or change colors or cursor type when pointed at by a touchpad or mouse.
- [ ] The overall color scheme of the website is altered from the original light blue and grey theme to a simpler, almost monotone, black and white so that the aesthetic of the website has a more contemporary and clean feel.

## Video Walkthrough

Here's a walkthrough of implemented features:
<img src='https://imgur.com/TOdwWdK' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with LiceCap!

## Notes

- Figuring out how to use javascript's for loop feature to create a function that adds all data from the games array to the page was my first major challenge. I made use of for each and for in before realizing that for of was the optimal for method to use.
- It took me a bit of time to fully grasp the idea behind filter and reduce in order to implement them and manipulate them, especially when coming up with a strategy for counting the number of unfunded games.
- The ternary operator also stumped me for a few minutes, when trying to create a grammatically correct string that explained the number of unfunded games properly but was satisfying when I got it!
- I ran into a couple struggles with CSS overall when figuring out how to manipulate flex box using features like flex grow and flex direction to structure the nav bar and home/stats sections in the exact way I wanted it. Using the '100vh' measurement to fill the page with my website's content was a really helpful hack that I hadn't prior been exposed to.
- I struggled with understanding how to implement .gitignore; I still don't think I fully have the hang of it but I was able to ignore the DS_Store file and hope to practice using the git function more!
- The smooth scroll functionality isn't fully where I want it to be yet; I haven't been able to debug yet why it isn't working like I had hoped it would. I tried using jQuery and javascript as an alternative method but I didn't understand exactly how to code worked so I decided to exclude it temporarily and come back to it.
- I still intend to add in a functionality that will allow the user to search for a specific game they have heard of withouth having to scroll through the games section, but it is a task I put off before this submission in order to allow myself submit as early as possible to hopefully secure a place in the class.

## License

    Copyright [2023] [Victory_Yinka-Banjo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
