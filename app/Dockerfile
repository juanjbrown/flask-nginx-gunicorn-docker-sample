FROM python:2.7

# Copying the requirements for installation to take
# advantage of the caching.
COPY requirements.txt .
RUN pip install -r ./requirements.txt
