# hng9backendT2
HNG 9 Backend Task 2
Here's the STAGE 2  TASK
Backend Stage 2 Task
Study Material
REST API TUTORIAL https://www.gravitee.io/blog/rest-api-tutorial

Task Description
Using the same server setup from stage one
Create an (POST) api endoint that takes the following sample json:
{ “operation_type”: Enum <addition | subtraction | multiplication> , “x”: Integer, “y”: Integer }
Operation can either be addition, subtraction or mutiplication
x can be a number and Integer datatype
y can be a number and Integer datatype
Based on the operation sent, perform a simple arithmetic operation on x and y
Return a response with the result of the operation and your slack username
{ “slackUsername”: String, "operation_type" : Enum. value, “result”: Integer }

Push to GitHub
Sample Input { “operation_type”: Enum <addition | subtraction | multiplication> , “x”: Integer, “y”: Integer }
Sample Response Format { “slackUsername”: String, “result”: Integer, “operation_type”: Enum.value }

Task Duration: 3 Days

Submission Details:

Use the slack command /grade along with your hosted URL. If it passes/fails, you would know immediately.
/grade https://yoururl.com

Deadline: Saturday 5th Nov 2022 - 11:59PM WAT

Bonus
We will send in a random string to the "operation_type" field . This string will be an operation written in words, for example “Can you please add the following numbers together - 13 and 25.”
This string will not be revealed ahead of time. On marking day, we will reveal the string and test it against all scripts.
