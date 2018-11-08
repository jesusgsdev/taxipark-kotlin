### Taxy park

The TaxiPark class stores information about the registered drivers, passengers, and their trips. Your task is to implement six functions which collect different statistics about the data.

#### Task 1

```fun TaxiPark.findFakeDrivers(): Collection<Driver>```

Find all the drivers who performed no trips.

#### Task 2

```fun TaxiPark.findFaithfulPassengers(minTrips: Int): List<Passenger>```

Find all the clients who completed at least the given number of trips.

#### Task 3

```fun TaxiPark.findFrequentPassengers(driver: Driver): List<Passenger>```
Find all the passengers, who were taken by a given driver more than once.

#### Task 4

```fun TaxiPark.findSmartPassengers(): Collection<Passenger>```
Find the passengers who had a discount for majority of their trips. Note that the discount can't be 0.0, it's always non-zero if it's recorded.

#### Task 5

```fun TaxiPark.findTheMostFrequentTripDuration(): IntRange?```
Find the most frequent trip duration among minute periods 0..9, 10..19, 20..29, and so on. Return any suitable period if many are the most frequent, return null if there're no trips.

#### Task 6

```fun TaxiPark.checkParetoPrinciple(): Boolean```
Check whether no more than 20% of the drivers contribute 80% of the income. If the taxi park contains no trips, the result should be false.