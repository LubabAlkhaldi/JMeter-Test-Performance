# 🚀 JMeter Performance Testing - SauceDemo

## 📌 Overview

This project demonstrates **performance testing** for the SauceDemo website using **Apache JMeter**.
The test simulates multiple virtual users accessing the application to evaluate performance, response time, throughput, and stability under load conditions.

## 🛠️ Tools & Technologies

* 🔹 Apache JMeter 5.6.3
* 🔹 Performance Testing
* 🔹 HTTP Request Sampler
* 🔹 JMeter Listeners for result analysis

## ⚙️ Test Configuration

| Parameter         | Value       |
| ----------------- | ----------- |
| 👥 Virtual Users  | 500         |
| ⏱️ Ramp-up Period | 300 seconds |
| 🔁 Loop Count     | 20          |

## 📈 Load Increase

The performance test was gradually enhanced by increasing the load during the testing process.

The initial test was performed with:

* 👥 Virtual Users: 5
* ⏱️ Ramp-up Period: 5 seconds
* 🔁 Loop Count: 5

After analyzing the initial results, the load was increased to evaluate the application's behavior and stability under higher traffic conditions.

The final test configuration reached:

* 👥 500 Virtual Users
* ⏱️ 300 seconds Ramp-up Period
* 🔁 20 Iterations

## 🧪 Test Scenario

The test simulates concurrent users sending HTTP requests to the SauceDemo website and evaluates how the application behaves under a high user load.

The test includes:

* 🌐 Sending HTTP requests
* 👥 Simulating concurrent users
* 📊 Collecting performance data
* 📈 Analyzing test results

## 📊 Performance Metrics

The following metrics are analyzed:

* ⚡ Response Time
* 🚦 Request Success Rate
* 📈 Throughput
* 👥 Load Handling Performance

## ▶️ How to Run

1. 📥 Open the `Saucedemo .jmx` file using Apache JMeter.
2. ⚙️ Configure the required test parameters.
3. ▶️ Execute the test plan.
4. 📊 Review the generated reports and performance results.

## 🎥 Demo Video

You can watch the test execution demo on LinkedIn:

🔗 [Watch the Demo Video on LinkedIn](https://www.linkedin.com/posts/lubab-alkhaldi_softwaretesting-performancetesting-apachejmeter-ugcPost-7481766900075560960-BAxI)

## 🌐 Website Under Test

🔗 https://www.saucedemo.com/

---

⭐ Created as part of my QA & Performance Testing portfolio.
