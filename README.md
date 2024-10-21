# CS-305

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that creates individualized financial plans for customers. They are looking for a way to make their existing application more secure.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I mostly enjoyed exploring the dependency reports that I created for my code. There was a lot there that I hadn't known about previously. Secure coding ensures the protection of your, and your client's, files. The wellbeing of a company depends on secure coding because having data leaked can affect the reputation of any institution regardless of the content. Keeping the company's data secure is the best way to keep them reputable.

## Which part of the vulnerability assessment was challenging or helpful to you?
The dependency check tool was the most helpful. It made checking for vulnerabilities infinitely faster and easier.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Through testing, most of the vulnerabilities were caused by outdated libraries so by updating the libraries currently in use in the code more secure software is created. Using penetration testing in the future will better assess the and additional vulnerabilities within the code.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Something that I've always done was block checking. When I finish a block of code, I run it to see if any errors arise. If nothing breaks, I move on to the next block. After refactoring the code, I would rerun the dependency check to ensure no new vulnerabilities popped up. 

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Stack overflow and Google were my best friends this term. There was one assignment that I couldn't figure out and reached out to my professor, and he was able to point me in the right direction. Side note: Make sure the Pom.xml file has all correct versions!

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would demonstrate my understanding of false positives and how to suppress them until updates can be made.
