# roopnarine
[![Build Status](https://travis-ci.org/globalbioticinteractions/roopnarine.svg?branch=master)](https://travis-ci.org/globalbioticinteractions/roopnarine)

dataset retrieved from:
Roopnarine, P.D. & Hertog, R., 2013. Detailed Food Web Networks of Three Greater Antillean Coral Reef Systems: The Cayman Islands, Cuba, and Jamaica. DatasetImpl Papers in Ecology, 2013, pp.1–9. Available at: http://dx.doi.org/10.7167/2013/857470

open questions:
1. roopnarine/857470.item.2.csv line 15, contains a reference to non-existing trophic guild with number 0. Currently ignoring this
2. roopnarine/857470.item.2.csv line 113, contains 20.22, and should probably be 20,22
3. roopnarine/857470.item.2.csv line 118, contains 100 103, and should probably be 100,103
4. roopnarine/857470.item.2.csv line 129, contains 100 101, and should probably be 100,101
5. roopnarine/857470.item.2.csv line 178, contains 100103, and should probably be 100,103
6. roopnarine/857470.item.2.csv line 185, contains 129188157142192000000000, ignoring this for now
7. roopnarine/857470.item.2.csv line 186, contains 200 141, and should probably be 200,141
8. roopnarine/857470.item.2.csv line 190, contains 109108188196107000000, ignoring this for now
9. roopnarine/857470.item.2.csv line 207, contains 120 122, should probably be 120, 122
10. roopnarine/857470.item.3.csv line 238, contains 152109183215232000000000000000000000000000000000000000000000000, is ignored.


Currently, all " " are replace with ",", such that cases "100 103" turn to "100,103".  Reported all occurances of these up to item 9.

