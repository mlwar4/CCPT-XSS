# Exploiting DOM-Based XSS 

![Pasted image 20240603233737](https://github.com/user-attachments/assets/1515a880-145f-4a89-9059-448aec49f7ab)


thats the page we are going to hack and i can see mathmagic and number 20 but up in the url we can see something 

a parameter called statement with value of 10+10 looks like this statement=10+10 

its like a mathmatical calculation

![Pasted image 20240603233906](https://github.com/user-attachments/assets/af034b88-ccae-4223-bd0d-3181debb98c5)


after making it statement=10+40 we got 50 so this is what basically dom is used to change the value dynamically the thing is when you preform the calculation your preforming it from your end  

![Pasted image 20240603234025](https://github.com/user-attachments/assets/70e667a9-4c34-4745-88c2-561eedbca728)


thats what would happen if someone else copied my link it only changes for us like roblox cheats 
javascript is only being exectuted on our browser anything found on html page can only change on our side so we can also

![Pasted image 20240603234151](https://github.com/user-attachments/assets/66915742-2d0e-476e-a8e0-be74bbfd8e76)


thats the source 

![Pasted image 20240603234202](https://github.com/user-attachments/assets/2281389f-516b-41c6-bb1e-9cf2dc7b8f82)


when ever you see document. what ever its dom , this 

if u see eval() just put the alert payload in it like this 

![Pasted image 20240603234410](https://github.com/user-attachments/assets/7f86837c-87ed-4e87-a19d-42d51a0c604c)
