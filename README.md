
# ElectroStore

ElectroStore is a full fledged electronics store which facilitates all end-to-end processes from user authentication to payment intergration. 

- It's Front End is built on NextJS and TailwindCSS along with TypeScript and the Back End is managed by SanityCMS and authentication is supported by GoogleOAuth and NextAuth.
 

## Features

- User Authentication:
    - User Authentication is facilitated by GoogleOAuth and NextAuth package.
    - In terms of operations, authentication is not playing a key role.
    - After completion of payment process, if user is logged in, one's name will be displayed otherwise it will be replaced by guest.
- Payment Processing Using Stripe:
    - The entire payment system is facilitated by Stripe which makes payment not only secure but also very fast.
- Server-Side Rendering:
    - All the images of the products, user account image, product categories are rendered server side which improves the site response time thereby enhancing user experience.
- User and Content Database:
    - Once the user sign-in, his/her account will be automatically generated in the Sanity Database. This is achieved by implementing sanity adapter and along with that the entire content of the site is also managed by SanityCMS.



## Tech Stack

**Client:** NextJS, Redux, TailwindCSS, TypeScript

**Server:** SanityCMS, Stripe, NextAuth, TypeScript


## Tweaking the Project

Here are the steps you can follow if you want to make changes to this project

Clone the github repository:
```
git clone https://github.com/Devrajsinh-Jhala/ElectroStore.git
``` 

Install the dependencies:
```
yarn install
```
Start the server:
```
yarn run dev
```

Note: The authentication and payments require secret keys to work which due to obvious reasons I cannot share publicly, If you are geniunly interested in any sort of changes, please raise and issue and give details. If seems geniune, I will share the credentials.

## Lessons Learned

- Working extensively with TypeScript which resulted in thorough understanding of types, common problems while installing dependencies etc.
- Implementing Redux and TypeScript together and developing better understanding of Redux and Redux Toolkit.
- Setting up payments in stripe and authentication with Google Cloud and NextAuth.
- Working more with TailwindCSS and media queries along with learning more about animations.
## Author

- [@Devrajsinh Jhala](https://github.com/Devrajsinh-Jhala)



