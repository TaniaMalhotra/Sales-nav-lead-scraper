# Sales-nav-lead-scraper

LinkedIn Sales Navigator does not offer a built-in option to export saved leads from your lists. Accessing and exporting saved leads to a file or CSV is a crucial part of the sales process. While there are tools available in the market, such as https://evaboot.com/, these services cost as much as $29 per month.

This scraper provides a free and efficient solution to quickly access and export your saved leads from LinkedIn Sales Navigator. With this tool, you can automate the process of extracting lead information and save it in a CSV file for easy management and integration into your sales workflow.


## To use

### Step 1: Prepare LinkedIn Sales Navigator

1. Navigate to LinkedIn Sales Navigator.
2. Input your desired search query.
3. Ensure the page URL follows the format: `https://www.linkedin.com/sales/search/people?recentSearchId=xxx&sessionId=xxx`.

### Step 2: Open the Developer Console

1. Ctrl + I
2. This will open the developer console in a separate window.

### Step 3: Configure and Run the Script

1. Adjust the variable `NUM_OF_PAGES` in the script to the number of pages you wish to scrape, starting from the current page.
   - For example, set `NUM_OF_PAGES` to 5 to scrape 5 pages.
2. Paste the script into the developer console and press `Enter` to execute it.

### Step 4: Wait for the download
That's it! 
You can now access the CSV file from your downloads folder

### Important Note

- It is highly recommended not to scrape too many pages at once. LinkedIn has strict policies regarding the use of automation tools and may ban accounts for excessive use.

#### Did that help? 
Leave a star! ⭐
