FROM python:3.11-slim


WORKDIR /app

COPY requirements.txt .

RUN pip install --no-cache-dir --upgrade pip
RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000

CMD ["python3","app.py"]

####
#FROM python3-alpine

#COPY --from=builder



