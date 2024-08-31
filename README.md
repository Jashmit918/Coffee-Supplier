## Run
```
./tester.rb ./example_submission.rb
```

## Map file format:
First row contains the number of companies C. It's followed by C rows where the n-th row contains
the distance between the coffee supplier and the company measured in hours (that means that coffee
sent now will arrive this many hours later).

Example file:
```
5
1
1
2
2
3
```

## Historic data and test data file format:
First row contains the number of turns T for which data will be provided. It is followed by T
series of data, where the first row is a timestamp in "YYYY-MM-DD HH:mm" format and the next C rows contain
coffee consumption levels (measured in cups of coffee) for the given timestamp (the n-th row contains
the consumption level for the n-th company).

Example file:
```
2
2024-09-01 00:00
13
66
0
12
33
2024-09-01 01:00
12
33
1
12
0
```

The map is fixed for the whole contest. The final test data is correlated with the historic data provided.
