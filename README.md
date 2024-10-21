# CS-305

## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that creates individualized financial plans for customers. They are looking for a way to make their existing application more secure.

## What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I mostly enjoyed exploring the dependency reports that I created for my code. There was a lot there that I hadn't known about previously. Secure coding ensures the protection of your, and your client's, files. The wellbeing of a company depends on secure coding because having data leaked can affect the reputation of any institution regardless of the content. Keeping the company's data secure is the best way to keep them reputable.

## What about the process of working through the vulnerability assessment did you find challenging or helpful?
The dependency check tool was the most helpful. It made checked for vulnerabilities infinitely faster and easier.

## How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
Through testing most of the vulnerabilities were caused by using old libraries so by updating the libraries currently in use in the code more secure software is created. Using penetration testing in the future will better assess the and additional vulnerabilities within the code.

## How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
Something that I've always done was block checking. When I finish a block of code, I run it to see if any errors arise. If nothing breaks, I move on to the next block. After refactoring the code, I would rerun the dependency check to ensure no new vulnerabilities popped up.

## What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Stack overflow and Google were my best friends this term. There was one assignment that I couldn't figure out and reached out to my professor, and he was able to point me in the right direction. Side note: Make sure the Pom.xml file has all correct versions!

## Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this assignment might you want to showcase to a future employer?
I would demonstrate my understanding of false positives and how to suppress them until updates can be made.
