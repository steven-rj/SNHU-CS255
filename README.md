## SNHU-CS255
a course project repo for SNHU's CS 255

## Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
 
For this class project, we were tasked with analysing the client requirements of, and designing the system of DriverPass, a web-based platform where customers could sign up for exam and on-the-road training to pass the DMV's driver tests. The proposed system would allow users to purchase training packages of varying on-road hours with an instructor. The owner specifically asked for the ability to print system reports of user cancellations or appointment modifications, and that system security and backups be handled by an external entity. 

 
## What did you do particularly well?
    
We defined the different user types very well. We first had a main User class, which comprises properties that everyone would need. Next we created Customer, Vendor, and Employee subclasses from this, each with their own individual characteristics and methods. Last, we derived the Admin class from Employee, again, with its own properties.

    
## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
    
The Use Case Diagram could use some revision. Cleaning it up and defining more system use cases could help better refine the proceeding Sequence and Class diagrams. 

    
## How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
    
The transcript of the interview between the DriverPass owner and the project manager provided invaluable insight of the requirements and expectations of the new system we were to develop. While the feasibility of client requirements naturally ought be address, at the end of the day, the product should mimic what is asked for as closely as possible. Else, (unless the client is very loose or flexible with their requirements) what is the point of delivering to the customer something very different from what they asked for?

    
## How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
    
