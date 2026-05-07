  # Family Budget Tracker — Privacy Policy                                                                      
                                                                                                                
  **Last updated:** Thursday, 7 May 2026 (GMT+3)                                                                              
  **Effective date:** Thursday, 7 May 2026 (GMT+3)                                                                            
                                                                                                                
  This privacy policy explains how **aliaksei.shalamitski** ("we",                                   
  "us") handles personal data when you use the **Family Budget Tracker**                                        
  mobile application ("the app") and the related backend services.                                              
                                                                                                                
  ## 1. Who we are                                                                                              
                                                                                                                
  - **Data controller:** aliaksei.shalamitski         
  - **Contact:** up.dreams.dev@gmail.com                                                     
   
  ## 2. What data we collect                                                                                    
                                                                  
  We only collect data that is necessary to operate the app.                                                    
                                                                  
  | Category                | Examples                                                                 | Source 
                           |
  | ----------------------- | ------------------------------------------------------------------------ |        
  ------------------------------- |                                                                             
  | **Profile**             | Display name, email address                                              | Google
  or Apple OAuth, or entered by you |                                                                           
  | **User identifiers**    | Internal user UUID, OAuth provider ID, hashed device identifier (guest)  |
  Generated on sign-up            |                                                                             
  | **Authentication**      | Refresh token hash, sign-in timestamps                                   |
  Generated on each login         |                                                                             
  | **Personal finance data** | Budget categories, transactions, amounts, dates, goals, recurring entries |
  Entered by you in the app       |                                                                             
  | **Family membership**   | Family ID, role (admin/member), join/leave timestamps                    | Created
   when you join or create a family |                                                                           
  | **Operational logs**    | API request logs, error logs (no payload contents)                        |
  Server-side, automatic           |                                                                            
                                                                  
  We **do not** collect: precise or approximate location, contacts, photos,                                     
  audio, microphone or camera input, calendar entries, browsing history,
  advertising identifiers, payment-card data, health or biometric data.                                         
                                                                                                                
  ## 3. Why we collect it                                                                                       
                                                                                                                
  | Purpose                              | Data used                                          |                 
  | ------------------------------------ | -------------------------------------------------- |
  | Provide the app's core features      | Profile, finance data, family membership           |                 
  | Authenticate you and keep you signed in | Identifiers, authentication tokens                 |              
  | Identify guest accounts across sessions | Hashed device identifier                           |              
  | Prevent abuse and rate-limit sign-ups | Hashed device identifier, IP address, request logs |                
  | Diagnose errors and keep the service running | Operational logs                                |            
                                                                                                                
  We do **not** use your data for advertising, profiling, or to train                                           
  machine-learning models.                                                                                      
                                                                                                                
  ## 4. Legal basis for processing (EEA/UK users)                                                               
   
  - **Performance of a contract** (GDPR Art. 6(1)(b)) — processing required                                     
    to deliver the service you requested.                         
  - **Legitimate interests** (Art. 6(1)(f)) — for security, fraud prevention,                                   
    and operating the service. You can object at any time by contacting us.                                     
  - **Consent** (Art. 6(1)(a)) — only where required, e.g. before processing                                    
    any optional data we may add later.                                                                         
                                                                                                                
  ## 5. Who we share data with                                                                                  
                                                                                                                
  We do **not** sell, rent, or trade your personal data.                                                        
   
  We share data only with:                                                                                      
                                                                  
  - **Identity providers** (Google, Apple) — to verify your sign-in. They                                       
    receive only what is needed to complete authentication.
  - **Hosting and infrastructure providers** acting as our processors —                                         
    <name your hosting provider, e.g. "DigitalOcean", "AWS", "Hetzner">,                                        
    located in <region, e.g. "the EU">. They store data on our behalf                                           
    under contract and have no independent right to use it.                                                     
  - **Authorities**, when legally compelled (e.g. court order).                                                 
                                                                                                                
  ## 6. International transfers                                                                                 
                                                                                                                
  Your data is stored on servers located in <region>. If data is transferred                                    
  outside your country, we rely on appropriate safeguards such as Standard
  Contractual Clauses approved by the European Commission.                                                      
                                                                                                                
  ## 7. How long we keep it
                                                                                                                
  | Data                              | Retention period                          |                             
  | --------------------------------- | ----------------------------------------- |
  | Account profile and finance data  | Until you delete your account             |                             
  | Authentication tokens             | Until they expire or you sign out         |                             
  | Operational logs                  | Up to 90 days, then deleted               |
  | Encrypted database backups        | Up to 30 days, then rotated and destroyed |                             
  | Anonymized aggregate metrics      | Indefinitely (no personal data)           |                             
                                                                                                                
  When you delete your account, your personal data is permanently removed                                       
  from the live database immediately. Residual copies in encrypted backups                                      
  are destroyed within 30 days.                                                                                 
                                                                  
  ## 8. Your rights                                                                                             
                                                                  
  Depending on your location, you may have the right to:                                                        
   
  - **Access** the personal data we hold about you                                                              
  - **Correct** inaccurate data                                   
  - **Delete** your account and associated data (see [Account & Data
    Deletion](./#delete-account))                                                                               
  - **Restrict** or **object to** certain processing                                                            
  - **Receive a copy** of your data in a portable format                                                        
  - **Withdraw consent** where processing is based on consent                                                   
  - **Lodge a complaint** with your local data protection authority
                                                                                                                
  To exercise these rights, email **up.dreams.dev@gmail.com**. We respond                                         
  within 30 days.                                                                                               
                                                                                                                
  ## 9. Security                                                  

  - All traffic between the app and our servers is encrypted with TLS (HTTPS).                                  
  - Authentication tokens are stored in encrypted device storage
    (`expo-secure-store` on Android/iOS).                                                                       
  - Refresh tokens are stored only as one-way hashes on the server.                                             
  - Device identifiers used for guest accounts are hashed with a server-side                                    
    secret before being saved to the database.                                                                  
  - Access to production systems is limited to authorized personnel.                                            
                                                                                                                
  No system is perfectly secure. If we ever discover a personal-data breach                                     
  that affects you, we will notify you and the relevant authorities as                                          
  required by law.                                                                                              
                                                                  
  ## 10. Children                                                                                               
                                                                  
  The app is intended for users aged **18 and over**. We do not knowingly                                       
  collect personal data from anyone under 18. If you believe a minor has
  provided us data, contact us at **up.dreams.dev@gmail.com** and we will                                         
  delete it.                                                                                                    
                                                                                                                
  ## 11. Changes to this policy                                                                                 
                                                                  
  We may update this policy from time to time. The "Last updated" date at
  the top of this page reflects the most recent change. Material changes
  will be communicated in-app or by email.                                                                      
   
  ## 12. Contact                                                                                                
                                                                  
  ## 10. Children

  The app is intended for users aged **18 and over**. We do not knowingly
  collect personal data from anyone under 18. If you believe a minor has
  provided us data, contact us at **up.dreams.dev@gmail.com** and we will
  delete it.

  ## 11. Changes to this policy

  We may update this policy from time to time. The "Last updated" date at
  the top of this page reflects the most recent change. Material changes
  will be communicated in-app or by email.

  ## 12. Contact

  Questions, requests, or complaints:

  - **Email:** up.dreams.dev@gmail.com
  - **App / Developer:** Family Budget Tracker — aliaksei.shalamitski
