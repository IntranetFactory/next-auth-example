
## About 

This is an example of how to use [NextAuth.js](https://next-auth.js.org) library to add adenin DigitalAssistant localhost authentication to a [Next.js](https://nextjs.org) application.


`dev.cmd`  disables ssl validation (so that node will accept dev certificate for https://localhost:44367) and runs `next dev`


## Host Tenant

A new OAuth client needs to be registered:   
Client Name: spanext    
Title: nextjs spa    
Client Id: tt94cztgbzknvmgfdyfiqk9ah4ej79hq    
Return Url: http://localhost:3000/api/auth/callback/adenin    
