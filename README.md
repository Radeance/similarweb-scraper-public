# 📌 Fastest Similarweb Scraper



![Similarweb Scraper Cover Image](https://i.imgur.com/UwajF9E.png)
| Try our other scrapers ► | [Wellfound Premium Job Scraper](https://apify.com/radeance/wellfound-job-listings-scraper) | [Glassdoor Scraper](https://apify.com/radeance/glassdoor-jobs-scraper)| [Tesco UK Scraper](https://apify.com/radeance/tesco-scraper)
|----------------------------|-----------------------------|-----------------------------|-----------------------------|



This high-speed & powerful scraper is designed to **effortlessly** extract website **traffic insights** from **SimilarWeb**. <br><br>
Whether you’re a marketer, SEO analyst, or business strategist, this scraper helps you uncover **detailed web analytics**, including **traffic sources**, **engagement metrics**, top referral sites, audience demographics, and **competitor comparisons**. Gain deep insights into any website’s performance in just a few clicks! 

### [Try it today for free with our 3-day free trial!](https://apify.com/radeance/similarweb-scraper)

## Key Fields
-	**🌍 Comprehensive Website Analytics:**
    - Scrapes detailed web traffic insights from SimilarWeb
    - Extracts essential metrics like global rank, country rank, and category rank
    - Retrieves title, description, and domain details automatically
-	**📊 In-Depth Traffic Data:**
    - Provides total visits and monthly visits for the last 3 months
    - Extracts engagement metrics like bounce rate, pages per visit, and average time on site
-	**🚦 Traffic Source Breakdown:**
    - Scrapes direct, referral, search, social, paid, and mail traffic distribution
    - Analyzes country-specific traffic shares for regional insights
-	**⚡ Fast and Efficient:**
    - Blazing-fast performance, capable of scraping thousands of entries in minutes
-	**🔧 Advanced Customization:**
    - Allows scraping a specific website URL for targeted insights
    - Easy to configure for extracting custom datasets
-	**📁 Flexible Data Output:**
    - Exports data in multiple formats: CSV, XLSX, JSON, JSONL, XML, and RSS


## ⬇ Input

If you use this actor on the apify platform, the UI Input interface is quite self explaining but here are some guidelines to help you use it:


### Allowed URL formats 
| Formats    | 
| -------- |
| `https://google.com`  |
| `http://google.com`  |
| `google.com`  |




- `urls`: (Required) (String Array) 
Enter your desired webpage urls in bulk or as a single url
<br>



### JSON Input Example
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
  "searchUrl": "https://google.com",
  "url": "google.com",
  "domain": "google.com",
  "rankGlobal": 1,
  "country": "US",
  "countryRank": 1,
  "category": "Computers_Electronics_and_Technology/Search_Engines",
  "categoryRank": 1,
  "title": "Google",
  "description": "",
  "totalVisits": 76304016912,
  "monthlyVisitsDateFormat": {
    "2024-12-01": 83269386218,
    "2025-01-01": 84515939909,
    "2025-02-01": 76304016912
  },
  "monthlyVisits": [
    {
      "month": "December 2024",
      "visits": 83269386218
    },
    {
      "month": "January 2025",
      "visits": 84515939909
    },
    {
      "month": "February 2025",
      "visits": 76304016912
    }
  ],
  "topKeywords": [
    {
      "keyword": "gmail",
      "estimatedValue": 176713742.0,
      "searchVolume": 111867130,
      "cpc": 0.858841125
    },
    {
      "keyword": "google",
      "estimatedValue": 65678772.0,
      "searchVolume": 69192790,
      "cpc": 0.6290823125
    },
    {
      "keyword": "google maps",
      "estimatedValue": 41897484.0,
      "searchVolume": 69198210,
      "cpc": 0.39930775
    },
    {
      "keyword": "google docs",
      "estimatedValue": 26475700.0,
      "searchVolume": 23615780,
      "cpc": 1.437721625
    },
    {
      "keyword": "google translate",
      "estimatedValue": 24836532.0,
      "searchVolume": 78668740,
      "cpc": 0.2907259375
    }
  ],
  "engagement": {
    "bounceRate": 0.2783256175100767,
    "month": 2,
    "year": 2025,
    "pagesPerVisit": 8.689840089793947,
    "visits": 76304016912,
    "timeOnSite": 646.5548538678281,
    "dateFormat": "2025-02-01 00:00:00"
  },
  "socialTraffic": 0.00808780398736754,
  "paidReferralsTraffic": null,
  "referralTraffic": 0.055120825270134066,
  "searchTraffic": 0.054824608870361974,
  "directTraffic": 0.8781732527327041,
  "mailTraffic": 0.0018995915034521439,
  "countryShare": [
    {
      "country": "US",
      "share": 0.2508199398460522
    },
    {
      "country": "IN",
      "share": 0.055138206592492474
    },
    {
      "country": "JP",
      "share": 0.05226193478967889
    },
    {
      "country": "BR",
      "share": 0.047370083698530505
    },
    {
      "country": "GB",
      "share": 0.037849022336788926
    }
  ],
  "isDataFromGoogleAds": false,
  "isSmall": false,
  "policy": 0,
  "previewDesktop": "https://site-images.similarcdn.com/image?url=google.com&t=1&s=1&h=eb35e0fbafa3eb290132ffdfe47187d950d68daaa659ec1bd4b4e834b8f16461",
  "previewMobile": "https://site-images.similarcdn.com/image?url=google.com&t=4&s=1&h=eb35e0fbafa3eb290132ffdfe47187d950d68daaa659ec1bd4b4e834b8f16461",
  "snapshotDate": "2025-02-01 00:00:00+00:00"
}
```
### Output Overview
![Output Table View](https://i.imgur.com/OEX9OmV.png)

### ➡️ How many results can you scrape with Similarweb Scraper
Similarweb Scraper can retrieve as much results as you need. We tested it with on average between 50-100 individual webpages per search request. It's realy up to you how much you need to scale it. Performance wise the scraper is able to return results like 5 page results in a matter of seconds.

Please keep in mind that [Similarweb](https://www.similarweb.com) is a highly dynamic page with suffisticated bot protection so your results may very depending on your use-case. We do our best so you don't need to worry about this limitations.

For most cases, the SimilarWeb Actor is perfect **for individuals**, **market researchers**, **analysts**, and **digital marketing professionals**, as well as **businesses** looking to analyze web traffic and competitor insights.


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


### 🌀 While the scraper is running

During the run, the actor will output log messages letting you know what is going on at any point. Each message always contains specific information about the process including which url / page the actor is working on.

If you provide invalid inputs to the actor, it will immediately stop with a failure state and output log messages explaining what is wrong. If you are unsure what went wrong feel free to open up an issue in the issue tab.



## 🔗 Personal Data Protection

The **Similarweb Scraper** is designed to ethically extract **only publicly available web and meta data**, and it **does not** scrape private user data such as personal email addresses or personal identifiers.

Our scrapers are ethical and do not extract any private user data, such as email addresses, gender, or location. They only extract what the user has chosen to share publicly. We therefore believe that our scrapers, when used for ethical purposes by Apify users, are safe. However, you should be aware that your results could contain personal data. Personal data is protected by the GDPR in the European Union and by other regulations around the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read our [blog post](https://blog.apify.com/is-web-scraping-legal/) on the legality of web scraping

## 💬 Feedback and Support

**Your satisfaction** is **important** to us! Therefore we are constantly striving to enhance the performance of our Actors.

If you have any technical feedback or encounter any bugs with the Similarweb Scraper, please create an issue in the Actor’s Issues tab above.

You can also contact us directly for custom integrations or project use cases at business@radeance.com
<br>

### [Try it today for free with our 3-day free trial!](https://apify.com/radeance/similarweb-scraper)