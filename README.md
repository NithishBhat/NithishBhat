# Nithish Bhat

Software engineer working on backend systems, cloud infrastructure and machine learning.\
MS in Computer Science at Northeastern University, graduating December 2026. Previously four years at Bosch.

Boston, MA · [LinkedIn](https://linkedin.com/in/nithish-bhat)

## About

I spent four years at Bosch Global Software Technologies building test and tooling software that works close to hardware, and finished there as a Senior Software Engineer. At Northeastern I have focused on distributed systems, AWS infrastructure, and ML and MLOps.

I am looking for software engineering roles in backend, cloud, ML/MLOps or embedded tooling.

## Experience

**Senior Software Engineer**, Bosch Global Software Technologies, Bengaluru\
*January 2021 to December 2024*

- Built a Python platform that controlled five lab instruments over UART/serial and cut a test cycle from five days to three. It won an internal innovation award.
- Built a firmware flashing tool and analysis tooling for sensor data sampled every 2 ms.
- Built an internal chatbot on Llama 2 to help new hires get up to speed.

**MS in Computer Science**, Northeastern University, Boston\
*January 2025 to December 2026*

Coursework includes Scalable Distributed Systems (CS 6650) and MLOps (IE 7374).

## Selected projects

### Distributed systems and cloud

**[Distributed Ticket Reservation](https://github.com/NithishBhat/distributed-ticket-reservation)**\
Backend for flash ticket sales. In load tests it handled about 500 orders per second without selling a seat twice, and stayed up when a server failed mid-sale. We implemented three locking strategies and measured how each holds up.\
`Go` `PostgreSQL` `Redis` `AWS` `Terraform`

**[Album Store](https://github.com/NithishBhat/album-store)**\
Photo-album backend on AWS that passed every test of the course's automated load-testing grader. Large uploads were crashing the server under load, which I fixed by streaming files directly to S3 instead of buffering them in memory.\
`Go` `DynamoDB` `S3` `Fargate` `Terraform`

**[Common Crawl Career Scan](https://github.com/NithishBhat/commoncrawl-career-scan)**\
Overnight scan of 2.12 billion web pages (about 20 TB) from the Common Crawl archive, run on up to 24 EC2 spot instances for $22.60 with no errors. It found careers pages for 53,737 tech and automotive companies.\
`Python` `EC2 Spot` `S3` `CloudWatch`

### Machine learning

**[Bill Drop](https://github.com/NithishBhat/bill-drop)**, Hackachusetts 2026\
Reads a Massachusetts electricity bill, recommends a cheaper supply plan and matching rebates, and pre-fills the City of Boston enrollment form. An LLM on Amazon Bedrock reads the bill and retrieves from a knowledge base of real rate and rebate documents. The savings calculations run in plain Python so the figures cannot be hallucinated. The full stack deploys with a single `terraform apply`.\
`Python` `Amazon Bedrock` `Docker` `Terraform`

**[Skin Lesion Classifier](https://github.com/multimodal-derm/derm-platform)**\
Team project that combines a lesion photo with clinical notes to predict one of six diagnoses, reaching 0.95 ROC-AUC on the PAD-UFES-20 dataset.\
`PyTorch` `ClinicalBERT` `Streamlit`

**[RA/QA Job Match](https://regulatory-affairs-jobs-board.vercel.app)**\
Public job board for Regulatory Affairs and Quality roles, collected from employers' own career sites. It ranks jobs against an uploaded résumé using keyword, TF-IDF and embedding scores, all computed in the browser so the résumé never leaves the user's machine.\
`Python` `JavaScript` `Vercel`

**[MLOps Labs](https://github.com/NithishBhat/MLOps-Homework)**\
CI with pytest and unittest, GitHub Actions pipelines that train, calibrate and version models, and a model served through FastAPI in Docker.\
`GitHub Actions` `Docker` `FastAPI`

### Web and other

**[Brew Haven](https://github.com/NithishBhat/Coffee_ecom)** ([live](https://coffee-ecom-rho.vercel.app))\
Online coffee store with cart, payments, order tracking, tax invoices and an admin sales dashboard.\
`React` `Node.js` `Express` `MongoDB`

**[Coffee News](https://github.com/NithishBhat/News)** ([live](https://news-six-inky.vercel.app))\
Daily dashboard for coffee growers with market news, frost and leaf-rust weather alerts, live arabica and robusta prices, and a crop calendar.\
`React` `Node.js` `Vercel`

**[Empire Tycoon](https://github.com/NithishBhat/Empire-tycoon)** ([live](https://empire-tycoon-smoky.vercel.app))\
Browser business simulation with businesses, markets and real estate whose prices and demand change in real time.\
`React` `Vite`

**[Fiber Routing](https://github.com/NithishBhat/Minimum-Cost-Optical-Fiber-Routing-with-Prim-s-Algorithm)**\
Finds the lowest-cost fiber-optic layout over a real city street network using Prim's algorithm, with a KNN filtering step that makes large graphs tractable.\
`Python` `OSMnx`

**[Calendar App](https://github.com/NithishBhat/Calendar-app)**\
Desktop calendar with recurring events, multiple calendars across time zones, and import/export.\
`Java`

## Skills

**Languages:** Go, Python, TypeScript, JavaScript, Java, C#, SQL, working knowledge of C++\
**Cloud and DevOps:** AWS (ECS, Fargate, EC2, Lambda, S3, SNS/SQS, RDS, CloudWatch, Bedrock), Terraform, Docker, GitHub Actions, Locust\
**Databases:** PostgreSQL, MySQL, DynamoDB, MongoDB, Redis\
**Machine learning:** PyTorch, Hugging Face Transformers, scikit-learn, pandas, NumPy, FastAPI\
**Web:** React, Next.js, Node.js, Express\
**Embedded and test:** Python/PyQt5 test automation, UART/serial instrument control, firmware flashing
