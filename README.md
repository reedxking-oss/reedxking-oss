<div align="center">
  <h1>Hi, I'm Fareed</h1>
  <p>I turn messy operational data into tools people actually use</p>
  <p>Python • SQL • Excel • Tableau • Learning AWS</p>
</div>

---

## About me

I work in data center operations and have a background in semiconductor manufacturing and facility commissioning. The projects I'm proudest of started as problems I saw on the floor: tracking that lived in spreadsheets, numbers nobody trusted, and reports that had to be rebuilt by hand every week. I like rebuilding those in code so they're repeatable, checked, and easy to hand off.

## Projects

### [Commissioning SLA Analysis](https://github.com/reedxking-oss/commissioning-sla-analysis)
Tracked 10,693 pieces of equipment against a 5 business day commissioning SLA.
- Found that delays came from a few trades: Electrical was 87% on time, while UPW and Room/Bay-Ready were about 85% late
- Rebuilt my Excel tracker in Python. It matched on 10,684 units and caught 3 that the original formula scored wrong
- Masked the project data with random unit IDs before any of it was shared

**Python (pandas) • Matplotlib • Excel**

### [Tech Layoffs 2020 to 2024](https://github.com/reedxking-oss/tech-layoffs-workforce-analysis)
Cleaned and analyzed 1,416 layoff events with Python, SQL, and Tableau.
- Found and fixed corrupted company names, cut off labels, and hidden duplicates in data that looked clean
- Showed that Post-IPO companies made up 62% of jobs lost but cut only about 15% of staff on average
- [Live Tableau dashboard](https://public.tableau.com/app/profile/fareed.boone/viz/Tech-Layoffs-Workforce-Intelligence-2020-2024/WorkforceIntelligenceDashboard)

**Python • SQL (CTEs, window functions) • Tableau**

### [MotoGP Rider Consistency](https://github.com/reedxking-oss/motogp-performance-analysis)
Ranked riders by consistency across 8,227 race results from 2022 to 2025.
- Caught a rider listed under two names who was ranking 3rd from only 7 races
- Added a finish rate so crashes and DNFs count against consistency

**Excel • Python • SQL • Tableau**

## Currently building

A serverless inventory tracker on AWS (S3, SQS, Lambda, DynamoDB), based on a QR code tracking system I designed for warehouse parts.

## Connect

- [LinkedIn](https://linkedin.com/in/fareed-boone-b0508436b)
- [Tableau Public](https://public.tableau.com/app/profile/fareed.boone)
- Fareedboone107@gmail.com
