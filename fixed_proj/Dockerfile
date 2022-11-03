FROM python
WORKDIR /app
COPY app/ /app
RUN pip3 install -r requirements.txt 
CMD ["python", "app.py"]
# CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]
