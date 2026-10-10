# HOMEWORK 1 REFLECTION FILE

## HTTP Request

I enter my GitHub page URL into the search tab. The browser first looks for where the website is hosted. Then the DNS helps to connect the domain name to the server. After that, the browser sends an HTTP or an HTTPS request to GitHub's servers requesting the webpage.
GitHub responds by sending the website files back to the browser. The browser first reads the index.html file. Then it loads other files that are connected to the index.html. After the files are loaded, the browser finally displays the completed website.

## AI Attribution

I used ChatGPT as an additional source to help fix simple mistakes when it came to organizing HTML and the CSS files.
When working on this assignment, as I was following the instructions provided, I noticed that I was just writing on and on which made it look very disorganized. This is where I asked help from chatGPT.

Prompt Used:
I inserted my index.html file into ChatGPT
"Can you organize my file and make it look neat and fix up the spacing."

I also noticed that when I looked at my portfolio, my picture wasn't showing. I asked ChatGPT why that is.

Prompt Used:
"On my portfolio, my profile picture isn't showing. How do I fix that?"

I then realized I never actually inserted an image into my assets folder.


## AI logic Error
When creating the assets folder, AI told me to create a placeholder file that was a .txt file. I initially followed these instructions, but later realized that the placeholder file wasn't needed for the assignment. The assets folder actually needed to contain the image that I was using for my portfolio. I corrected this by uploading my profile image into the assets folder and making sure that the file name matched what I had written in my index.html file.

# HOMEWORK 2 REFLECTION

1. What is the difference between flex-direction: row and flex-direction: column?

   The difference between the row and the column is how the elements are arranged on the page.
flex-direction: row, places the elements horizontally or from left to right, while flex-direction: column, places the elements     vertically or from top to bottom. In my portfolio, I used Flexbox in order to display my name and the navigation links side by     side on the desktop and for mobile devices I used the flex-direction: column, to stack the navigation links vertically to          compensate with the phone having a smaller screen.

2. Why are relative units important for responsive design?

   Relative units like percentages or the rem are quite important because it allows a website to adjust to different screen sizes.
Instead of relying on fixed measurements, relative units makes it easier for a website to be easily usable for all devices.
An example from my portfolio would be when I used width: 80% for my main content on desktop and changed it to 90% for mobile       devices. I also used rem for my font sizes so the text could easily adjust across all devices.

3. How did you use AI, and what changes did you make?

   I used ChatGPT to initially understand how I would use a Flexbox. I also needed assistance on the media queries. ChatGPT explained to me how I would go about it and taught me what it does and showed me visuals of it. I also needed help with my images. There was an instance where I committed my CSS style file, but then on the website, the images were still messed up. It was a typo that I had in my code.

   "My images are appearing too large, can you what is messing up? Then I added my CSS project section"

After analyzing my code, it told me I had a typo in my code. I had used: grid-template-columns: repeat(3, minmax(0, lfr));
I used a lowercase L instead of a 1. It messed up my images because of it. After correcting the type and refreshing my webpage, everything was sorted out and worked out.
