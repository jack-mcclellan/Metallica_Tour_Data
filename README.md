# Web Scraping Metallica's Tour History

Check out my Tableau Viz of this data: https://public.tableau.com/app/profile/jack.mcclellan/viz/Metallica_Tour_Data/MetallicaTourData

This is my first project using Python to webscrape data. Metallica is a heavy metal band with an extensive touring history dating back to 1982. Their website contains all of their past events with date, location, and setlist (if known and filled in) and there are over 2100 shows in their website catalog. I decided this would be a fun challenge to apply what I learned in the 'Python For Everybody Coursera course taught by Charles Severance.

I filtered through every page of tour history on their website and scraped the tour event url, date, location (broken down by city, state, and country), and every song in the setlist. 

Notes:
- Some tour events had duplicate songs in the setlist since they played the song twice in a single show to get multiple takes for a live concert film, i have decided to remove those duplicate songs during the scrape.
- Metallica has played a show in Antartica, that is scraped into the country field (although it is a continent).
