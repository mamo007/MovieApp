# MovieApp

## DESCRIPTION
 MovieApp is kinda a netflix-clone but with many more interesting features made using ASP.NET MVC CORE / Code-First / Lazy load.
 The project is mainly made for ITI (Final project). <3

## FEATURES
  - Friendly Theme.
  - Braintree gateway is included for payment system.
  - Every account can make 5 profiles max (You can change the limit).
  - Customized video play.
  - Customized authentication & authorization using Identity.
  - Full control on subscriptions and payments also payment logs are included.
  - Two factor authentication.
  - Availability to control your profiles (Manage Profiles).
  - Availability to add trailers.
  - Availability to rate movies/series.
  - Availability to check watch history and rates for every profile made for the account.
  - Availability to renew your subscription if it ended.
  - Availability to add custom subscriptions from admin panel.
  - Availability to search for movies/series using its name or actor or generie.
  - Wish list is included.
  - Admin dashboard is included.
  - Track monthly revenues from admin panel.
  - Full control on users/roles/subscriptions/payments/movies/series/actors/genries from admin panel (Customized CRUD operations).
  - Saving last watching time on a movie/series.
  
## TECHNOLOGIES
  - ASP.NET MVC CORE
  - Entity Framework Core.
  - JSON
  - HTML5
  - CSS3
  - JS
  - Bootstrap

## OTHER LIBRARIES
  - Jquery
  - Datatables
  - Chart
  - Fontawesome
  - Braintree gateway
  - SendGrid
  - NToastNotify

## USAGE
  - The project is code-first and you need to add some packages first:
  1. Braintree: Used for the payment gateway to work and then change the data written in appsettings to your account data.
  2. Json.net: Used to serialize some data in the project to json.
  3. EntityFrameworkCore: Used for the code-first.
  4. EntityFrameworkCore.Proxies: Used for the lazy-loading.
  5. NToastNotify: Used for crud operations notifications in admin panel (Not required).
  6. SendGrid: Used for sending emails (Like email confirmation). You need to change the data written in appsettings to your account data. 
  
  - After installing the packages, update your database then add your Roles/Subscriptions/Countries in the database and you good to go.
## PREVIEW
  [![MovieApp](https://lh3.googleusercontent.com/fife/AKsag4M1uUUdiJJ2ecPv2pZbKT5OztlwCnRcBplGXacoovpBuXraJUblm1DcxGgmrUsPyf-PzfFCUu-PbwH175VloJd_6-WZpzL6POqAcRA1XNWJ4kQ-cFDjK-oEj5i9980vy_LWT3weHzONC046GEjb-vH-q5gFf6KgkOzXNJAkM7u_DpvcRPeZaxFMG0O-GQgocLY7WvO9uxg4PEc_ZICKHxYuVG_9Ayo4MgkCmF0TeKDhN0CHfVZp6dE8CyUyaJI8ze3btNPExv7P7Enz4zJDFoU5NwGr9u5hOIgwRNDdLxfxJHCr5Og0nQFQLUDlMG5urr5zKSyIhooXRaNVKPfOGnam8E_87_Bzojk1xodBk_Z1zxH00ifYVUckWKjuZLKcuoFuX-sJlCM4NGM4j6thPKqNv4oT7GyA8umPcfWlBqCHnPtUfXFX8r1CXvslTj38GLI77zvNbD5XWItd2zmsCjYzEyX0jv54cSE-ujLVzGI0dcydlX4d5AtmVdX5wtKBd0m9F5glDJIcG746WJQk16tCFJMZYewwY2HZsJxhZywh4eleNS_2ctBrJUHt_8ZpKA0yaHRIXdBhVm67v8WPSxES7dzrdPlbfvRSvHCHnLVBFSuW0fuMlOBh3GSVB9Ql66zpb4aJ2Y3wSFlPR7jvtgcOuVZu-JLo14ecs2GCoAAjtN7q4ahMYJBuN01QOzQtb6tbxChAaNpke7ibX0rnrdKfNqeAxUIuXSy8BbvBKjBmAEBaP8KbCxw6_maKDr9GQK-LEcFbjTnnm5uV-12n3Qi5SfOHNY_dTQz-gq4Y6t_Rxsz1XoYgSggCdzy-iec7-xOCfxNtfGYr-eozR4Jaj9Oq9Zy2T2hqmvWFrpujZtovto6o1qBqVLSxIZnp1Sr2wfT1N6ow6PERUNZT_caSgsgah-EAb7B7_6lvvb2IjMIxiUlmNVBdhHFrU1Gr-0lpnWEcITM1nZLJV_-PxAhrispnCtaAg3i1nCftFtOXaY0y-jLSuxVEuOe0cHBUEofkjFZ5TYzbgMl5C7l_PmlY8rJwzsRZ7oSyZ_qRHzq5o1qiJDPWQECv_jccwM31Ggw1AdtAZU6uTSQfkiPGfF4_BI-JVmPiZ4hGMm4CEG4elonNOupwT7FUjuP11OvOhQvunUbFCKxPYbz7fhYZuoZLFb1UWbc6D6u8ky9GmEZrSbhNkU0JAcI4JY_Le-ME-UVrz-zIffg_fb9oFz0N9KhIv9ILSq2txWCA-105kYj86H_sAH8DbOAUrh3L4-Hyal3B8HKtNGnea-JBpYAFG_mSzucwlNsGGneQdBUyijukJAKopd9WZjOqM9YuPg7hjjhrfZb2OClle89o-XJsDarV1obUinVjSu0OdqC6lOriPliYu5sDyU0Y1Eejvgfi3R5Sw7dQAba4HQ3Y6wwg2POKlXmVIwYlvRubf2iY8B2aNyOmEq123F3p_IfM_rWhy9scUaYcSLRxDE2FR7F3ukHSWBjs2Sm3L1UmhGw8gyCdR_FFWDR0tTjewSbjmRAU0iovjD18qRMa3OwWWpIBSoDBwIGJs2RjroSktGlngjELPCR_XDMCm33cFfztTw=w1920-h893)](https://drive.google.com/file/d/1NKLajrb7A8-cKuMU6N71ByI0SYwFs0Dc/view "MovieApp")

## ABOUT
  **Mohamed Hamdi**  
  Email: **mohamed2007969@gmail.com**  
  LinkedIn: [**mamo007**](https://www.linkedin.com/in/mamo007/)  
