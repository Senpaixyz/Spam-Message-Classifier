# SPAM MESSAGE CLASSIFIER

Spam messages are characterized as anonymous messages often containing phishing links. These unsolicited messages, transmitted via the internet or SMS, typically originate from unknown sources. They commonly take the form of robo-texts and are associated with spam that promotes products or scams. One prevalent tactic is sending deceptive messages like "Congratulations! You are the Winner!" in an attempt to trick recipients into clicking on malicious links and divulging private information.

[![N|Solid](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/landingpage.PNG?raw=true)](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/landingpage.PNG)


## Spam Message Characteristics

- Connection Behavior.
- Falsifying the Envelope Sender Address.
- Disguising the Subject: Header.
- Camouflaging the HTML Body.
- Attempting to Fool Signature Detectors.
- Unnecessary Encoding.
- Grokking the Site.



## Features

- User Friendly Graphical User Interface.
- The model has 98% accuracy from the trained datasets
- It can be deployed in realtime or be use as API.

### Classification Report
The trained model attained the accuracy of 98% from the trained model. The precision of 2 classes which are ham(99%) and spam(93%). While the recalled of the said model according to the classification report got ham(99%) and spam(92%). The developer tried to minimize the inbalance data by 8% according to the f1-score.

[![N|Solid](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/classification_report.PNG?raw=true)](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/classification_report.PNG)
### Datasets

That datasets contains overall total of 5572, that compoased of  4825 ham message and 747 spam messages. You can download [datasets](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/data/datasets/spam.csv) from this github reporsitory.

[![N|Datasets](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/datasets.PNG?raw=true)](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/datasets.PNGG)

### Model Prediction
##### Ham Message
The sample figure below shows the prediction of the model from the given phrase in the input box. The message predicted by the model was a kind of Ham Message meaning it is not type of spam message.

[![N|Ham Message](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/ham.PNG?raw=true)](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/ham.PNG)

##### Spam Message
While figure below is the message that predicted as a spam.

[![N|Spam Message](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/spam.PNG?raw=true)](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/images/spam.PNG)

## Packages
Additional Packages
| Package | URL |
| ------ | ------ |
| Model File | [MODEL PKL](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/models/model.pkl)|
| TFR | [TFR PKL](https://github.com/Senpaixyz/Spam-Message-Classifier/blob/master/models/tfr.pkl) |

## Installation

For first time use please download all the packages needed in this web application, please create virtual environment from the Pycharm IDE. Then open the terminal and run:

```sh
pip install -r requirements.txt
```
After use install all the dependency that needed in this web application. just simply type in the terminal:

```sh
python app.py
```
Verify the deployment by navigating to your server address in
your preferred browser.

```sh
http://127.0.0.1:5000/
```
This web application was supported by ngrok api. Uncomment this in the app.py to use it and shared this web application from another devices and via internet.

`//run_with_ngrok(app)`

## License

MIT

**Free Web Application Developed by Jheno Cerbito**
