# Lambda-Deep-Dive

Lambda in AWS is a serverless computing service that allows users to run code in response to events without provisioning or managing servers.

Examples of such events:

![lambda](./img/3.png)

![lambda](./img/1.png)

![lambda](./img/2.png)

![lambda](./img/4.png)

![lambda](./img/5.png)

![lambda](./img/6.png)

![lambda](./img/7.png)

![lambda](./img/8.png)

![lambda](./img/9.png)

![lambda](./img/10.png)

![lambda](./img/11.png)

![lambda](./img/12.png)

![lambda](./img/13.png)

![lambda](./img/14.png)

![lambda](./img/15.png)

## What is a Lambda Runtime

- A Lambda runtime, in simple terms, is the environment provided by AWS Lambda that allows you to run your function code. It includes the language interpreter or the execution environment needed for your code. For example, if your Lambda function is written in Python, the runtime will be a specific version of Python, such as Python 3.8, which interprets and executes your Python code. The runtime takes care of managing the resources your code needs to run and integrates with other AWS services to process events and execute the function accordingly. Essentially, it's what allows your function to run within the AWS ecosystem without needing to manage servers or operating systems.

![lambda](./img/17.png)

![lambda](./img/16.png)

![lambda](./img/18.png)

![lambda](./img/19.png)

## What is a Lambda Handler

- In simple terms, a Lambda handler in AWS is like the main function in your code—it's the starting point where AWS Lambda begins executing your custom code when the function is triggered.

- It is the entry point or function within an AWS Lambda function that is executed when the function is invoked. It typically specifies the code to be executed and any necessary event data processing.

![lambda](./img/20.png)

- When a request is made to an AWS Lambda function, it's typically divided into two main components: the event object and the context object. The event object contains the data or information about the event that triggered the Lambda function, such as an HTTP request or a message from an AWS service. The context object provides runtime information about the Lambda execution environment and allows the function to interact with AWS services and resources, such as logging or accessing configuration settings. These two objects work together to provide the necessary inputs and context for the Lambda function to execute successfully.

![lambda](./img/21.png)

- The event object and the context object are passed into the handler method, where they are used to run some processing and return a result


#### See event handler template below: 

![lambda](./img/22.png)
![lambda](./img/23.png)
![lambda](./img/24.png)
![lambda](./img/25.png)
![lambda](./img/26.png)
![lambda](./img/27.png)
![lambda](./img/28.png)
![lambda](./img/29.png)

#### Lambda configurations:

![lambda](./img/30.png)
![lambda](./img/31.png)
![lambda](./img/32.png)
![lambda](./img/33.png)
![lambda](./img/34.png)
![lambda](./img/35.png)