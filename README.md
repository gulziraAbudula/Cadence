# Cadence

CodePath WEB103 Final Project

Designed and developed by: Gulzira Zara Abdullah

🔗 Link to deployed app:

## About

### Description and Purpose

Cadence is a study planner made for students who don't have the same amount of energy or focus every day. Instead of giving students the same type of schedule every day, Cadence starts from what a student wants to accomplish in a week, then builds each day's plan by assigning tasks based on the student's energy level, focus level, and how much time they have that day.

If a student doesn't get through everything in a given week, unfinished tasks roll forward into the next week's plan instead of being marked as a failure. The goal is to help students make realistic study plans that they can actually follow, instead of planning too much and feeling overwhelmed when they can't complete everything.

### Inspiration

I got the idea for Cadence from my own experience with planning my schoolwork. I like making plans and organizing everything I need to get done, but I noticed that my productivity isn't the same every day. Some days I have a lot of energy and can focus for hours, while other days I might be tired, stressed, or just not able to concentrate as well.

Most planners don't really account for that. They assume that if I have three hours available, I can always use those three hours the same way. I wanted to build something that takes my current energy, focus, available time, and the difficulty of my tasks into account when creating my daily plan.

The idea behind Cadence is that being productive isn't about doing the maximum amount of work every day. It's about finding a realistic rhythm that works for you.

## Tech Stack

Frontend: React, Vite, React Router

Backend: Node js, Express, PostgreSQL

## Features

### Task Management

Students can create, view, edit, and delete their assignments and study tasks. Each task can include information such as the estimated time, priority, difficulty, deadline, and the type of day it is best suited for.

[gif goes here]

### Daily Check-In

Students can check in at the beginning of the day by entering things like their energy level, focus level, and how much time they have available. Cadence uses this information when creating their daily plan.

[gif goes here]

### Adaptive Daily Planner

Cadence creates a daily study plan based on the student's tasks and their current capacity. For example, on a high-energy day it may prioritize difficult assignments, while on a low-energy day it may suggest easier tasks such as reviewing notes or completing a reading.

[gif goes here]

### Weekly Rollover
If a student doesn't finish everything they planned for the week, unfinished tasks automatically carry over into the next week's plan instead of being lost or marked incomplete. Cadence is built around the idea that a rough week is normal, not a failure.
 
[gif goes here]
 
### Proactive Re-Scoping *(planned as a stretch feature)*
Partway through the week, Cadence could look at a student's pace and flag it if they're unlikely to finish everything — for example, "At this pace, you may not finish 3 of these 8 tasks. Want to move the lowest-priority ones to next week now?" This goes beyond simply rolling tasks forward after the fact, and gives students a chance to re-plan mid-week instead of finding out on Sunday.
 
[gif goes here]

### Reschedule Tasks

If a student can't finish a task or doesn't have the energy to work on it that day, they can reschedule it instead of simply deleting it. Cadence moves the task to another day so the student can keep their overall workload organized.

[gif goes here]

### Task Status Tracking

Each task included in a daily plan has its own status — pending, completed, or skipped — so a student's history reflects what actually happened, not just what was originally planned.

[gif goes here]

### Weekly Progress

Students can see what they have completed throughout the week and compare their planned workload with what they actually completed.

[gif goes here]

### Course Organization

Students can organize their tasks by course so they can keep track of everything they need to do across multiple classes in one place.

[gif goes here]

### Filtering & Sorting

Students can filter tasks by course or priority, and sort by due date or difficulty, to quickly find what needs attention first.

[gif goes here]

### Due Date Validation

Cadence rejects a task submitted with a due date in the past, preventing students from accidentally creating an impossible deadline.

[gif goes here]

### Database Reset

The app includes a script that rebuilds the database and reseeds sample data, allowing the environment to be reset to a known state during development.

[gif goes here]

### Graceful Error Handling

Cadence returns clear, specific error messages instead of failing silently — for example, if a plan is generated with no available tasks.

[gif goes here]

### Task Splitting *(planned as a stretch feature)*

Large assignments can be broken into smaller steps so students don't have to complete everything in one session. For example, a four-hour research paper could be divided into finding sources, creating an outline, writing, and editing.

[gif goes here]

### Responsive Design

Cadence is designed to work across different screen sizes so students can use it from their laptop, tablet, or phone.

[gif goes here]

## Installation Instructions

[instructions go here]
