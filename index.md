# Lab Report 4
## Part 1: Changing the start parameter and its uses to base

```
/start<enter>cebase<esc>n.n.:w<enter> 
```

* /start <enter> moves the cursor in front of "start" 

<img width="495" alt="Screen Shot 2022-12-02 at 8 50 09 PM" src="https://user-images.githubusercontent.com/98442414/205424162-02039e2e-3de3-4fea-b386-992f0e57dbdf.png">

* cebase <esc> Changes to insert mode, deletes the word "start" and types "base", then exits insert mode 

<img width="451" alt="Screen Shot 2022-12-02 at 8 51 53 PM" src="https://user-images.githubusercontent.com/98442414/205424241-0d4bec45-1986-4944-862c-d9aaaeeb2776.png">

* n. searches the last search command and repeats the last insert command

<img width="460" alt="Screen Shot 2022-12-02 at 8 53 51 PM" src="https://user-images.githubusercontent.com/98442414/205424302-c2732548-5f61-4e17-87fc-17bcccfa5f18.png">

* n. again, searches for "start" and replaces it to "base" 

<img width="458" alt="Screen Shot 2022-12-02 at 8 56 14 PM" src="https://user-images.githubusercontent.com/98442414/205424468-985b7af4-9485-4c19-a86f-e65957bb540e.png">

* :w <enter> saves the changes done above

<img width="480" alt="Screen Shot 2022-12-02 at 8 56 52 PM" src="https://user-images.githubusercontent.com/98442414/205424492-7369243b-95bc-4819-86b9-a6c33a7c5cfb.png">

---
## Part 2: Questions
***Report how long it took you to make the edit in seconds in both styles, and any difficulties or details that came up in doing so.**

Making the changes and then using scp took 55 seconds whereas using vim on the server took 30 seconds. This is because you do not need to copy over the changes done. 

***Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?**

I prefer using vim because it is much faster and copying over files after editing them can be very tedious and annoying at times

***What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)**

Personally, I would prefer to use vim but if projects or assignments are more complex, I would use my local computer as it is easier for me to change a large amount of texts and it is more visually easy for me. I am also more comfortable on my local computer so if it is something that would take hours, I would use local rather than vim. 
