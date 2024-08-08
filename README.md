# WEB102 Prework - _Sea Monster Crowdfunding_

Submitted by: **Alexander Guel**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **6** hours spent in total

## Required Features

The following **required** functionality is completed:

-   [x] The introduction section explains the background of the company and how many games remain unfunded.
-   [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
-   [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
-   [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

-   [x] Added a navigation bar to quickly move the user's view to the Stats or Our Games sections.
-   [x] Smooth transitions when hovering over important elements (such as the stats cards and the games).
-   [x] Compact game card design that shows extra information on mouse hover.
-   [x] Added a "funded" percentage to show how much games have been funded in relation to their goal.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://imgur.com/a/gKIOjzD' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->

GIF created with LICEcap

<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

When adding the additional, optional features to the website, I had a hard time coming up with something. So, I turned to a real crowdfunding website which I have seen before: Kickstarter. I went over to their own version of an "Our Games" section and saw a really nice card design. It was compact as it only showed the title and a few other details about the games needing funding. However, upon hovering the element with the cursor, it would show more information. And so, my main design challenge became implementing something similar in this website.

Getting the effect to work took many tries. I first attempted hiding and showing information dynamically, but it wasn't working as intended. What helped me get unstuck was breaking the problem down into smaller pieces. I created a separate directory where I would tinker with different CSS rules until I finally came upon my solution using opacity and height changes.

This was an excellent project to not only practice fundamental JavaScript skills necessary for moving into a JS framework like React, but it was also great to work with a real design challenge requiring careful planning.

## License

    Copyright 2024 Alexander Guel

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
