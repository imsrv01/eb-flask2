# eb-flask2

git clone 
cd eb-flask2
sudo apt-get install -y python3-venv
python3 -m venv virt
source virt/bin/activate
pip3 install flask==1.0.2
pip3 freeze > requirements.txt

pip3 install requirements.txt
python3 application.py


eb init -p python-3.6 flask-tutorial --region us-east-1
eb init
eb create flask-env
eb open
