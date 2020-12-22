# HerokuDashWebApp
For deploying Dash webapps with Heroku

# How to deploy a simple Plotly Dash app on Heroku

* You can view the finished app on [Heroku](https://flying-dog.herokuapp.com/).
* Take a moment to read my [Medium post about deploying Dash apps](https://medium.com/@austinlasseter/how-to-deploy-a-simple-plotly-dash-app-to-heroku-622a2216eb73).
* I also have a gallery of simple Dash apps for learning [here](https://github.com/austinlasseter/plotly_dash_tutorial/blob/master/06%20Heroku%20examples/list%20of%20resources.md).
* If you'd like to learn even more about Plotly Dash, check out my [tutorial repo](https://github.com/austinlasseter/plotly_dash_tutorial) on github!.
* If you'd like to tinker with the colors of your app, try using HEX codes from [HTML Color Codes](https://htmlcolorcodes.com/).
* The `assets` folder contains a file called `favicon.ico` -- you can find and download customized favicons [here](https://www.favicon.cc/). Just replace the current favicon with a new one.
* Plotly Dash apps can only be viewed in a modern browser (like Chrome or Mozilla). They won't render in antediluvian browsers such as Microsoft.

I made requirments.txt file using command pip list --format=freeze > requirements.txt
instead of normal command pip freeze> requirements.txt as otherwise it produced weird path locations in requirments folder

Had to manually adjust requirements.txt file 
mkl-fft==1.2.0
mkl-random==1.1.1
mkl-service==2.3.0
setuptools==51.0.0.post20201207

were changed to 
mkl-fft==1.0.6
mkl-random==1.0.1.1
setuptools==51.1.0

Note I could not find a version of mkl-service
