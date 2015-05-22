# Le Wagon Fight Night

[@soniaprevost](https://github.com/soniaprevost)] and [@atmosfeer](https://github.com/soniaprevost), [Le Wagon](http://www.lewagon.org/en) alumni Batch #6 and Batch #8 respectively, started the idea of not so friendly coding wars between batches :) Here are the rules
for epic nights:

## Rules

### Basics

#### Rule #1

You do NOT talk about Fight Night.

#### Rule #2

You do NOT talk about Fight Night.

### Teams & Officiating Crew

#### Rule #3

Two teams battle against each other. There can be as many coders on each team as desired, as long as they're from the same batch.

#### Rule #4

The officiating crew consists of one main referee and two side-judges, one from each batch competing. The side-judge's role is to observe the opposing team and make sure that rules are being respected.

### The Battle

#### Rule #5

5 rounds of increasing difficulty. One code kata will be solved each round by each team. The first team to win 3 rounds wins the battle. Each round has a duration pre-determined by the referee depending on the kata.

#### Rule #6

Code Katas are selected prior to the fight by an impartial referee. The katas in question are secret to the teams before the event, obviously.

#### Rule #7

Teams shall be separated in different rooms during the battle to keep copycats honest.

### Allowed Resources

#### Rule #7

Each team can use one laptop for coding and two laptops for research. The only resource allowed is the [Ruby Doc](http://ruby-doc.org/). No Google, no Stack Overflow, and no outside help . Have a cookie and go cry about it in the corner.

#### Rule #8

All phones from the members of both team will be gathered by the officiating crew to ensure no outside help is provided.

### Score

#### Rule #9

Points will only be attributed each round if the code runs all the tests successfully. No cumulative score will be considered, only numbers of rounds won. The score for each round shall be calculated using the following formula:

round_length = amount of time for the given round in seconds
time_spent = time spent in seconds by the team to solve the kata before the final submission.
run_time = time in milliseconds to execute all the tests successfully.
code_elegance = a mark given by the ref. See rule 10 for details

score = (round_length - time_spent) + ( (1000 - run_time) * 3 ) + (300 * code_elegance)

#### Rule #10

After each round, the ref will take a look at each solution and give a mark from 1-10 based on the following criteria:
  - cleverness & efficiency of answer
  - elegance & legibility of code
  - whether the answer follows Ruby & general best practice



