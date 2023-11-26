## Information
Written by: Brandon Welsh

Start date: 11/19/2023 10:00am

Due date: 11/27/2023 11:59pm

## Program Goals
"Welcome to this module challenge focused on data analysis with Python's Pandas library. As a crucial component in various fields, such as data science, machine learning, and business intelligence, practical data analysis involves examining, cleaning, processing, and extracting useful information from large datasets. This assignment provides a hands-on opportunity to develop these skills.

In this challenge, we'll dive into a dataset from a fictional e-commerce company, exploring and analyzing data to address real-world business questions. Your mission will involve identifying top customers, popular product categories, calculating profits, and more. By the end of this task, you'll have a practical understanding of data exploration, transformation, and analysis, preparing you for more complex data scenarios in your future career." (copied from Bootcamp Spot Module 4 Challenge Instructions page)

## Resources Utilized
This section is dedicated to keep track of what I used to help complete this program.

70% Class Notes - We had an abundance of great practice on pandas in class so far. I frequently went back to class notes, copied a function that was close to what I needed, then modified it so it worked in this program (changed variable names and syntax and whatnot). I did that for the bulk of this assignment.

25% AI assistance - Occasionally I ran into an error that I just couldn't figure out so I showed my work to an AI and talked it through what I was doing until it was able to figure out what I did wrong and helped me correct my mistake. I also used it to figure out the first Lambda function, shown below, which I then modified for the remaining three columns that needed it:

    cleaned_summary_df['Shipping Cost'] = (cleaned_summary_df['Shipping Cost']/1000000).apply(lambda x: f'${x:.2f}M')

5% Google - used to figure out that .agg() method existed. If we covered this in class, I must have totally forgotten because I was stumped lol.

## Bugs

This isn't a bug but rather a special note: there was a random .DS_Store file in the challenge files from bootcamp spot which I promptly deleted because it's specific to macOS and Apple is the bane of my existence so I felt obligated to purge that bit of heresy from my holy Windows 10 system.

There are no bugs with this program, it's just a simple click "Run All" and the outputs just show up. I quite like Jupyter notebooks.

## Update Log
11/19/2023: Created github repo. Finished part 1: Exploring the data

11/24/2023: Finished part 2: Transform the data and part 3: Confirm your work

11/26/2023: Finally quit procrastinating and finished part 4: Summarize and analyze. It's done, it works. Updated README.md and got this thing ready for submission.
