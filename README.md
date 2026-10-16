# Who Gets a Call?

A hands-on classroom activity on fairness in AI, built by the FACTS-H Lab, IIIT Kottayam, for the AICTE QIP PG Programme in AI&DS.

**Open the activity:** https://ansiths-iiitk.github.io/fair-demo

It runs in any web browser, on a phone or a laptop. There is nothing to install, no login, and no code to run.

## What the activity is about

A college uses an AI model to find students who may fail, so that a support team can call them early. The page lets you decide who gets a call and see who is helped, who is called unnecessarily and who is missed.

- **Part 1: Set the cut-off.** Move a slider for two groups of students and try three challenges about treating both groups equally.
- **Part 2: Delete the column.** Train a small model on past internship shortlists, remove information from it, and see whether the result becomes fair.

## Data

All students and records on the page are made up for teaching. No real student data is used. The differences between groups were chosen to illustrate the ideas and are not real findings about any group.

## How it works

The whole activity is one file, `index.html`. The data and a small logistic regression model are written in plain JavaScript inside the page, so it works without a server.
