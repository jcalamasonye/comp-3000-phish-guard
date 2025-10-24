# comp-3000-phish-guard
A web-based phishing simulation and training platform to educate people about phishing by showing them what a phishing attack looks like in a safe and ethical manner. 
It works by sending controlled, simulated phishing emails to users such as employees in a company, or test participants. When a user clicks a link in that fake phishing email, instead of being harmed, they are redirected to a learning page that explains:
1.	Why the email was suspicious. 
2.	What signs they missed or link they missed such as a fake URL, strange sender address or typo errors.
3.	How to avoid real phishing attacks henceforth. 
  Instead of users getting punished for clicking the link, the app turns the mistake into a learning experience. 
## How it works (step-by-step flow)
As an Admin such as IT managers, teachers, or researchers can register on the app, they can upload a list of users email addresses or manually invite users, the admin then create a phishing email template such as (password reset, new job offer, payment issue alert), the app then sends this email using SendGrid API to users, the admin dashboard will show performance such as:
1.	Who opened the email
2.	Who clicked the fake link
3.	Who attempted the quiz after clicking the link 
As a user such as employee or trainee, they receive a realistic looking phishing email but completely safe, if the user clicks on the link they land on a phish guard training platform instead of landing on a malicious page, The training page explains the phishing attempt and includes a short interactive quiz teaching the user how to identify phishing in the future. Their quiz performance and progress are stored so the admin can track improvement over time.

 ##  Legal, Ethical, Social and Professional Considerations for Phish Guard
 ### 1.	Legal Consideration
Data protection and privacy: The system only accepts personal email data, which means users must give consent before being included. This would be done through a sign-up form, where users agree to receiving simulated phishing messages for training. The email form would clearly state that the emails are for awareness and training purposes only, no data breach will be caused, and data are being used for educational purposes. when a user signs up, there would be a message that says " By continuing or registering, you agree to receive simulated phishing emails from Phish Guard for educational purposes. These emails are safe and will take you to a learning module designed to improve your awareness of phishing threats. 
 ### 2.	Ethical Consideration
Part of the ethical consideration includes transparency; the system should make it straight that the core aim is to educate users not to punish or trick them, that means raising awareness and concern not to exploit trust 
 ### 3.	Social Consideration
social awareness which is helping people/users recognise phishing attempts or emails thereby improving better cybersecurity culture. Social consideration or responsibility means to change human behaviour and promote safer online practices. 
 ### 4.	Professional Consideration 
professionalism come across as the main value, which involves creating an app that raises awareness without breaking legal or ethical laws. which also involves good coding practices to prevent vulnerabilities since the app handles user’s data and email communication

