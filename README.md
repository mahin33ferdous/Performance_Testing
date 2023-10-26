## Performance testing of demoblaze.com by JMeter


# Introduction

### This is a complete project which contains the performance testing documentation for [demoblaze.com](https://www.demoblaze.com/)  site , for a collection of API with various HTTP methods. Performance testing was done by JMeter.

 All the test files (jmx, jtl & html files) are included in this repository and the following is a report of all the test procedures and reports.

 **Types of performance testing that has been demonstrated in this project are:**

- **Load Testing** </br>
- **Stress Testing** </br>
- **Spike Testing** </br>


# Collection of API


# Load Testing

 **While executing 60 concurrent threads(users), total of 300 requests are made with error rate 0.00%.**

 **While executing 80 concurrent threads(users), total of 400 requests are made with error rate 0.00%.**

 **While executing 100 concurrent threads(users), total of 500 requests are made with error rate 0.00%.**


## Summary of Load Testing

**60 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 4.5 And Total Concurrent API requested: 300.**
**80 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 8 And Total Concurrent API requested: 400.**
**100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 10 And Total Concurrent API requested: 500.**


# Stress Testing

 **While executing 500 concurrent threads(users), total of 2500 requests are made with error rate 0.00%.**

 **While executing 800 concurrent threads(users), total of 4000 requests are made with error rate 0.00%.**

 **While executing 1000 concurrent threads(users), total of 5000 requests are made with error rate 0.38%.**


 # Spike Testing

 **While executing 1500 concurrent threads(users), total of 7500 requests are made with error rate 0.00%.**

 # Assertion