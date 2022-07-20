Install gatsby cli `npm install -g gatsby-cli`

# Startup with the default template

1. run in terminal: `npx gatsby new gatsby-starter-default https://github.com/gatsbyjs/gatsby-starter-default`
2. move into folder `cd gatsby-starter-default`
3. start development `gatsby develop` - [see more](https://www.gatsbyjs.com/docs/reference/gatsby-cli/#develop)
4. cleanup static content with `gatsby clean` - [see more](https://www.gatsbyjs.com/docs/reference/gatsby-cli/#clean)

# Startup from scratch

1. run in terminal `gatsby new`
2. follow the wizard

# Startup from github repo 

1. run in terminal `gatbsy new somefolder https://github.com/someproject/something.git`
2. navigate in somefolder
3. add the upstream repo `git remote add upstream https://github-url-here`
4. fetch the upstream repo `git fetch upstream`

# Build the production version

1. build with `gatsby build`
2. serve the site with `gatsby serve`