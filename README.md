# Hellō Next.js Starter

This is a starter application for the Hellō Next.js SDK [@hellocoop/nextjs](https://www.npmjs.com/package/@hellocoop/nextjs)

See a deployed version  at [https://hello-nextjs-starter.vercel.appss](https://hello-nextjs-starter.vercel.app)

To run locally, you will need:

- [nodejs 18+](https://nodejs.org/en/download)
- [git](https://github.com/git-guides/install-githttps://github.com/git-guides/install-git)
- A [GitHub](https://github.com) account

## 1\. Fork this repository to your GitHub account

<https://github.com/hellocoop/hello-nextjs-starter/fork>

## 2\. Clone your fork to your local machine

```
git clone https://github.com/<YOUR_ACCUONT>/hello-nextjs-starter
```

## 3\. Install, setup, commit, push and run!

```
cd hello-nextjs-start          # change to project directory
npm install                    # intall the node modules
npm run quickstart             # launch the Hellō Quickstart web app to register your app
git add *                      # add in the package-lock.json that was generated
git commit -a -m"quickstart"   # commit the environment variables for your app
git push origin                # push the changes up to your repo for future deployment
npm run dev                    # start the local dev environment
```

Open <http://localhost:3000> (assuming port 3000 was free)

### 4\. Deploy to Vercel and open your deployment

You will need:

- a [Vercel](https://vercel.com) account linked to your GitHub account
- Vercel CLI that is logged into your Vercel account 

```
# commands to install and login
npm install -g vercel
vercel login
```

These commands will build and deploy your repo to Vercel and then load the deployed site:

```
DEPLOYMENT=$(vercel --yes)     # deploy to Vercel with defaults
npx open-cli $DEPLOYMENT       # open deployment in browser
```

No otther configuration needed at Vercel!

The first time you login to your deployed app, you will be prompted to add the Redirect URI to your app at the [Hello Developer Console](https://console.hello.coop/). For development deployments, add to your Development Redirect URIs, for production or deployments you want others to access, add to your Production Redirect URIs.

---

## Learn More

- [Hellō Next.js SDK](https://www.npmjs.com/package/@hellocoop/nextjs)
- [Hellō Quickstart for Next.js](https://www.npmjs.com/package/@hellocoop/quickstart-nextjs)
- [Hellō Documentation](https://www.hello.dev/documentation)