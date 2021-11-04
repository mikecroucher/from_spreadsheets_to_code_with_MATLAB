# The art of coding without coding with MATLAB

You're going about your day in the lab, analysing and collecting data, writing papers and drinking coffee when your PI sends you a message.

![](./yourtask.png)

"No problem", you think, "I've got a spreadsheet built by the last postdoc who worked here, it'll take care of that no problem. We've been using it for years."

![](./task_rules.PNG)

uh oh!

# You have a problem that can be solved by coding, now you have two problems

When someone has invested a lot of time into learning a computational tool, telling them that it is a bad tool and that they should do something else entirely is not necessarily helpful.  Even if you are right, all you've really done is given them a set of new problems.  In this case one of those new problems is **learn to code**.  

'**Learn to code**' is good advice but its difficulty should not be underestimated.  Learning to code is a time-consuming affair (some might say never-ending) and in an ideal world we would always be productive while learning.  

The MATLAB ecosystem supports you at every level of your programming career, even when you've never written a single line of code in your life. 

## Importing the spreadsheet and generating our first Live Script

There are few things more daunting to a new programmer than an empty command prompt and your mind may be full of questions.  Where can I find help?  How can I learn how to program in this language?  Is there anyone I can talk to to help me further, either from MathWorks support or the MATLAB user community?  With MATLAB, the answer to these questions are just a click away in the resources tab.

![](./resources.PNG)

Today, however, we are just going to dive right in.  We need to import some data so let's click on the import data tab and select our spreadsheet.

![](./desktop.png)

This opens the Import tool which gives a preview of the spreadsheet and a whole bunch of options we can select.  Everything seems OK with this very simple, two column spreadsheet so we'll not change any of the automatically detected options.  Instead we'll click on **Import Selection** and choose **Generate Live Script**

![](./livescript_select.gif)

The result is a [Live Script](https://uk.mathworks.com/help/matlab/live-scripts-and-functions.html) which combines text, code and results into one interactive document.  The code is commented and our report has begun.  We've done something useful, solved the blank-page problem and are on our way to solving the larger problem at hand.

## Live tasks -- the art of coding without coding

One of the first things anyone does after importing some data is plotting it.  As with importing, this is such a common task that MATLAB provides additional assistance for those who want it.

Click on the part of the Live Script where you'd like to add your plotting code and then click on **Insert** -> **Task**

You'll see a list of tasks that will vary according to which selection of MATLAB toolboxes you have installed.  Here I have tasks ranging from plotting and outlier removal included in base MATLAB through to more specialist things such as clustering and Audio Feature Extraction.  I choose the **create plot** task and the graphical user interface (GUI) is loaded where I want the code to appear.

![](./plot_task.gif)
Audio
