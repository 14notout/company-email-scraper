# company-email-scraper

A scraper fetching all company emails from Seedtable and Clutch websites.

🚀 Install the dependancies: `pip3 install -r requirements.txt`

In order to use sendgrid, you will need to go register with them and optain the SENDGRID_API_KEY that they provide you with.
You will have to store that SENDGRID_API_KEY in a sendgrid.env file.

[SendGrid API Getting Started](https://sendgrid.com/docs/for-developers/sending-email/api-getting-started/#prerequisites-for-sending-your-first-email-with-the-sendgrid-api)

Before running the program, remember to export you SENDGRID_API_KEY in terminal.\
`export SENDGRID_API_KEY='YOUR_SENDGRID_API_KEY'`

Once everything is set up, go into the `scrapers` folder and run either `python clutchco_scraper.py` or `python seedtable_scraper.py`. 

💛 Happy Sending!

![Alt Text](https://media.giphy.com/media/kDaE01OtFSyobqta2C/giphy.gif)
