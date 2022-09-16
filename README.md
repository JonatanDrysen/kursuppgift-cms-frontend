# Frontend for headless wordpress

## Getting started

### Locally
1. Clone this repository
2. Run `npm install` to install node modules
3. Create `.env.local` file in root directory
4. Paste `REACT_APP_API_URL=https://public-api.wordpress.com/rest/v1.1/sites/YOUR_WORDPRESS_SITE.wordpress.com` into `.env.local`
5. edit "YOUR_WORDPRESS_SITE" to your own site name, i.e `https://public-api.wordpress.com/rest/v1.1/sites/jonatandrysenfullstack.wordpress.com`

   After saving documents and running `npm start` you should have a working React App populated with your own posts from your WordPress blog

### Live deploy
1. Log in or create a Vercel account on vercel.com (Github is recommended to access your existing repositories)
2. Click the `Add New` button and choose your repository
3. Import said repository
4. In the `Configure Project` dropdown in the next step, create an environment variable called `REACT_APP_API_URL` with your unique WordPress API URL as in `.env.local`
5. Click `Deploy`

   After a quick build and deploy process, your site should now be live! Further pushes to your repository will automatically update the site.


## Contact me
Admin: Jonatan Drysén
Email: mailto:jojodrysen@gmail.com
  
## Use my API
If you want to use my personal API, email me your WordPress.com username or connected email and i'll give you access to my site, if you ask nicely! If you don't already have a WordPress.com account, you will instead be directed to a sign up page, follow the instructions provided by WordPress first, and when your own account is created, you'll be able to access my site and create posts.
