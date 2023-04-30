# kafka-course-project
The project is to create a data flow of patient information.

## setup project

- Create al virtual environment (`virtualenv venv`).
- Activate your virtual environment: `source venv/bin/activate`.
- Install requirements: `pip install -r requirements.txt`.
- Create a config file, you can use `config.example.ini` as a reference.

## produce messages
Execute `python3 producer.py [config file name].ini`

## consume messages
Execute `python3 consumer.py [config file name].ini`
