# social-media-automation-workflow
Automate social media notifications with Make.com! This workflow monitors Google Sheets for new posts and sends formatted Gmail alerts to your team. Ideal for small businesses and content creators, it saves time, prevents missed posts, and provides a simple, scalable, beginner-friendly automation solution.
# Social Media Automation Workflow

## 📌 Overview
This project automates social media post notifications using **Make.com**.  
Whenever a new post is added to Google Sheets, an automatic HTML email is sent via Gmail. It helps teams stay updated, saves time, and prevents missed posts.

---

## 👩‍💻 Author
**Bushra Ashraf**  
- MSc Mathematics  
- MA Special Education (Visual Impairment Category)  
- Current Job: Special Education Teacher (Visual Impairment)  
- Role: Project Creator  
- Email: bushraedu.ai@gmail.com  

---

## ⚙️ Workflow Components
- **Google Sheets:** Stores post data (Date, Platform, Content)  
- **Make.com:** Automation workflow  
- **Gmail:** Sends HTML email notifications  

---

## 🗂️ Google Sheet Format
| Date       | Platform | Content |
|------------|----------|---------|
| 2025-11-22 | Twitter  | Check out our new post! |

---

## 📧 Email Template (HTML)
```html
<p><strong>New Social Media Post Alert!</strong></p>
<p>Platform: <strong>{{Platform}}</strong></p>
<p>Date: <em>{{Date}}</em></p>
<p>Content:</p>
<p>{{Content}}</p>
<hr>
<p>✔ This post is ready for scheduling.</p>
