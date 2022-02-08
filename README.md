# Welcome to Sumo Logic Documentation

Share your knowledge with the community by contributing to Sumo Logic Documentation!

You can contribute by creating an issue or pull request (PR) on our GitHub repository. We welcome all types of contributions; from minor typo fixes to new topics.

Documentation staff members review issues and pull requests on a regular basis. We do our best to address all issues as soon as possible, but working through the backlog takes time. We appreciate your patience.

## Contributing Content

For details on contributions, see [CONTRIBUTING](https://github.com/SumoLogic/sumologic-documentation/blob/main/CONTRIBUTING.md) and the [GitHub Wiki](https://github.com/SumoLogic/sumologic-documentation/wiki).

We recommend forking the repo, creating all content changes in branches, and submitting pull requests. We will work with you to get this content reviewed, tested, and merged for publishing.

## Building Locally

The site includes translations into other languages.

1. Clone the repo using Git or tools like GitHub Desktop.
2. Run the install command: `yarn install`
3. To build locally and test links, use build: `yarn build`
4. To serve and review, use one of the following:

    * Use start, hot reloads as you make changes: `yarn start`

        Any issues with broken links and images are listed according to file. Locate and update those issues, then run again to verify.

    * Use npm serve to test and review multi-languages: `npm run serve`

        This build does not hot reload and requires a rebuild to test and review.

The site was created using [Docusaurus 2](https://docusaurus.io/) and supporting React, Rehype, and Remark plugins.

## Publishing Content

As Pull Requests (PR) are merged to the main branch by the Sumo Logic Doc team, the content builds and deploys to a staging site. This can be reviewed and tested thoroughly on a server, rather than a local.

When all content is tested and ready for live, a Sumo Logic Doc team member can tag a release to build and deploy to Production. This site is live to the world to search, use, and read to learn Sumo Logic.