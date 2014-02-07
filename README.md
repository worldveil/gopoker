gopoker
=====

Uses same algorithm and techniques as Deuces: 
https://github.com/worldveil/deuces

Hand evaluator command line utility for Go for 5, 6, and 7 card hands. Hands are given a rank in the range `[1, 7462]`, where 1 is a Royal Flush.

Example usages:
```
$ go run evaluate.go As Ks Qs Js Ts 7h
1
$ go run evaluate.go 7h 5d 4c 3s 2h
7462
$ go run evaluate.go 7h 5d 4c 3s 2h
7462
$ go run evaluate.go Ts 9d 8c 7c 6h As
1604
```