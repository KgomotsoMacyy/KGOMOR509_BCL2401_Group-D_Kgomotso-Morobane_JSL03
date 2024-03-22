# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: Example 1(Imperative):
https://www.loom.com/share/efdc5373577d4d71a4f62f4eba4c420e?sid=7bc466c1-15cd-4098-bba6-fcce9d3a62ce

Loom Recoding Link: Example 2(Declarative):
https://www.loom.com/share/f1e5ad355eb44158800905d5a6ac9927?sid=95fd9a36-2e79-48be-bcc8-aa60a4dff2c1

Loom Recoding Link: Learning Outcomes:
https://www.loom.com/share/97ef6fb9866347358fedc7ed01285bab?sid=d83bd8a3-5640-4e03-b56c-4e8421f24474

# Project Overview

In this project, I was presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. My task was to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 


# Presentation Talking Points

Example #: 1

## Imperative Approach 
1. **Step-by-Step Explanation:** 
   Preheating the Grill: The code starts by initializing variables ‘grillTemperature’ and ‘steakTemperature’ to track the temperature of the 
                          grill and the steak, respectively.
   Cooking the Steak: The code enters a while loop to cook the steak until it reaches the desired doneness (desiredDoneness). Inside the 
                      loop, it grills the steak, measures its internal temperature, adjusts the grill temperature and cooking time based on 
                      factors like steakWeight and desiredDoneness, and updates steakTemperature. The loop continues until the steak's 
                      temperature matches or exceeds the desired doneness.
   Serving the Steak: After cooking, the code checks if the steak is ready to serve based on its temperature. If the steak is done, it 
                      returns 'Steak is ready to serve!' Otherwise, it returns 'Steak needs more cooking.'


2. **Emphasis on How:** 
   Loop and Conditions: The while loop is used to iterate over the cooking process until the steak reaches the desired doneness. Inside the 
                        loop, conditions are checked to determine whether the steak needs more cooking or is ready to serve.
   Mutable Variables: Mutable variables like grillTemperature and steakTemperature are used to track the state and progress of the cooking 
                      process. These variables are updated throughout the execution of the function to reflect changes in grill temperature 
                      and steak temperature, indicating the imperative nature of the code.



Example #: 2

## Declarative Approach 
1. **High-Level Process Description:**
   Abstracted Cooking Process: The code defines the cooking process in a structured array called `cookingProcess`. Each element of this 
                               array represents a step in the cooking process, described by properties such as `action`, `temperature`, or 
                               `seasoning`. 
   Emphasis on What, Not How: By abstracting the cooking process into a series of discrete steps, the code emphasizes what actions need to 
                              happen rather than how they should be executed. This separation of concerns improves readability and 
                              maintainability by clearly defining the desired outcome without getting bogged down in implementation details.


2. **Use of Data Structures:** 
   Structured Representation: The use of a structured array of objects (`cookingProcess`) organizes the cooking process into a clear and 
                              easily understandable format. Each object within the array encapsulates a specific step of the process, with 
                              properties defining the action to be taken (e.g., preheat grill, season steak).
   Abstraction Layers: By encapsulating each step within an object, the code abstracts away the details of each action, promoting modularity 
                       and reusability. This allows for easy modification or extension of the cooking process without directly modifying the 
                       code logic. Additionally, the code promotes a separation of concerns by clearly defining the cooking process separate 
                       from its execution.


# Learning Outcome 
Analyzing code examples in different paradigms has provided valuable insights into the various approaches to problem-solving and programming. Here are some reflections on what I've learned:


Understanding Paradigm Differences: Imperative programming focuses on explicitly detailing the steps to accomplish a task, while declarative programming emphasizes describing the desired outcome without specifying the exact steps.

Emphasis on Clarity and Readability: Comparing the two approaches underscored the importance of clarity and readability in code. Declarative code tends to be more concise and expressive, making it easier to understand the overall logic and intent of the program. 

Modularity and Reusability: Declarative programming often promotes modularity and reusability by abstracting away implementation details and encapsulating functionality into reusable components.

Flexibility vs. Control: Imperative programming provides developers with fine-grained control over the execution flow and state manipulation, which can be beneficial in scenarios where precise control is necessary


