# 조현준 (Hyun-Jun Jo) - Backend Engineer

## About Me

I'm a backend developer focused on solving everyday inconveniences through code. My goal is to make incremental improvements that eventually lead to significant transformations. Currently serving as an industrial technical personnel at a Warehouse Platform company.

- 🎓 Kwangwoon University, Software Department (4th year, on leave)
- 📧 Email: hyunjun2087@gmail.com
- 📱 GitHub: [Tianea2160](https://github.com/Tianea2160)
- 💼 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/%ED%98%84%EC%A4%80-%EC%A1%B0-2747a9245/)
- 📝 Blog: [Technical Blog](https://tianea.hashnode.dev/)

## Tech Stack

![Java](https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=fff)
![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=fff)
![Kotlin](https://img.shields.io/badge/Kotlin-B75EA4?style=for-the-badge&logo=kotlin&logoColor=F6891F)
![Python](https://img.shields.io/badge/Python-0067A3?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-049593?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=Amazon%20AWS&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
![NGINX](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=Nginx&logoColor=white)

## Career

- **2023.07.10 - Present**: Software Engineer at [Techtaka (ARGO)](https://www.argoport.com/#FULFILLMENT)
  - Serving as an industrial technical personnel
  - Contributed to securing Series B and C investments from Altos Ventures through warehouse process improvements
  - Improved operational efficiency by optimizing work division strategies
  - Implemented distributed lock system and Kafka-based performance improvements

## Key Projects at Techtaka

### 📦 Logistics Picking Work Lifecycle Improvement
- **Problem**: Order cancellations required product restocking, causing resource waste
- **Solution**: Implemented delayed work creation based on remaining work counts and improved process flow
- **Impact**:
  - Secured ~2 hours 10 minutes of order cancellation time without restocking per order
  - Despite 35% increase in order cancellations, achieved 7.8% decrease in restocking requirements
  - Designed business architecture using Choreography-based Saga pattern for inventory location recommendations

### 🚚 Single Product Movement Optimization System
- **Problem**: Inefficient sorting without limits on product types per container
- **Solution**: Experimented with expanding maximum product types from 1 to 3, then 5 per container
- **Impact**:
  - Reduced average processing time per order by 42.86% (70 seconds to 40 seconds)
  - Decreased collection tasks by 78.9% (2,388 to 505)
  - Achieved daily workforce reduction of approximately 1.33 workers

### 🔒 Distributed Lock Annotation-Based Duplication Prevention
- **Problem**: Occasional duplicate work completion events causing inventory double-counting
- **Solution**: Implemented Redis-based distributed lock with custom annotation (@DistributedLock)
- **Impact**:
  - Completely eliminated duplicate processing issues
  - Currently used in more than 4 domains across the system
  - Enhanced developer productivity by simplifying lock implementation

### ⚡ Shipping Instruction Processing System Optimization
- **Problem**: Processing 300 orders took 10-15 minutes, exceeding client timeout (1 minute)
- **Solution**: Transformed synchronous API calls to asynchronous Kafka-based processing
- **Impact**:
  - Reduced API response time from ~12 minutes to ~1 second (99.86% decrease)
  - Decreased actual data processing time from 10-12 minutes to ~3 seconds (up to 97.5% reduction)
  - Eliminated POD CPU overload issues (previously reaching 100%)

### 📅 Same-Day Receipt Processing Capacity Management
- **Problem**: Lack of volume management system for same-day receipts, risking SLA violations
- **Solution**: Led the development of a processing type capacity management system
- **Impact**:
  - Prevented center overload by blocking excess orders during 31% of operating days
  - Satisfied Naver direct contract SLA and improved customer satisfaction
  - Enabled data-driven resource allocation through receipt calendar functionality

## Personal Projects

- [**Nimble**](https://github.com/daldal-nimble/Nimble): Platform for designing, reviewing, and sharing personal running courses (B-side Potent Day Hackathon)

- [**Ooi**](https://github.com/SANHAK-HYUNDAI): Dashboard service analyzing data between Naver Cafe posts and vehicle repair shops (7th Industry-Academic Cooperation Project, University President's Award)

- [**KW Dormitory**](https://github.com/kw-notice): Dormitory notification monitoring service

- [**MRP**](https://github.com/Project-MPR): Restaurant recommendation web service for locations near subway stations

## Certifications & Activities

- AWS Certified Practitioner
- Techtaka In-house Hackathon 1st Place: In-house Hackathon Newspaper
- DDD IT Union Club 9th Generation

## GitHub Stats

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Tianea2160&count_private=true&theme=cobalt&show_icons=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tianea2160&layout=compact&langs_count=7&theme=cobalt"/>
