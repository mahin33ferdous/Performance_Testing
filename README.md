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

![CollectionOfApi](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/79fdb3cc-afdd-4426-b3cd-e05dfb1edcb9)


# Load Testing

 ### While executing 60 concurrent threads(users), total of 300 requests are made with error rate 0.00%.

![t60_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/efabe5af-d6c3-482d-b177-dac6142fa4a0)


 ### While executing 80 concurrent threads(users), total of 400 requests are made with error rate 0.00%.


![t80_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/bee7ecea-d81c-4975-851a-3be891cfccbc)


 ### While executing 100 concurrent threads(users), total of 500 requests are made with error rate 0.00%.


![t100_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/f14194b6-1f0d-4782-bed3-dc58b36141bc)


## Summary of Load Testing

**60 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 4.5 And Total Concurrent API requested: 300.**

**80 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 8 And Total Concurrent API requested: 400.**

**100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 10 And Total Concurrent API requested: 500.**


# Stress Testing

 ### While executing 500 concurrent threads(users), total of 2500 requests are made with error rate 0.00%.

 


![t500_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/c087935b-c2f9-4f16-bcd2-03f9bb78c928)


 ### While executing 800 concurrent threads(users), total of 4000 requests are made with error rate 0.00%.

 


![t800_report1](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/5e22a520-1587-4f01-b53a-30608c3f0651)


 ### While executing 1000 concurrent threads(users), total of 5000 requests are made with error rate 0.38%.

 


![t1000_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/438aac97-28ab-43f5-9de4-50be17b446f6)

### error



![t1000_error](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/67fd9506-643e-4df8-9fe0-8dbc4d94a208)

 ## Summary of Stress Testing

**500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 50 And Total Concurrent API requested: 2500.**

**800 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 80 And Total Concurrent API requested: 4000.**

**1000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 99 And Total Concurrent API requested: 5000.**


 # Spike Testing

 ### While executing 1500 concurrent threads(users), total of 7500 requests are made with error rate 0.12%.

 

![t1500_report](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/3cc8658b-9ed3-402f-9c44-4a3d8c4f9d6c)

### error



![t1500_error](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/9534d0f5-269d-4464-9a14-bdbb489b1d4b)

 ## Summary of Spike Testing

**1500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 95 And Total Concurrent API requested: 7500.**


 # Assertion

## response code


![response_code](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/4223441f-a71a-45b3-9277-ed1795f61cf4)

 ## response size

![response_size](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/37239f01-6353-41ba-82b0-ec346badffc6)


## Load Time
  

![14 10 2023_00 30 36_REC](https://github.com/mahin33ferdous/Performance_Testing/assets/108746973/07bc8d7b-5553-48c0-945b-21fd09c56af7)




