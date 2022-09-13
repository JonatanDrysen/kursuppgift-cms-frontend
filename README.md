# Frontend for headless wordpress

## Getting started

### Locally
1. Clone this repository
2. Run `npm install` to install node modules
3. Create `.env.local` file
4. Paste `REACT_APP_API_URL=https://public-api.wordpress.com/rest/v1.1/sites/YOUR WORDPRESS SITE.wordpress.com` into `.env.local`
5. Change "YOUR WORDPRESS SITE" to your own site name

   After saving documents and running `npm start` you should have a working React App populated with your own posts from your WordPress blog

### Live deploy
1. Log in or create a Vercel account (Github is recommended to access your existing repositories)
2. Click the `Add New` button and choose your repository
3. Import said repository
4. In the `Configure Project` dropdown in the next step, create an environment variable called `REACT_APP_API_URL` with your unique site URL as in `.env.local`
5. Click `Deploy`

   After a quick build and deploy process, your site should now be live! Further pushes to your repository will automatically update the site.
