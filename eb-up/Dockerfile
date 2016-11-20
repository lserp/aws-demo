FROM python:2.7

# Add sample application
ADD application.py /tmp/application.py
RUN mkdir -p /tmp/sample-app/
RUN touch /tmp/sample-app/sample-app.log
EXPOSE 8000

# Run it
ENTRYPOINT ["python", "/tmp/application.py"]
