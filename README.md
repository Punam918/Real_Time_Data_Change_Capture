
# Real Time Changed Data Capturing
A real time data changed data Capturing using postgresql, docker, debezium, apache kafka, confluent control centre.


### Steps
      1. Contanarized environment was setup by using docker and running docker-compose up -d
      2. Using python's faker library to crete fake data to be loaded on financial_db database.
      3. Running the python file
      4. Going to port 8080 for connenting postgresql.
      5. Going to port 9021 for confluent centre which is a cloud based software for kafka.
      6. Going on terminal and writing psql -U postgres -d financial_db to connect to the database on terminal.
      7. Writing postgresql query to change the data, optimize and record the data change on the terminal.
      8. When data is modified using postgresql it can be seen at Vs code's terminal with new column modified by, modified at for time, and change info for what changed.

### Images


![Image](https://github.com/user-attachments/assets/2d189448-73da-4346-a675-97d2805488c3)





![Image](https://github.com/user-attachments/assets/fb42a98c-cbb9-47d2-9f7b-f758fcff80fe)






![Image](https://github.com/user-attachments/assets/e294236f-6703-4f09-b59e-5798c1f26a62)



