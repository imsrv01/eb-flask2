# eb-flask2

# Clone and test the application locally
git clone https://github.com/imsrv01/eb-flask2.git

cd eb-flask2

sudo apt-get install -y python3-venv

python3 -m venv virt

source virt/bin/activate

pip3 install -r requirements.txt

python3 application.py

# deploy in aws elastic bean stalk
eb init -p python-3.6 flask-tutorial --region us-east-1

eb init

eb create flask-env

eb open
