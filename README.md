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
