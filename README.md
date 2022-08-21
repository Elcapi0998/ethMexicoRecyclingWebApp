# ethMexicoRecyclingWebApp

The Recycling Web App is Cheve's app that allow users to exchange their glass bottles for MATIC.
The app consists on mainly 2 parts, the former part allows to connect the user's wallet with the app, meanwhile, the latter part emulates the process when
the user introduces a new bottle to the machine in exchenge of MATIC. The transfer query is then send to an API which handles the transaction.

To run the project in localhost run:
```python
python3 -m http.runserver 8080
```

To view the project in the browser:
```http 
http://localhost:8080/recycling-machine.html
```
The sample machine this app is emulating is shown below.


![Bottle Recycling Machine](https://circulareconomy.europa.eu/platform/sites/default/files/styles/large/public/bbot_visuel_0.png?itok=eOJh2apK)
