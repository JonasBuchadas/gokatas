[![Go Reference](https://pkg.go.dev/badge/github.com/jreisinger/gokatas.svg)](https://pkg.go.dev/github.com/jreisinger/gokatas)
[![Go Report Card](https://goreportcard.com/badge/github.com/jreisinger/gokatas)](https://goreportcard.com/report/github.com/jreisinger/gokatas)
[![test and scan](https://github.com/jreisinger/gokatas/actions/workflows/test-scan.yaml/badge.svg)](https://github.com/jreisinger/gokatas/actions/workflows/test-scan.yaml)

# Go katas

Katas (形) are practiced in martial arts as a way to internalize the movements
and techniques so they can be executed and adapted under different
circumstances, without thought or hesitation. Let's try the same with Go code.

## Why

I've been learning to program in Go. I work in the sysadmin/devops and security
areas so I don't normally get to program every day. But I still want to keep my
coding skills fresh. Maybe even improve them. I use gokatas as one of the ways
to achieve this.

## How

The approach is pretty low-tech. Go katas is basically a
[list](https://pkg.go.dev/github.com/jreisinger/gokatas#section-directories) of
packages and commands (package main) that you should understand and then be
rewriting from scratch or partially. There's a command to show katas and your
progress:

```
$ go run cmd/gokatas.go -c 2 -d 14
Kata              Last done    Done  Level     Topics
----              ---------    ----  -----     ------
boring/boring     0 days ago     1x  beginner  concurrency, design
boring/channel    0 days ago     1x  beginner  goroutines, channels
areader           3 days ago     2x  beginner  interfaces, io.Reader
----                           ----
3                                4x 
```

It's important to practice regularly because repetition creates habits, and
habits are what enable mastery. Set a goal that you can meet, e.g. 45 minutes
every day before work. Start by taking baby steps. At first it's fine even if
you only read through one of the beginner level katas.

After enough time it will require much less will power to practice. Your
programming moves will start looking simpler and smoother. If you feel
comfortable enough with a kata, stop practicing it (for some time) and pick up
one that interests you and is slightly beyond your current ability.

## Initial setup

1) [Install Go](https://go.dev/doc/install).

2) [Fork](https://github.com/jreisinger/gokatas/fork) and then clone the repo: `git clone git@github.com:<you>/gokatas.git`.

3) Start practicing:

```
cd gokatas
> katas.md # if you are not me :-)
go doc
```
