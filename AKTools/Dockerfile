FROM python:3.11-rc-alpine3.16

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "-m", "aktools" ]
