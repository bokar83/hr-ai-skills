---
name: hr-chart-rules
description: "Chooses the right chart for HR data and sets the rules for labels, colour, scale and small groups, so a chart tells the truth at a glance. Use when the user says what chart should I use, make this chart clearer, chart rules, dashboard layout, or how to show headcount, attrition or survey results."
---

# HR chart rules

Pick the chart that answers the question, then make it honest and readable. Output is a chart specification you can build in any tool, not a picture.

## When to use
- You have HR numbers (headcount, attrition, hiring time, survey scores, training completion) and need to show them.
- A dashboard or slide has too many charts, or the chart is hard to read.
- You are reviewing a chart someone else made.

## When to skip
- You need the analysis itself, with protection for small groups. Use hr-data-insights first.
- The audience needs one number. Show the number, not a chart.

## Inputs needed
- The question the chart must answer, in one sentence.
- The data described in words or as a small table (use made-up or aggregated figures, not individual records).
- Who will read it and where (slide, report, dashboard, printout).

## Steps
1. Write the one message the reader should take away. If there are two messages, plan two charts.
2. Choose the form from the question:
   - Compare categories: horizontal bars, sorted by value unless the categories have a natural order.
   - Change over time: a line for many periods, columns for a few.
   - Part of a whole: a single stacked bar or a table. Use a pie only for two or three parts, never more.
   - Distribution: a histogram or a simple range band.
   - Relationship between two measures: a scatter plot.
   - Exact values matter: a table.
3. Set the axes. Bars start at zero. Lines may start elsewhere only if the axis is labelled clearly. Never cut an axis to make a change look bigger.
4. Label directly. Put the title as the finding (Attrition fell 3 points in Q3), not the topic (Attrition). Label lines and bars on the chart instead of a distant legend. Name units and the time period.
5. Colour with purpose. Use one neutral colour for everything, and one accent for the point you want seen. Do not use red and green alone to separate groups, because many people cannot tell them apart. Check that the chart still reads in greyscale.
6. Protect people. If a group is smaller than the minimum your company sets (often five or ten), combine it or hide it. Never chart a group so small that an individual can be identified.
7. Remove clutter: no 3D, no heavy gridlines, no decoration, no second axis unless it is unavoidable.
8. Add a source line and the date of the data. Add one caveat if the data is partial.
9. Give a test: show the chart to someone for five seconds. They should say the message back.

## Quality bar
- One message per chart. Every number on the chart comes from the data supplied.
- No invented values. Use placeholders if figures are missing.

## Output format
1 The message. 2 Chart type and why. 3 Specification: title, axes, labels, colours, order, notes. 4 Small-group check. 5 A short list of what to cut. 6 The five-second test.

## If input is missing
Ask for the question and the audience. If the data is missing, give the specification with [NEED FACT] placeholders.

## Works with
Run after hr-data-insights. Use executive-brief to write the text that goes with the chart.

## Rules for every skill
- Use only what the user gave. Do not invent facts, quotes, numbers or dates. Write UNKNOWN or [NEED FACT] instead.
- If you are not sure, say so plainly. Never guess to look confident.
- Plain English. No dashes used as punctuation breaks.
- Never send, post or act on anything. Produce drafts for the user to decide on.
