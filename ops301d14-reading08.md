# Ops Reading 08
## RADIUS Authentication

This is very important because you need to know these and how a companies network work.

#### Computer Network - AAA (Authentication, Authorization, Accounting)

**1. Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story.**

*If you ever wanted to change your wifi password at home you would have to do it remotely. Doing that is not always safe because someone who is a hacker can intercept your connection so that why there are the Three A's in network computing*
- Authentication - Authentication is what identifies you. This is where the username and password come to play. When someone wants to hop on the wifi, we use authentication to identify and choose if we want to grant them access

- Authorization - Think of this as the authority to do something on the network. Let say you playing a basketball game and the coach draws up a play for your teammate to take the game winning shot. Instead you take it. You were NOT authorize to take that shot.

- Accounting - Accounting is like the data tracker. It logs how long you have been on the system. The admin can set up to where it can log anything wants.

**2. What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?**
- If the ACS fails to authenticate a user during the AAA implementation then the admin should mention using the local database of the device as a backup.

**3. What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.**
- ![Alt text](image.png)

#### RADIUS Concepts

**1. What are the benefits of using RADIUS for authentication and authorization?**
- The RADIUS is like a secret bodyguard that can guard you from any attack that benefits the authentication and authorization because not everyone is on the same level in the network or has the same permission to do stuff on it. 

**2. What is RADIUS and what does it stand for?**
- RADIUS (Remote Authentication Dial-in User Service) 
It is a centralize authenticator for users. Today RADIUS is very commonly used and even tho the name has dialed in, we commonly used our ethernet port to use RADIUS


**3. Research: What encryption algorithms does RADIUS use?**
- TLS 
- Secret Handshake
- Message Digest Algorithm(MD5) and Secure Hash Algorithm (SHA)

## Things I want to know more about
I wish i knew more about how many companies use RADIUS


# Resources:
 https://www.google.com/search?sca_esv=588417346&rlz=1C1CHBD_enUS952US952&sxsrf=AM9HkKkcnqnAzoWdIWYJrlAtt2iRT9aJMw:1701880286615&q=What+is+the+role+of+the+NAS+in+the+AAA+implementation+using+an+ACS+server%3F+Use+a+diagram&tbm=isch&source=lnms&sa=X&ved=2ahUKEwif_ruPnvuCAxUbHTQIHfraBtYQ0pQJegQIDBAB&biw=1013&bih=921&dpr=1#imgrc=iTkpyhF5S7T7PM

 https://chat.openai.com/share/199dab80-fb74-4aed-813c-3e3ab2241c01

 https://youtu.be/-8P2fqO2nnA?feature=shared