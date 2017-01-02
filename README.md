#WeatherForecast

WeatherForecast is a simple application to check weather forecast in a specific place. WeatherForecast provides information about actual weather parameter, localization of your place and predicted temperature, atmospheric pressure, humidity and height of precipitation.

##Installation
1. Install and configure PostgreSQL and Postgis (see [Install PostGis](https://docs.djangoproject.com/pl/1.10/ref/contrib/gis/install/postgis/)).
2. Install python 3
```
$ apt-get install python3
```
3. Setup a new virtualenv with python3
```
$ mkvirtualenv --python=/usr/bin/python3 <virtualenv_name>
```
3. Check virtualenv python version
```
$ python -V
```

You should have 3.x.x version.

4. Go to the repository directory, activate your environment and install requirements using pip:
```
$ pip install -r Requirements.txt
```

6. 

##License

WeatherForecast is licensed under the terms of the MIT License (see the file LICENSE).
