# RabbitMQ

### RabbitMQ is the most widely deployed open source message broker.
### Default port for RabbitMQ is 5672

### To work with RabbitMQ you need to do:

 - Download Docker 
   
   - run *docker run --name rabbitmq -p 5672:5672 rabbitmq*
   
   
 ### NOTE: If you create project step by step:    
 
 - In Visual Studio Code open terminal and write *npm init -y* that initializing package.json
 - In Visual Studio Code open terminal and write *npm install amqplib*, installing the module that is used in the project
 
 ### Add some changes to package.json:

 "scripts": {
    "publish": "node publisher.js",
    "consume": "node consumer.js"
  }
 
 - With this two lines you can execute consumer.js and publisher.js through terminal in next way:
 
   - consumer.js: *npm run consume*
   - publisher.js *npm run publish 4*. Node: You can add any number you want. But in code you can see that you need to add number. If you do not add, than the output will be marked as "Job sent successfully *undefined*".
 
 ### NOTE: If you use all my code, than you only need to: 
 
 - In Visual Studio Code open terminal and write *npm install amqplib*, installing the module that is used in the project
 
 - Execute the project:
 
   - consumer.js: *npm run consume*
   
   - publisher.js *npm run publish 4*
 

 
