FROM openjdk

WORKDIR /disktop

COPY ahmed.java .

RUN javac ahmed.java

CMD java ahmed