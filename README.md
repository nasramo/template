# GCSE Calendar template
This is a template of my GCSE calendar, and if you read on you can find my documentation on how to make a working calendar similar to the one I made for the May/June 2022 exam series. Click any link in the contents to find a specific section, or use `Ctrl`+`F` to find what you need.

## Contents
### Introduction
### Building the calendar
### Placing exams in calendar
- Quick reference to exam snippets
### Adding new subjects - calendar
### Adding new subjects - specifications
...

## Introduction
The idea of making a GCSE calendar website occurred to me in the half term between February mocks. I didn't like having paper calendars: I hated the faff of searching through my pockets to find a single piece of paper and could never find mine so always had to rely on others to tell me what exams we had. If only we had a website we could easily check to see our exams and their details! So I began working around then, planning using my trusty notebook, and came to a design I liked. The page wasn't going to be mobile-friendly at first, but when I discovered frameworks, I decided I may as well put in a bit more effort since the framework would be doing most of the heavy lifting for me. (This uses Bootstrap 4, even though there is the later BS5 which was out at that time, primarily because I found more documentation for the slightly older version!)

This guide will help you with the main parts of building this calendar. I might experiment with creating a page which generates the code and adds different features by clicking buttons, but this will help you copy and paste code snippets to create a functional page not dissimilar to the one I made. You should start with X lines of HTML in this template and end with well over 100 lines by the end!

## Building the calendar
First, we must start by building the actual calendar where the exams will go. Keeping a calendar ready on either a phone or split screen will be useful for this part. Creating the calendar uses a table in HTML, which is composed of multiple rows and cells, so first create the row which will form the days of the week. 

To create this row, use the `<th></th>` and `<td></td>`tags like so:

```html
<th>
  <td>Mon</td?
  <td>Tue</td>
  <td>Wed</td>
  <td>Thur</td>
  <td>Fri</td>
</th>
```
The `<th>` tag creates a row which is emphasised as the header row. You can edit the CSS for this if you want.
	
	I used 5 days since 7 made the exams look quite cramped on smaller devices and will continue with this through this guide but feel free to adjust things to your liking.


