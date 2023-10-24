In order to run this program you must create an account at https://fred.stlouisfed.org/
and request an API KEY.

This program will grab data up to 10 years from date of running the program if the data is available,
So keep in mind if you want specific dates you must modify the program.

****Known issues with mplcursor in juypter notebook****
When importing mplcursor you may need to use the command %matplotlib widget
for it to work correctly.
When using the cursor on one chart and the scrolling down to the next chart,
mplcursor can crash and become unfunctional. I belive this to be an issue with
having multiple charts and not the code itself, however I am not entirely sure.
