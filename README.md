## Nithish Bhat

I'm a software engineer doing my MS in Computer Science at Northeastern University in Boston (graduating May 2027). Before that I spent four years at Bosch Global Software Technologies in Bengaluru, working my way up to Senior Software Engineer.

At Bosch I built tools that sit close to hardware: a Python platform that drove five lab instruments over UART/serial and cut a test cycle from five days to three (it won an internal innovation award), a firmware flashing tool, and analysis for sensor data sampled every 2 ms. I also built an internal chatbot on Llama 2 for new hires.

At Northeastern I've been focused on backend and distributed systems, and on machine learning. I'm looking for software engineering roles in backend, ML or embedded tooling.

[LinkedIn](https://linkedin.com/in/nithish-bhat)

### Projects

**[Distributed Ticket Reservation](https://github.com/NithishBhat/distributed-ticket-reservation)**
A ticketing backend for flash sales, where thousands of people try to buy the same seats at the same moment. In load tests it handled around 500 orders a second without ever selling a seat twice, and kept running when a server crashed in the middle of a sale. We built it with three different locking approaches and measured which one holds up best.
*Go, PostgreSQL, Redis, AWS, Terraform*

**[Album Store](https://github.com/NithishBhat/album-store)**
A photo-sharing backend on AWS. The course grades it with an automated tester that hammers the service with heavy traffic and large uploads, and it passed every test. The hardest part was large uploads crashing the server under load; I fixed that by streaming files straight to storage instead of holding them in memory.
*Go, AWS (DynamoDB, S3, Fargate), Terraform*

**[Skin Lesion Classifier](https://github.com/multimodal-derm/derm-platform)**
A team project that looks at a photo of a skin lesion together with the patient's clinical notes and predicts which of six diagnoses it is. The model combines an image network with a medical language model, and reached 0.95 ROC-AUC on the PAD-UFES-20 dataset.
*PyTorch, ClinicalBERT, Streamlit*

**[Brew Haven](https://github.com/NithishBhat/Coffee_ecom)**
An online store for coffee beans with a cart, online payments, order tracking, tax invoices and an admin dashboard for sales.
*React, Node/Express, MongoDB*

**[Fiber Routing](https://github.com/NithishBhat/Minimum-Cost-Optical-Fiber-Routing-with-Prim-s-Algorithm)**
Finds the cheapest way to lay fiber-optic cable across a real city's street map. A filtering step lets it handle large maps much faster than the standard algorithm.
*Python*

**[Calendar App](https://github.com/NithishBhat/Calendar-app)**
A desktop calendar along the lines of Google Calendar: recurring events, multiple calendars across time zones, and import/export.
*Java*

### Tools I use

**Backend & cloud:** Go, Python, SQL · PostgreSQL, MySQL, DynamoDB, MongoDB, Redis · AWS (ECS, Fargate, Lambda, SNS/SQS, S3, RDS), Docker, Terraform, GitHub Actions · load testing with Locust

**AI / ML:** PyTorch, Hugging Face Transformers, ClinicalBERT, Llama 2, scikit-learn, pandas, NumPy

**Embedded & test tooling:** Python (PyQt5) test automation, UART/serial instrument control, firmware flashing, C# desktop tools, working with C++ codebases

**Web:** JavaScript/TypeScript, React, Next.js, Node.js, Express
