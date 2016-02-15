
4.12 Time Updater in Servlet
----------------------------
In this program we are going to make one program on servlet which will keep on updating the time in every second and the result will be displayed to you.
To make this servlet firstly we need to make a class named TimeUpdater.  The name of the class should be such that it becomes easy to understand what the program is going to do. Call the method getWriter() method of the response object which will return a PrintWriter object. Use the method getHeader() of the response object to add a new header. We can also use setHeader() in place of getHeader(). The setHeader() method overrides the previous set header. Now by using the PrintWriter object display the result on the browser.


![screenshot 167](https://cloud.githubusercontent.com/assets/17025509/13041248/9c278a70-d3db-11e5-994a-60e8d462a6d0.png)
![screenshot 168](https://cloud.githubusercontent.com/assets/17025509/13041254/aa0313b2-d3db-11e5-87e6-a665558bb7ca.png)
