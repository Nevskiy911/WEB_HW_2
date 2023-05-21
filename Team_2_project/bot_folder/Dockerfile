FROM python 3.10

ENV APP_HOME /APP_HOME

WORKDIR $APP_HOME

COPY . .

RUN pip install -r requirements.txt

CMD [*python*, *main.py*] 