FROM django:onbuild

#COPY /Users/subhan/docker /usr/src/app
#ADD /Users/subhan/docker /usr/src/app
#COPY . /usr/src/app

RUN pip install -r /usr/src/app/requirements.txt
 
WORKDIR /usr/src/app 

EXPOSE 8000

ENTRYPOINT ["python", "manage.py", "runserver",  "0.0.0.0:8000"]
 #8000:8000 -d django bash -c 

