# 2d-cellular-automata
Coding exercise I completed as part of an interview process: build an automata that features 'the game of life'

## Overview
This was a coding exercise given to me by a prospective employer. The 'Instructions.docx' file will show the exact details, rule sets, and requirements of the challenge.

## Explanation of legitimacy of existing code, as-is
They told me this should take 1 hour to complete, but it took me about 4.5 hours (including research time, writing out the extra documentation, and review).

In an effort to truly preserve the 'challenge' nature of this exercise, I have kept this code exactly as it was at the time of completion and submission to the company.

I have not come back to update the various bits of it that I think could have been done better. In fact, those same possible revisions are already outlined in a REVISIONS.md file and they still apply.

## Instructions to run automata
1. Download ZIP file
2. Extract contents
3. Load index.html into a browser
4. Click Generate to start cycle

### Answer to question: What is Generation 20?
Note: The below seed data is also featured in 'datasets.md'.

Given seed data for generation 1:  
0 0 0 0 0 0 0 0 0 0  
0 0 1 1 0 0 0 0 0 0  
0 0 0 0 2 0 0 0 0 0  
0 0 0 1 2 0 0 0 0 0  
0 0 0 0 0 0 0 0 0 0  
0 0 1 0 0 0 0 0 0 0  
0 2 1 0 0 0 0 0 0 0  
0 2 0 0 0 0 0 0 0 0  
0 0 0 0 0 0 0 0 0 0  
0 0 0 0 0 0 0 0 0 0

Result for generation 20:  
0 0 0 0 0 0 0 0 0 0  
0 0 0 0 0 0 0 0 0 0  
0 0 0 0 0 0 0 0 0 0  
0 2 2 0 2 2 0 0 0 0  
0 0 0 0 0 0 1 3 1 0  
0 0 2 0 0 0 0 3 0 0  
0 0 0 2 0 0 1 3 1 0  
0 0 0 0 0 0 2 0 0 0  
0 0 0 0 2 2 0 0 0 0  
0 0 0 0 0 0 0 0 0 0