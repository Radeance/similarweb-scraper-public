
#  ⚡️ Similarweb Scraper

[Try it out now for free on Apify!](https://apify.com/radeance/similarweb-scraper)

![Similarweb Presenter Image](https://i.imgur.com/tuC05zU.png)

### What does [Similarweb Scraper](https://apify.com/radeance/similarweb-scraper) do?

Our [Similarweb Scraper](https://apify.com/radeance/similarweb-scraper) retrieves valuable web traffic and seo data such as keywords, organic and paid traffic. Extract data at scale, perfect for your seo projects, business intelligence, and developing new applications. This actor allows you to scrape:

•	URL,
	•	Domain
	•	Global Rank
	•	Country
	•	Country Rank
	•	Category
	•	Category Rank
	•	Title
	•	Description
	•	Total Visits
	•	Monthly Visits
	•	Month
	•	Visits
	•	Social Traffic
	•	Paid Referrals Traffic
	•	Referral Traffic
	•	Search Traffic
	•	Direct Traffic
	•	Mail Traffic
	•	Country Share
	•	Country
	•	Shares
	•	and many more…


### ⬇ Input

If you use this actor on the apify platform, the UI Input interface is quite self explaining but here are some guidelines to help you use it:



- `urls`: (Required) (String Array) 
Enter your desired webpage urls in bulk or as a single url
<br>



#### JSON Input Example
  If you decide to use this actor from your favourite programming language. This would be a sample JSON input if you use the apify api via CURL, Python, JS etc.

```json
{
	"urls": [
		"https://www.indeed.com/",
		"https://www.linkedin.com/",
		"https://www.glassdoor.com/"
	]
}
```

### Output ⬆

**Full JSON Data Sample**
```json
{
  "url": "reddit.com",
  "domain": "www.reddit.com",
  "rankGlobal": 16,
  "country": "US",
  "countryRank": 8,
  "category": "Computers_Electronics_and_Technology/Social_Networks_and_Online_Communities",
  "categoryRank": 4,
  "title": "reddit is a network of communities where people can dive into their interests, hobbies and passions. there's a community for whatever you're interested in on reddit.",
  "description": "reddit is a network of communities where people can dive into their interests, hobbies and passions. there's a community for whatever you're interested in on reddit.",
  "totalVisits": 2389456765,
  "monthlyVisits": [
    {
      "month": "March 2024",
      "visits": 2189839131
    },
    {
      "month": "April 2024",
      "visits": 2219176885
    },
    {
      "month": "May 2024",
      "visits": 2389456765
    }
  ],
  "socialTraffic": 0.006667449744798684,
  "paidReferralsTraffic": null,
  "referralTraffic": 0.0036927595556386092,
  "searchTraffic": 0.6239548287381043,
  "directTraffic": 0.36172326123300835,
  "mailTraffic": 0.0038588574982430543,
  "countryShare": [
    {
      "country": "US",
      "share": 0.4810561456406962
    },
    {
      "country": "GB",
      "share": 0.0753728952653418
    },
    {
      "country": "CA",
      "share": 0.06956058936597427
    },
    {
      "country": "AU",
      "share": 0.04108357231283925
    },
    {
      "country": "DE",
      "share": 0.029960610427697505
    }
  ],
  "isDataFromGoogleAds": false,
  "previewDesktop": "https://site-images.similarcdn.com/image?url=reddit.com&t=1&s=1&h=66f2412047e0362ec60d5583d4b186511a8e859446bb112c60d22968facae906",
  "previewMobile": "https://site-images.similarcdn.com/image?url=reddit.com&t=4&s=1&h=66f2412047e0362ec60d5583d4b186511a8e859446bb112c60d22968facae906"
}
```
#### Output Overview
![Output Table View](https://i.imgur.com/OEX9OmV.png)


### ➡️ How you could use this website traffic and company data

**Market Analysis**: Efficiently scrape and analyze large volumes of website traffic data to understand market trends, popular categories, and emerging online sectors.

**Competitor Benchmarking**: Extract and compare website traffic metrics across different domains to determine competitive positioning and performance benchmarks.

**Company Insights**: Gather detailed company information, including domain authority, global and country ranks, and category ranks to evaluate market presence and performance.

**Traffic Source Analysis**: Identify and analyze traffic sources, such as direct, referral, social, and search traffic to optimize marketing strategies and improve traffic acquisition.

**Regional Market Insights**: Collect and analyze country-specific traffic data to understand regional market shares and user demographics for targeted marketing campaigns.

**SEO and SEM Optimization**: Monitor search traffic and paid referrals to refine SEO strategies and enhance SEM campaigns, ensuring higher visibility and better ROI.

**Content Performance Tracking**: Analyze the performance of specific content categories and popular topics among users to optimize content marketing strategies and boost engagement.

**Audience Segmentation**: Segment audiences based on traffic sources and country shares to tailor marketing messages and improve conversion rates.

**Technology Usage Analysis**: Discover the technologies used by competitors and market leaders to inform technology stack decisions and stay ahead in the digital landscape.

**Strategic Planning**: Use comprehensive website and traffic data to inform strategic planning, market entry decisions, and business development initiatives.

**Ad Campaign Effectiveness**: Evaluate the effectiveness of digital ad campaigns by tracking referral and direct traffic metrics, ensuring optimal ad spend and higher conversion rates.

**Brand Visibility**: Analyze and compare global and local rankings to measure brand visibility and impact in different markets, guiding brand-building efforts.

These use cases demonstrate the versatility and value of the Similarweb Scraper in providing detailed market insights, optimizing digital marketing efforts, and enhancing strategic business planning.

### ➡️ How easy it is to get started
**1.** Create a free Apify Account

**2.** Go to the **Inputs Tab** on this Scraper

**3.** Enter one or multiple **Webpage Url(s)*

**4.** Press **Start**

**5.** Get your **results in seconds**!


## 💬 Feedback and Support

**Your satisfaction** is **important** to us! Therefore we are constantly striving to enhance the performance of our Actors.

If you have any technical feedback or encounter any bugs with the Similarweb Scraper, please create an issue [here](https://github.com/Radeance/similarweb-scraper-public/issues).

You can also contact us directly for custom integrations or project use cases at business@radeance.com

Thank you and happy scraping!


<br>

[Try it out now for free on Apify!](https://apify.com/radeance/similarweb-scraper)