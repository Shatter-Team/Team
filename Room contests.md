# Room Contest Guidelines

**Official Shatter Room Contests** should typically be quick, themed contests for a single room done in about one week that is fair to the creators.

## Guidelines

* Room contests should take at most a week from the start until the end.
  * There shall be no time extensions without the consent of everyone who has previously submitted.
* Voting should be done entirely by people.
* The winner of the previous room contest should not be able to submit in the next contest.
  * However, they may submit again after the next one.
* Submissions can be modififed later as long as it is within the deadline.
* Creators can help each other, ask for feedback and integrate it into their rooms.
* Only rooms created entirely during the time of the contest can be submitted.
* Creators must agree to have their mod included in a compilation mod and one must be made.
* There should be at least a month (30 days) of time between two room contests.

### Optional extra guidelines

* The person who is running the contest can submit a room but it cannot be voted on.

## Length

I think LRC's main drawback has been that it takes too fucking long to see results from it. The first was 2+ weeks long and it was just boring for people to wait so long to see if they did anything, and the people who submitted late didn't even come close to winning anyways.

IMO room contests should be very fast pace. This helps to keep people engaged.

## Winner submission rule

To make it more likely that a variety of people win, I think it's better that the previous winner is not able to submit. This gives others a chance to and also makes the winner less predictable.

## Compilation mod

I think a compilation mod is good to keep people engaged and also to reward people to participate in the contest by seeing their work alongside others'.

The rooms should be in the winning place order.

## Time between contests

Waiting some time between contests should allow the individual contest to feel much more meaningful relative to what the contest is.

## Possible extra: Ranking system

We could also do some kind of rank system to encourage that new creators make stages and give more challenge for old creators. For example a person's rank could be:

```py
for each person:
  rank = floor(wins / 3) + 1
```

Then you could use this to make it harder for old players to win:

```py
for each person:
  score = votes / sqrt(rank)
```

Then the final score could be used to determine the actual winner of the contest.
