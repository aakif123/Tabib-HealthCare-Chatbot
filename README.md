# Tabib-HealthCare-Chatbot
Purpose : Major Project Team Size : 4 Duration : 10 Months [ Oct. 1, 2021 - June 31, 2022 ] Key Skills : Rasa AI , Python , NLP , Flask , HTML , CSS , JavaScript It is a Web-based Chatbot to automate healthcare management with audio assistance. Users can get immediate medication for their symptoms and book appointments via an audio feature. In addition to text assistance, this chatbot has an audio assistance feature. This feature eliminates the restrictions that visually impaired patients face with currently available text-enabled healthcare chatbots. This voice-enabled chatbot was designed and developed using the Rasa interface for the backend, the Web Speech API, and the Talkify API for voice input and output, respectively. Title: ' TaBiB: Chatbot for Healthcare Automation with Audio Assistance using Artificial Intelligence '. The project was presented and was approved at the 6th National Conference of Science and Engineering (NCSEM), 2022. Tools used : Rasa AI, Python, NLP, Flask, Web Speech API, Talkify API, HTML, CSS in Atom Editor.


****************************************************************************************************
#   Tabib: Chatbot for Healthcare Automation with Audio Assistance using Artificial Intelligence   #
****************************************************************************************************
#   TaBiB Bot Commands   #
**************************

----------------------------------------
````````````````````````````````````````
***Download C++ redistributable***

// https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170
[or]
// https://www.tensorflow.org/install/

----------------------------------------
````````````````````````````````````````
***Download and install Anaconda***

// https://www.anaconda.com/products/distribution

----------------------------------------
````````````````````````````````````````
***Create a new anaconda environment***
*_open anaconda prompt_*

>> conda create -n tabib_bot python=3.8
>> conda activate tabib_bot

----------------------------------------
````````````````````````````````````````
***Update pip***

>> python -m pip uninstall pip
>> python -m ensurepip
>> python -m pip install -U pip

----------------------------------------
````````````````````````````````````````
***Install Dependencies***

>> pip install flask
>> pip install requests

----------------------------------------
````````````````````````````````````````
***Install Rasa***

>> pip install rasa
>> rasa --version

----------------------------------------
````````````````````````````````````````
***Running Rasa server***

>> cd (target  Tabib_Bot\rasabot  directory) [ex: cd C:\Users\Computer Name\Downloads\Tabib_Bot\rasabot]
>> rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml

----------------------------------------
````````````````````````````````````````
***Running Flask for Web App***
*_open another terminal_*

>> cd (target  Tabib_Bot\web_app  directory) [ex: cd C:\Users\Computer Name\Downloads\Tabib_Bot\web_app]
>> flask run

----------------------------------------
````````````````````````````````````````
***To run TaBiB website***
*_open browser_*

>> localhost:5000
[or]
>> http://127.0.0.1:5000/

----------------------------------------
````````````````````````````````````````
***To train rasa bot***

>> rasa train
>> rasa shell nlu

***To view sequence graph of rasa bot***
>> rasa visualize

----------------------------------------
````````````````````````````````````````

****************************************************************************************************
