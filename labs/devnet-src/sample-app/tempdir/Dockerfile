FROM python
RUN pip install flask
Copy  ./static /home/myapp/static/
Copy  ./templates /home/myapp/templates/
Copy  sample_app.py /home/myapp/
EXPOSE 8080
CMD python3 /home/myapp/sample_app.py
