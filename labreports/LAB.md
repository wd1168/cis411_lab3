# Lab Report Template for CIS411_Lab3
Course: Messiah College CIS 411, Fall 2018<br/>
Instructors: [Joel Worrall](https://github.com/tangollama) & [Trevor Bunch](https://github.com/trevordbunch)<br/>

Name: Wyatt Derk<br/>

GitHub: [wd1168](https://github.com/wd1168)<br/>

# Step 1: Fork this repository
- The URL of my forked repository

# Step 2: Clone your forked repository from the command line
- My GraphQL response from adding myself as an account on the test project
```
{
  "data": {
    "mutateAccount": {
      "id": "e88098fc-d910-4560-ad1a-582794ce0555",
      "name": "Wyatt R Derk",
      "email": "wd1168@messiah.edu"
    }
  }
}
```

# Step 3: Signup for and configure New Relic
- The chosen name of your New Relic ```app_name``` configuration
```
app_name: ['<CIS411_Lab3>']
```

# Step 4: Exercising the application / generating performance data

_Note: No lab notes required._

# Step 5: Explore your performance data
* What are your observations regarding the performance of this application? 
Ans: Everything is running smoothly. No violations or errors occured. Response time is averaging at 4 seconds.
* Is performance even or uneven?
Ans:The performance was uneven, due to some queries being larger than others.
* Between queries and mutations, what requests are less performant?
Ans:Queries are less performant. 
* Among the less performant requests, which ones are the most problematic?
Ans:The queries that pull more data are more problematic.

# Step 6: Diagnosing an issue based on telemetry data
* Within the transactions you're examining, what segment(s) took the most time?
Ans: Orders containing the words "PA" and "everything" took the most time.
* Using New Relic, identify and record the least performant request(s).
Ans: Orders containing the onion and raisen bagel took the least performance.
* Using the Transaction Trace capability in New Relic, identify which segment(s) in that request permiatation is/are the most problematic and record your findings.
* Recommend a solution for improving the performance of those most problematic request(s) / permiatation(s).

# Step 7: Submitting a Pull Request
_Note: No lab notes required._

# Step 8: [EXTRA CREDIT] Address the performance issue(s)
For the purposes of gaining 25% extra credit on the assignment, perform any of the following:
1. Adjust the diagnosed slow call(s) to improve performance. 
2. Verify the improved performance in New Relic, **including data and/or screenshots in your lab report**.
2. Check in those changes and **note your solution(s)** in your lab report.
