# Link Shortener - C4C Coding Challenge
- The function of this application is to shorten links that are inputted by the user
on a local server. The links are then saved and show up on the website and can be 
clicked on to redirect the user to the original website.

## How to Use This:
- Type a link into the box with the sample URL inside
- Press Generate
- You will see a link in the form of the shortened URL underneath
- Click on this newly shortened link to be redirected to your website


# C4C Epilogue - Ananya Rath

- To improve the quality of this code base, I would: (least to greatest importance)

1. Break down the components of the backend and frontend further
   into different files and classes and utilize helper functions
   as well as make it clearer what the different classes and files  
   are doing in terms of their purpose. I would also add comments and labels
   for a clearer understanding of how the different components interact with one  
   another and the types of services they use (Postman, Chakra, etc.). I feel that this
   would improve the organization of the code base more and make it easier to add features
   and make improvements to the design and function.


2. Perform a validation of the URL inputs to check whether they are actually valid
   URLs that lead to a website before performing the shortening function on them. I would also
   create a popup or dialogue of some sort that informs the user if the link is broken or invalid.

3. For security purposes, validating the safety of a valid URL (this safety validation would be performed after #2)
   that a user is trying to shorten and access through the use of Cloud services. I would implement a Cloud Service like
   Google Cloud's Web Risk before providing the user with a link.

