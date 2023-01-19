# BERT-Chatbot-English

## Instructions to set up the Bert Chatbot English Demo on Local system

1. Clone the repository in your system.
2. Download the model file from https://drive.google.com/file/d/13N8xZbM5C9VBg1sAxOdskqiha0aSwYdX/view?usp=sharing and unzip it in root directory.
3. Install and create a virtual environment by the following step. You'll need <b>python <= 3.7</b> to set it up.
```shell
sudo apt install virtualenv
virtualenv venv --python=python3.7
source venv/bin/activate
```
4. Install the following dependencies
```shell
pip install Flask
pip install boto3
pip install requests
pip install regex
pip install flask_cors
pip install numpy
pip install transformers==2.1.1
pip install torch==1.4.0+cpu torchvision==0.5.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
[ Note : above torch command is for python3.7 and no_cuda, you can use this https://pytorch.org/ site to select the torch version according to our python-version and cuda version if you have ]
```
5. Now run the app.py by the following command 
```shell
python app.py
```
6. You can access the chatbot at  http://127.0.0.1:5000/ 

If you have any other questions or face issues in setting the demo up then kindly reach out to us at letstalk@pragnakalp.com 

For all your Natural Language Processing (NLP) requirements, we are here to help you. Email us your requirement at letstalk@pragnakalp.com and don't forget to check out more interesting <a href="https://www.pragnakalp.com/services/natural-language-processing-services/" target="_blank">NLP services</a> we are offering. 