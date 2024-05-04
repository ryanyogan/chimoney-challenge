## Description
This challenge is open to anyone who is interested in a Fullstack Developer role at Chimoney. Please, feel free to complete this challenge and invite @uchibeke to the Github PR to evaluate it. Feel to to have it in a public or private repo (invite @uchibeke as a Collaborator)

Welcome to the Chimoney Fullstack Developer Challenge! This challenge is designed to assess your skills and abilities across various aspects of fullstack development, including frontend and backend development, API integration, security, and understanding of payments and web3. You will have 7 days to complete the challenge (Ping @uchibeke on the day you decide to start the Challenge).

### Challenge Overview:

You are tasked with building a simple deployed web application that allows users to create and manage their accounts, send and receive payments, and view transaction history. The application should be built using React with Next.js (or similar frameworks) on the frontend and Node.js with Express on the backend. Firestore/Supabase (for simplicity or another DB of your choice) will be used as the database, and the application should be deployed using Vercel/Render/Heroku/AWS/GCP etc. It should be live and viewable and have CI/CD.

---

### Requirements:

- [ ] User Authentication: Implement user authentication using Firebase Authentication or similar. Users should be able to sign up, log in, and log out securely.

- [ ] Dashboard: Create a dashboard page where users can view their account balance, recent transactions, and perform actions such as sending and receiving payments. This could be a call to Chimoney to pull user transactions.

- [ ] Send Payment: Implement a feature that allows users to send payments to other users and non-users using Chimoney's API. Users should be able to specify the recipient's account ID (through a search), email or phone number and the amount to send.

- [ ] Receive Payment: Implement a feature that allows users to receive payments from other users. When a payment is received, it should be reflected in the user's account balance and transaction history. Consider allowing users receive Payments to their email or phone (powered by Chimoney) and cashing it into their Account in the Web App.

- [ ] Transaction History: Create a page where users can view their transaction history, including details such as transaction date, type (sent or received), amount, and recipient/sender information. This could be a call to Chimoney's API to pull user transactions and rendering this is a standard table using a table module of your choosing.

- [ ] Security: Ensure that sensitive user data such as passwords and payment information is stored securely and encrypted. Implement necessary security measures to prevent common vulnerabilities such as XSS and CSRF attacks.

- [ ] API Integration: Integrate Chimoney's API for sending and receiving payments. Refer to Chimoney's API documentation for details on endpoints and authentication.

- [ ] CI/CD: Set up continuous integration and deployment using a available tools. Automate the build and deployment process to ensure smooth and efficient deployment of updates.

- [ ] Ambition and Alignment: Demonstrate your ambition and alignment with Chimoney's values of excellence, speed, and impact by delivering a high-quality, well-designed application that meets the requirements and exceeds expectations.

### Evaluation Criteria:
Your submission will be evaluated based on the following criteria:

```
Attention to detail and adherence to requirements
Critical thinking and problem-solving skills
Ability to use React (Next.js or similar), Node.js, and Express (other backend tools) effectively
Implementation of Chimoney's API and integration with the application
Security measures implemented to protect user data
Understanding of payments and fintechs and their implications for the application
Implementation of CI/CD for automated deployment
Architecture, quality of code, including readability, maintainability, and documentation in the readme
Overall ambition and alignment with Chimoney's values
```

### Submission:
To submit your project, please mention @uchibeke in the GitHub repository containing your codebase. Include all required information in the PR along with any necessary instructions for running the application locally and the live lin. Additionally, include a brief summary of your approach and any challenges you encountered during the development process.

### Good luck, and we look forward to reviewing your submission!
