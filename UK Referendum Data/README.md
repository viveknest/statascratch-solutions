The objective of this exercise is to check your ability to use basic Python Data Structures, control program flow and, define and use functions


We will be using the [EU referendum results data](https://www.electoralcommission.org.uk/who-we-are-and-what-we-do/elections-and-referendums/past-elections-and-referendums/eu-referendum/results-and-turnout-eu-referendum). 

On 23rd June 2016, the United Kingdom voted to decide whether the country should remain a member of the European Union (EU) or leave. Each of the registered voter in the UK was given a simple choice. 

- Remain 
- Or Leave

The voters were asked to fill out their choices in a ballot paper. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c4/2016_EU_Referendum_Ballot_Paper.svg/1280px-2016_EU_Referendum_Ballot_Paper.svg.png" width="450"/>



For this exercise, we will analyze the results of this referendum. We have split the full data into three files. 

```uk_demo.json```

| Field       | Description                    |
|-------------|--------------------------------|
| ```Area_Code```   | Unique identifier for the area  |
| ```Area```        | Area Name               |
| ```Region_Code``` | Unique identifier for the region |
| ```Region```      | Region Name             |
| ```Electorate```  | Number of registered voters in the area   |

```uk_results.json```

| Field       | Description                            |
|-------------|----------------------------------------|
| ```Area_Code```   | Unique identifier for an area          |
| ```Votes_Cast```  | Number of Votes Cast in the area       |
| ```Valid_Votes``` | Number of Valid Votes cast in the area |
| ```Remain```      | Number of votes for Remain             |
| ```Leave```       | Number of votes for Leave              |

```uk_rejected_ballots.json```

| Field                         | Description                                                            |
|-------------------------------|------------------------------------------------------------------------|
| ```Area_Code```               | Unique identifier for an area                                          |
| ```Rejected_Ballots```        | Number of Rejected Ballots in the Area                                 |
| ```No_official_mark```        | Number of ballots rejected because they did not have any offical mark  |
| ```Voting_for_both_answers``` | Number of ballots rejected because they voted for both answers         |
| ```Writing_or_mark```         | Number of ballots rejected because they had a writing instead of check |
