<h1>warming up</h1>
<b>Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.</b>

My project would use javascript/typescript. For linting the answer is obvious, we would pick eslint. It works well with Visual Studio Code and is very flexible. Checked Google for some alternatives and found JSLint and JSHint. For testing I’d use Jest for the unit tests and Cypress for the End to end testing. Some other frameworks I’ve tried is Mocha and Chai. Google recommends Jasmine, Karma, Puppeteer. I’ve used Robot Framework and it’s also a very flexible testing framework, maybe not specially for JS but in general. For build tool I’d choose Webpack. Others I found were Grunt, Bower, Gulp, Parcel and npm. 

<b>What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!</b>

The CI choice is a hard one. They all have their own perks. I feel it depends on what the team is comfortable with. If the source code was hosted on GitHub I would pick Github Actions. Other CI alternatives there is Gitlab CI, Circle CI, TravisCI, TeamCity.

<b>Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?</b>

For a small team, I think cloud-based environment would be better. Not having to get the hardware to host your own Jenkins server and managing it is a big deal. Jenkins is better suited for bigger teams, where you can allocate personnel to manage it. Having the pipeline straight in Github would make the results visible for all the developers.
