ZOOM DIGITAL SIGNAGE STARTER PACKAGE

WHAT THIS IS
This package is a ready-to-upload starter kit for GitHub Pages. Once uploaded, the live page can be embedded into Google Sites or used directly in Zoom Rooms signage.

FILES INCLUDED
- index.html
- digital-signage/assets/pane1/images.json
- digital-signage/assets/pane1/image1.svg
- digital-signage/assets/pane1/image2.svg
- digital-signage/assets/pane1/image3.svg
- digital-signage/assets/backgrounds/info-bg.svg

HOW TO PUT THIS ON GITHUB PAGES
1. Create a new PUBLIC GitHub repository.
2. Upload everything in this package to the root of that repository.
3. In GitHub, go to Settings > Pages.
4. Choose Deploy from branch.
5. Choose main and /(root).
6. Save.
7. Your page will go live at:
   https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

HOW TO USE IN GOOGLE SITES
1. Open your Google Site.
2. Insert > Embed > By URL.
3. Paste your GitHub Pages URL.
4. Resize the embed to fill the page.

HOW TO CHANGE THE IMAGES IN PANE 1
1. Replace or add files in:
   digital-signage/assets/pane1/
2. Edit images.json so it lists the image files you want to rotate.

Example:
[
  "./digital-signage/assets/pane1/myphoto1.jpg",
  "./digital-signage/assets/pane1/myphoto2.png",
  "./digital-signage/assets/pane1/myphoto3.jpg"
]

HOW TO CHANGE THE SCROLLING INFOGRAPHIC IN PANE 2
Open index.html and look for INFO_ITEMS.
Edit the title and text entries.

HOW TO CHANGE THE BACKGROUND IMAGE IN PANE 2
Replace this file:
   digital-signage/assets/backgrounds/info-bg.svg
Or change the INFO_BACKGROUND_IMAGE value in index.html.

HOW TO CHANGE THE RSS FEED IN PANE 3
Open index.html and change:
   const RSS_FEED_URL = 'https://feeds.npr.org/1001/rss.xml';

Example RSS feeds:
- NPR News: https://feeds.npr.org/1001/rss.xml
- BBC News: http://feeds.bbci.co.uk/news/rss.xml
- CNN Top Stories: http://rss.cnn.com/rss/edition.rss

HOW TO CHANGE THE STOCKS IN PANE 4
Open index.html and edit TICKER_SYMBOLS.
Example:
{ proName: 'NASDAQ:TSLA', title: 'Tesla' }

IMPORTANT NOTES
- Google Sites does not host this kind of page directly. It needs to be hosted somewhere else and embedded by URL.
- GitHub Pages is the easiest free option for this.
- Some RSS feeds may stop working if the publisher changes access rules.
