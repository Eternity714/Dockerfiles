FROM python:3.11-rc-buster

COPY AKTools/requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "-m", "aktools" ]
