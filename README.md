
<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's CV starter
</h1>

Create your resume in a few minutes with this totally responsive starter using React. Show off your skills, work experiences and activities in github.

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```sh
    # create a new Gatsby site using the default starter
    npx gatsby new my-default-starter https://github.com/41rdg6br/gatsby-starter-cv
    ```

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```sh
    cd my-default-starter/
    npm run develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    \_Note: You'll also see a second link: `http://localhost:8000/___graphql`. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql).\_

    Open the `my-default-starter` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

1. **Generate production build**

  That command will generate a production build on _public_ folder
  ```sh
    npm run build
  ```

## Configuration

Update the configuration file with your data. The configuration file is in ```data/siteConfig.js```

:warning: NOTE: Please change googleAnalyticsId to your ID.  See https://analytics.google.com for details.

> **Skills** is a set of your personal skills and their respective levels ranging from > 0 to 100.
> **jobs** is a set of your work experiences

```js
module.exports = {
  siteTitle: 'Rodrigo',
  siteDescription: `Create your online curriculum in just a few minutes with this starter`,
  authorName: 'Rodrigo Nogueira',
  twitterUsername: '_rodrigonogueira',
  githubUsername: 'rodrigonogueira',
  authorAvatar: '/images/avatar.jpg',
  authorDescription: `Developer, passionate about what I do. Always interested in how the sites were made, I started to study HTML by hobby. <br />
  In 2012 I started working as a support technician and I approached the developers.
  In 2015, I started to study C # and started to contribute with the team giving maintenance in an application in C # and .NET. <br />
  I currently work as a frontend developer and mainly work with <strong>Javascript, NodeJS e React.</strong>`,
  skills: [
    {
      name: 'HTML',
      level: 70
    },
    {
      name: 'CSS',
      level: 60
    },
    {
      name: 'Javascript',
      level: 50
    },
    {
      name: 'NodeJs',
      level: 40
    },
    {
      name: 'React',
      level: 60
    },### 
    {
      name: 'Git',
      level: 70
    }
  ],
  jobs: [
    {
      company: "Lendico",
      begin: {
        month: 'apr',
        year: '2018'
      },
      duration: null,
      occupation: "Frontend developer",
      description: "I integrate the Frontend team responsible for developing and maintaining the online lending platform."
  
    }, {
      company: "Anapro",
      begin: {
        month: 'dec',
        year: '2016'
      },
      duration: '1 yr e 5 mos',
      occupation: "Fullstack developer",
      description: "Development and maintenance, corrective and preventive, of web applications for the real estate market."
    }, {
      company: "Anapro",
      begin: {
        month: 'set',
        year: '2012'
      },
      duration: '4 yrs e 3 mos',
      occupation: "Support Technician",
      description: "Responsible for the implementation and parameterization of the system, training and customer support. Acting also in person in real estate launches guaranteeing the success and good use of the tool."
  
    },
    /* ... */
  ],
  social: {
    twitter: "https://twitter.com/_rodrigonogueira",
    linkedin: "https://www.linkedin.com/in/rodrigo-nogueira",
    github: "https://github.com/41rdg6br",
    email: "41rdg6br@gmail.com"
  },
  siteUrl: 'https://rodrigonogueira.github.io/gatsby-starter-cv',
  pathPrefix: '/gatsby-starter-cv', // Note: it must *not* have a trailing slash.
  siteCover: '/images/cover.jpeg',
  googleAnalyticsId: 'UA-000000000-1',
  background_color: '#ffffff',
  theme_color: '#25303B',
  display: 'minimal-ui',
  icon: 'src/assets/gatsby-icon.png',
  headerLinks: [
    {
      label: 'Rodrigo Nogueira',
      url: '/',
    }
  ]
}

```
