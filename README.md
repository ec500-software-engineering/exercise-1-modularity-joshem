# EC500 Heart Monitor Mock application

## Prerequisites

1. Python 3+. Follow download here: https://www.python.org/downloads/. Installation tips for various operating systems can be found here: https://realpython.com/installing-python/.
2. A terminal running (Putty [Windows] or Terminal [Mac/Unix] or whatever the user prefers)

## Run instructions
```python main_app.py```

## Async - Exercise 1

For this model, our group modeled the heart monitor on five different threads; the blood oxygen/blood pulse/blood pressor sensors, the realtime data processor, and the prediction engine. The sensors periodically simulate readers by randomly generating data. We display data on a console, but have modules that could be modified to allow for texting/emailing/etc.
