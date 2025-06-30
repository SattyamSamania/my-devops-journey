# AWS Series – Part 1: How Websites Work, Cloud Computing & Introduction to AWS

## How Do Websites Work?

Before jumping into Cloud and AWS, it's important to understand how websites work behind the scenes.

### 1. You Enter a Website URL
Example: `www.amazon.com`

- The browser asks the DNS to resolve the domain into an IP address.
- Example: `www.amazon.com → 205.251.242.103`

### 2. Your Browser Sends a Request
It sends an HTTP request to the server, asking for the homepage.

### 3. The Server Responds
The server returns the webpage files (HTML, CSS, JS, etc.).

### 4. Your Browser Displays the Website
The browser renders the page using:
- **HTML** – Structure
- **CSS** – Styling
- **JavaScript** – Interactivity

> ✅ Bravo! The website is now displayed on your screen.

### Server Components
- **Compute:** CPU  
- **Memory:** RAM  
- **Storage:** Disk  
- **Database:** Structured data storage  
- **Network:** Routers, cables, switches, etc.

---

## Traditional Web Hosting (On-Premise Infrastructure)

### What is On-Prem Hosting?

- Buy physical servers
- Setup in office or data centers
- Manage hardware, OS, security, power, cooling
- Hire 24/7 monitoring staff
- **Disaster-prone** and hard to scale

🧠 *Example: Company sets up their own data center with expensive equipment*

---

## What is Cloud Computing?

> **Cloud Computing** is the on-demand delivery of computing resources over the Internet.

### Key Features:
- **On-demand** access
- **Pay-as-you-go** pricing
- Scalable & flexible resources

**You don’t own the servers – AWS does. You just use what you need.**

---

## Problems Solved by the Cloud

- 🔁 **Flexibility** – Change resource types on the fly  
- 💸 **Cost-Effectiveness** – Pay only for what you use  
- ⚙️ **Scalability** – Handle large traffic spikes  
- 📈 **Elasticity** – Auto scale in/out  
- 🔒 **High-availability** – Designed for failure tolerance

---

## Types of Cloud Computing

| Model        | Description | Examples |
|--------------|-------------|----------|
| **IaaS**     | Infrastructure as a Service – rent virtual servers & networks | AWS EC2, Azure, GCP |
| **PaaS**     | Platform as a Service – ready-made dev tools | AWS Elastic Beanstalk |
| **SaaS**     | Software as a Service – apps ready to use | Dropbox, Zoom, Gmail |

---

## Introduction to Amazon Web Services (AWS)

> AWS is the world’s most comprehensive and widely adopted cloud platform.

### 💡 What AWS Offers:
- Compute (EC2)
- Storage (S3)
- Databases (RDS)
- AI/ML (SageMaker)
- Networking, Security, and more

---

### AWS Cloud History

- 🗓️ Launched in 2006 with **Amazon S3**
- Mission: Scalable, affordable, accessible infrastructure

---

### AWS Cloud Use Cases

- Web hosting
- App development
- Disaster recovery
- Machine learning
- Storage & backups

---

## AWS Global Infrastructure

### 🌍 AWS Regions
- A **Region** is a group of multiple data centers
- Example: `us-east-1`, `ap-south-1`

### 🏢 Availability Zones
- Each Region has 3–6 AZs (physically separated data centers)
- Example: `ap-south-1a`, `ap-south-1b`, `ap-south-1c`

### 📍 Points of Presence (Edge Locations)
- 400+ PoPs across 90+ cities
- Used for **low-latency** content delivery via services like CloudFront

---

This sets the **foundation** before jumping into IAM, EC2, S3, and real projects.

📌 **Next up (Part 2): IAM – Identity and Access Management in AWS**

