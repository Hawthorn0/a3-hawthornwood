
---

## Les shopping list

https://a3-hawthornwood.onrender.com/

Basically my project allows people to log in and keep a shopping list personalized to their username. Its pretty simple but it gets the job done. The goal is to keep your shopping items in an easy place. Challanges I faced were... pretty much every step of the process. That being said I understand a lot more of mongodb and express and js so thats a win. I initially started making the authentication use a seperate collection for users which it'll refer to, then I realized its late at night the day this is due, so I pivoted to having each insertion of data have a field called userpass which stores the username and password. Then, when you log in it saves your username and password, and it only gets/modifies/deletes items with your username and password. Specifically, it stores it like this "user##@password". I used picnic https://picnicss.com/documentation because it looked clean and fit the clean vibe of a shopping list. I used modifications in the form of a different css sheet that goes after it, which sets some nice colors, centers things, and just makes it all fit better. 

## Technical Achievements
- **Tech Achievement 1**: I used OAuth authentication via the GitHub strategy

### Design/Evaluation Achievements
- **Design Achievement 1**: I followed the following tips from the W3C Web Accessibility Initiative...
