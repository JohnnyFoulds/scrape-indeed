# Scrape Indeed
This project will use Robotic Process Automation (RPA) in the form of UiPath to scrape Job Postings from https://www.indeed.co.za.

This is a micro project that is the first of a series of micro projects that will be build, expanded and later on integrated into a complete end-to-end solution were postings are scraped, streamed to a Big Data platform, and then analysed.

## Lessons Learned

### Speed Up Extract Structured Data
When it is waiting for the next button on the last item to find it, ContiniueOnError is set to true, so it will continue, but the default TimeOut is 30s, so decrease it to 2000 (2s) or so to drastically reduce the time you have to wait for that.
