# AWS-SERVERLESS
Intro to serverless framework. 

In this app we are going to explore event object of s3. The event object contains information from the invoker.The invoker passes this information as a JSON formatted string when it calls invoke and the runtime converts it into an object.

The context object contains information about the invocation, function and invocation environment.

Callback is a function that you can call in non-async functions to send a response. It takes two args an error and a response.
