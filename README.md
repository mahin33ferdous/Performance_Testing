## Performance testing of demoblaze.com by JMeter


# Introduction

### This is a complete project which contains the performance testing documentation for [demoblaze.com](https://www.demoblaze.com/)  site , for a collection of API with various HTTP methods. Performance testing was done by JMeter.

 All the test files (jmx, jtl & html files) are included in this repository and the following is a report of all the test procedures and reports.

 **Types of performance testing that has been demonstrated in this project are:**

- **Load Testing** </br>
- **Stress Testing** </br>
- **Spike Testing** </br>


# Collection of API

**A set of API for demoblaze.com covering various HTTP methods i.e. POST, GET are used for test data.**

[CollectionOfApi](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/329e9c0d-841d-4828-904e-67f67329984e)

# Load Testing

 ### While executing 60 concurrent threads(users), total of 300 requests are made with error rate 0.00%.

![t60_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/924e2b88-718b-4e92-9de6-6cff455f491d)


 ### While executing 80 concurrent threads(users), total of 400 requests are made with error rate 0.00%.

![t80_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/f9143089-1406-4776-a698-315127c74269)


 ### While executing 100 concurrent threads(users), total of 500 requests are made with error rate 0.00%.

 ![t100_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/d5d6d1c0-debd-47e3-b455-66f93fd94dac)


## Summary of Load Testing

**60 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 4.5 And Total Concurrent API requested: 300.**

**80 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 8 And Total Concurrent API requested: 400.**

**100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 10 And Total Concurrent API requested: 500.**


# Stress Testing

 ### While executing 500 concurrent threads(users), total of 2500 requests are made with error rate 0.00%.

 
![t500_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/cdc47fd3-1cba-4e64-8c5c-4dfcc2212d51)



 ### While executing 800 concurrent threads(users), total of 4000 requests are made with error rate 0.00%.

 
![t800_report1](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/1528ab82-cf20-410b-a587-7f1b05e5ada7)



 ### While executing 1000 concurrent threads(users), total of 5000 requests are made with error rate 0.38%.

 
![t1000_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/d57c2966-dd56-4fd7-ab33-ab3996801254)


### error

![t1000_error](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/ca0f68ab-4edd-48af-a6d4-925c0e51f2d7)


 ## Summary of Stress Testing

**500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 50 And Total Concurrent API requested: 2500.**

**800 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 80 And Total Concurrent API requested: 4000.**

**1000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 99 And Total Concurrent API requested: 5000.**


 # Spike Testing

 ### While executing 1500 concurrent threads(users), total of 7500 requests are made with error rate 0.12%.

 
![t1500_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/3ceeea91-a9fd-403a-aa08-cef13fbb2d02)

### error

![t1500_error](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/a94d0255-3c49-443c-b7d1-6af1d2073b12)


 ## Summary of Spike Testing

**1500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 95 And Total Concurrent API requested: 7500.**


 # Assertion

## response code

 ![response_code](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/4f25e483-95db-49ec-affd-ca528286a065)

 ## response size

 ![response_size](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/d871a6de-2256-4317-a166-46022efa8186)

## Load Time
  
 ![14 10 2023_00 30 36_REC](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/919472c0-5940-453a-b3fc-957cda57234e)




