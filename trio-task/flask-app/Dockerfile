#Use Python Image
FROM python:3.7
# Install apt dependencies
RUN pip install flask flask-sqlalchemy pymysql
# Copy contents into image
COPY . .
# run pip dependencies

# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["python", "app.py"]
