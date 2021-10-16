# Analyst-Ratings-API

Through the <a href="https://tradefeeds.com/analyst-ratings-api/" rel="nofollow"> Analyst Ratings API</a> A customers can retrieve data on historical and current analyst recommendations, consensus estimates and price targets. Our API database is immediately updated after sell-side analysts have published their revised stock ratings and sales recommendations. Any ratings changes or revisions made by stock experts are available in the API database on analyst ratings. Our data is obtained from leading equity analysts and financial experts who analyze all industries and sectors. 


Instead of searching for data yourself or maintaining an in-house database, you can request access to Tradefeeds Analyst Ratings API database. You can find accurate data on analyst ratings and recommendations, and forecasts, that contributes to investing or trading decisions on stocks. Our customers are diverse including developers who build their applications for a specific audience, in-house teams in all-sized companies and entrepeneurial individuals.The data is retrieved through fast and seamless JSON REST API or in downloadable excel or csv files. 


Tradefeeds subscription packages are developed in such a way to serve all customers' needs. For the moment, there is no free trial provided. In case that you are a researcher or a student, we could negotiate a free trial. <a href="https://tradefeeds.com/pricing-subscription-plans/" rel="nofollow">Sign up for an API key</a> and we work out your case.

<h2><a id="user-content-api-features" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Company-TechnicalIndicators-API#api-features" aria-hidden="true"></a>API Features</h2>

<li><strong>Analyst ratings and recommendations</strong></li>
<li><strong>Consensus estimates</strong></li>
<li><strong>Stock price forecasts</strong></li>
<li><strong>Individual ranking of analysts</strong></li>


<h2><a id="user-content-ways-to-access-company-data" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Company-information-API#ways-to-access-analyst-ratings-data" aria-hidden="true"></a>Ways to access analyst ratings data</h2>
<ul>
 	<li><strong>JSON REST API</strong></li>
 	<li><strong>Excel CSV download</strong></li>
 	<li><strong>PDF reports</strong></li>
 	<li><strong>Email link</strong></li>
</ul>

<h2>Documentation</h2>

Our <a href="https://tradefeeds.com/api-documentation/" rel="nofollow"> documentation</a> includes input API filtering parameters, output response objects with explanation of their meaning. Clear request and response examples are given on the documentation page. Furthermore, we provide SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala

<h2>Request and response examples</h2>

https://www.tradefeeds.com/api/v1/analystratings
    ?key=YOUR-KEY&
            stock_ticker_symbol=AAPL,GOOG

    "status": {
    "code": 200,
    "message": "Success."
},
"results": [
    {
    "basics": {
        "name": "Apple Inc",
        "stock_ticker_symbol": "AAPL"
        "isin_identifier": "US0378331005"
        "exchange": "nasdaq"
        },
    "output": {
        "averageRecommendation": {
            "current": "1.33",
            "one_month_ago": "1.29",
            "two_months_ago": "1.35",
            "three_months_ago": "1.35"
        },
        "strongBuy": {
            "current": "18",
            "one_month_ago": "19",
            "two_months_ago": "20",
            "three_months_ago": "20"
        },
        "hold": {
            "current": "2",
            "one_month_ago": "2",
            "two_months_ago": "3",
            "three_months_ago": "3"
        },
        "strongSell": {
            "current": "0",
            "one_month_ago": "0",
            "two_months_ago": "0",
            "three_months_ago": "0"
        }
    }
]

https://www.tradefeeds.com/api/v1/analystratings
    ?key=YOUR-KEY&
            analyst_firm=JP Morgan

    "status": {
    "message": "Success."
},
"results": [
    {
    "basics": {
        "analyst_firm": "JP Morgan",
        NO EXAMPLE PROVIDED, CONTACT US FOR EXAMPLES
        }
    }
]


<h2>Customer support</h2>

In case that you encounter a data issue or you want to have more features added to the API, <a href="mailto:support@tradefeeds.com">please contact us at</a>.</p>

<h2>Legal</h2>

<p> The use of Tradefeeds proprietary data and API database is subject to the&nbsp;<a href="https://tradefeeds.com/terms-and-conditions-on-data/">Tradefeeds Terms &amp; Conditions</a></p>



























