FROM openjdk
WORKDIR usr/lib
ENV MONGO_DATABASE=customerdb
ENV MONGO_URL=mongodb://localhost:27017/customerdb
ADD ./target/customerservice-0.0.1.jar /usr/lib/customerservice-0.0.1.jar
ENTRYPOINT ["java","-jar","customerservice-0.0.1.jar"]