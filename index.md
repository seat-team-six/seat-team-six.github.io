# Imagine Cup 2017
## Friday 26 May 2017
During our first year at UCL we were introduced to the Haskell programming language, which was taught via lectures and lab sessions where teaching assistants helped us with programming assignments given by our professor. We could rely on the TAs to answer specific questions if we were struggling,  however they weren’t able to spend a lot of time going through the code and checking if it was correct. The only way we had to verify that our solutions were correct was to compare our code with the model answers once they were released the following week, or ask teaching assistants, who just had a limited time. We thought that this system could be improved to both make students’ lives easier when learning programming and also increase professors’ productivity. 
 
Our vision as students was to be able to read, code, and test the solution inside a real IDE which professional programmers use later in their career. Likewise, there should be an easy way for teachers to write assignments. And wouldn’t it also be great to give real-time feedback to the professor, so she/he sees where students are struggling and being able to adjust the curriculum?
At this point, we realized we will need two things:
An IDE running on the major OS and which is easy to extend
A cloud infrastructure for easy data collection
The solution to the first problem was to create a VS Code extension that would allow students to read and code their assignments solutions without having to leave the IDE. Moreover, it would enable them to check if their code was correct at the click of a button. 
For the latter, we decided to build the complete infrastructure with Azure. Specifically the straightforward deployment of Docker containers hosted on Dockerhub via Web Apps made our life so much easier providing a great continuous deployment and integration experience.
 
 
 
 
The only issue I see with the current writing is that first you state that the problem is not being able to know if you answers are correct. But then you give more stress in the part of the solution that consists on reading and coding in the same IDE.
