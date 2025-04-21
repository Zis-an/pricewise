# What is web scraping?

- The word 'web scraping' refers to the action where someone copy some information from any website or we can say from web and store them in another place like on a paper or a text document or in an excel file. This process is recognized as web scraping.





# Difference between web scraper and web crawler :

- Main function
    - Web Crawlers generally navigate/roam around the web.
    - Web Scrapers extract data from the pages.

- Navigation
    - Web Crawlers follow all the links to discover new pages.
    - Web Scrapers target specific pages for data extraction.

- Usage
    - Web Crawlers are mostly related to SEO analysis.
    - Web Scrapers can scrape any piece of data. It has been mostly used to generate dataset for ML training.



# One of the most popular web scraper : Puppeteer

- There are two types of browser. Headful browser (Chrome, Mozilla, Brave) who has a GUI and the Headless browser who does not has any GUI. Headless browsers run in the background and do the job. Headless browsers are developed by Google.





# Web Scraping Obstacles :

1. If the scraper is detected as a ROBOT, that website will immediately block the IP of the device.

2. IP Blocking and rate limiting. It happens when scrapers send too many requests to a specific website.

3. Traditional scrapers struggle to capture dynamic contents as they gets to be loaded after the full page gets loaded. Headless browsers can't crack a few of these problems like loading dynamic content.





# To resolve these problems there is one thing called 'bright data'.

- This is a headful browser. It is termed as 'Scraping Browser'. It does the things as if a human actually using the website. It almost completely imitates a human. it rotates IP automatically.

# FEATURES

- Handling javascript-heavy pages.
- CAPTCHAs
- Anti-scraping measures
- User interactions
- Device detection
- Complex navigations
- IP rotation
- Managing requests
- Legal concerns



---- PROJECT STARTS ----

1.  npx create-next-app@latest

2.  npm run dev

3.  VS Code Extension to work rafce : es7+

4.  npm install -D tailwindcss@3 postcss autoprefixer ( Installs tailwind )

5.  npx tailwindcss init -p ( Generates tailwind.config.js file )

6.  mv tailwind.config.js tailwind.config.ts ( To convert .js file to .ts file )

7.  npm install -D ts-node @types/node  ( So that Tailwind can understand and run tailwind.config.ts file. Without it, Tailwind can't process .ts config files. )

9.  
