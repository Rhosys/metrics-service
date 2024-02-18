# The Cloud Metrics (Name TBD)

The Rhosys team is releasing the first ever Cloud Metrics as a Service. That focuses on pricing, data rention, and dashboards. We believe in no more `Charge by Seat`. The Cloud Metrics service focuses on Custom Metrics that automatically scale with your needs.

_Star the repo and watch it for changes and future releases. Have a question or comment, feel free to open an [issue ticket](https://github.com/Rhosys/metrics-service/issues)._

**Reason:**

There are no existing solutions that have an appropriate **charge by usage** strategy that matches the value that you get out. Most over-charge and focus on areas that aren’t relevant. The primary goal of the **Cloud Metrics Product** is to capture these custom metrics—APM, Custom Business Metrics, Dashboards built on top

**Core Value Proposition:**

- Affordable - Charges by Value, Not by Seat
- Serverless first - Serverless is a core competency and focus of the product, however will support any data source that can push metrics.
- Longevity - let's us track data over longish periods of time, many business needs require years of data, multiyear retention by default, decades optional

# MVP

- SSO w/ Unlimited Users of course
    - Granular permissions to integrate into your IdP
- global high SLA ~ 99.9% out of the box
- REST API
- Customizeable Dashboards
- Unlimited Custom Metrics
- Default 5 Year data retention
- Contracts—Data Addendums, BAA, etc…

# Stage 1

- Alerts
    - Subscriptions—Slack, Discord, Email, and others
- Monitoring
- Lambda Extension
- Metrics all in one place, Export from your Cloud—AWS, GCP, Azure

# Stage 2

- Anomaly Detection
- Alerts & Monitoring in one place—Integrates with your log storage of choice

# Want to see more:

Add [comments](https://github.com/Rhosys/metrics-service/issues) whereever there are questions or requests, and we will refine this into something that actually works for you. have questions or want to see more when this service is released, follow this repo and make sure to **Star it**!

# Pricing

**Pricing Goal -** Pay **Only** by **Usage** and **Storage**

Everyone wants to know how much this going to cost, we haven’t figured that out yet, but we can absolutely say for sure it will be cheaper than your current options by a factor of at least one magnitude. We are designing a service that matches our own pricing expectations if we would buy this solution. We are definitely collecting feedback on existing contract pricing for your existing tools.

Existing Pricing:

| Service | Monthly Price | Average Cost per Month | Max Retention |
| --- | --- | --- | --- |
| AWS Metrics | $0.30 / Metric | $30000 | 15 months |
| DataDog | $0.05 / metric | $5000 (Requires Enterprise Plan?) |  |
| InfluxData | charges by data | No public pricing |  |
| Grafana | $0.08 / Metric + Per User Pricing ($8 / user) | $10k | 13 months |
| New Relic | * Per User Pricing ($420 / user) * $0.50 / GB | $100k | 16 months |
| Our Cloud Metrics Service | $0.05 / metric | $5000 | 5 Years |

# Letters of Intent to purchase

We’re looking for innovative customers, if you are intrigued by this idea and want this for your company, and are a decision maker please email us at [Rhosys](mailto:metrics-github@rhosys.ch) so we can get your letter of intent.
