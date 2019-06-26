# TDI_Milestone
Latest version of TDI Milestone Project

The deployed Heroku app uses two concurrent web processes: a Bokeh server serving a Bokeh Application, and a gunicorn server serving a Flask web app.
The Bokeh Application includes three dropdown menu widgets that trigger python callbacks to update the stock data via API call and to update the range plotted on the x axis.
Furthermore a Javascript callback is used to update the y-axis range when the x-axis range changes. 
The Bokeh plot tools are auto-engaged to zoom and pan the x-axes of the first and second plot.
Financial indicators (MACD and signal with "histogram") are plotted in the middle plot.
The volume is plotted in the bottom plot.
All the x-axes are linked.

