---
title: "CLI Brain Teaser"
date: 2025-05-21
categories: [Projects]
tags: [jekyll, minimal-mistakes]
---

One morning I woke up, and had this urge to build a long lasting project, but I recently got sick of following those "GitHub project tutorials" that just leave you with boiler plate code (no hate to those, they're fantastic learning tools) and figured I'd learn more from building from the ground up. So here we are, after some mulling about I landed on the idea of building a sort of tutor / brain teaser CLI based game built to help someone get the juices flowing. The idea came to me as I was thinking about how older folks who read news papers typically start their day with sudoku or other similar puzzles. I found the notion of waking up to do some light problem solving to have some great benefits and figured "why not do something like that but make it practice mathematics".

Having recently flunked a semester in calculus, who better to help educate the masses than Myself?

## Design

The overarching idea is simple: build a lightweight puzzle game that allows users to select what they would like to practice (i.e arithmetic, geometry, trig, etc.) and the game loop will begin as it spits out simple problems that the user will try to answer, until eventually getting one wrong which ends the game loop and gives your final score 

(ex. each question is 10 points answering 10 correctly will net 100 points). 

Currently it is as simple as that but at some point I would like to add a sort of study guide to aid those who haven't touched the material

The display is going to be built using ncurses to be lightweight and not lock out any users with older hardware. The game loop will be fully built from the ground up and a lot of the mathematical handling of course will be using the 'math' header in C++. There are most definitely better utilities and languages I could've used but I can't help it I'm just a glutton for punishment and C/C++ provides me the whip with which to flagellate myself.

This is going to be an ongoing development, as I've never made a CLI based app like this. I will update this post as changes come.
