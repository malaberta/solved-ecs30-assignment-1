Download Link: https://assignmentchef.com/product/solved-ecs30-assignment-1
<br>



<h1>Exercise 1: vim Tutorial</h1>

Complete the vim Tutorial under Piazza-&gt;Resources.

File to submit to Gradescope: rain.txt

<h1>Problem 1: annualincome.c</h1>

Write a program that reads in an hourly wage and calculates the total income over the course of an entire year assuming 40 hours of work a week every week of the year. Example output:

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="d6a4a5b1afa5b3ba96a6b5e7e1">[email protected]</a> <sup>˜</sup>]$ ./annualincome What is your hourly wage? 5.00

Your total income over a year is 10400 dollars and 0 cents

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="a3d1d0c4dad0c6cfe3d3c09294">[email protected]</a> <sup>˜</sup>]$ ./annualincome

What is your hourly wage? 18.33

Your total income over a year is 38126 dollars and 40 cents

File to submit to Gradescope: annualincome.c

1

<h1>Problem 2: finalgrade.c</h1>

Write a program that calculates your final grade. Your program will read your current grade (out of 100 points), the value of the final as a percentage, and your final exam score (out of 100 points) from stdin and compute your final grade as a percent. All numbers should be whole numbers. Round up fractional final grades. Example output:

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="a3d1d0c4dad0c6cfe3d3c09294">[email protected]</a> <sup>˜</sup>]$ ./finalgrade

What is your current grade? 76

How much is the final worth? 20

What is your final exam score? 96

Your final grade is 80%

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="97e5e4f0eee4f2fbd7e7f4a6a0">[email protected]</a> <sup>˜</sup>]$ ./finalgrade

What is your current grade? 100 How much is the final worth? 20

What is your final exam score? 77

Your final grade is 95%

File to submit to Gradescope: finalgrade.c

<h1>Problem 3: primerib.c</h1>

Chef John Mitzewich of Food Wishes fame recommends the following method to cook prime rib, which he affectionately calls “Method X”<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a> . You have a prime rib that weighs <em>x </em>pounds. Chef Mitzewich orders you to cook your rib at 500 degrees Fahrenheit for 5<em>x </em>minutes, turn off the oven (<em>do not open the door</em>), and let the rib continue to cook in the oven for 2 hours. Write a program that outputs the total time that a rib weighing <em>x </em>pounds is in the oven with the following format:

Your rib will be in the oven for <em>h </em>hours, <em>m </em>minutes, and <em>s </em>seconds.

You must have <em>h</em>≥0, 0≤<em>m</em>≤59, and 0≤<em>s</em>≤59. Example output:

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="a2d0d1c5dbd1c7cee2d2c19395">[email protected]</a> <sup>˜</sup>]$ ./primerib

How many pounds is your prime rib? 3.75

Your rib will be in the oven for 2 hours, 18 minutes, and 45 seconds.

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="691b1a0e101a0c0529190a585e">[email protected]</a> <sup>˜</sup>]$ ./primerib

How many pounds is your prime rib? 5.35

Your rib will be in the oven for 2 hours, 26 minutes, and 45 seconds.

File to submit to Gradescope: primerib.c

2

<a href="#_ftnref1" name="_ftn1">[1]</a> Last updated January 8, 2017

<a href="#_ftnref2" name="_ftn2">[2]</a> No, really, this is a <a href="https://foodwishes.blogspot.com/2010/11/prime-time-for-revisiting-prime-rib-of.html">recipe,</a> and it works.