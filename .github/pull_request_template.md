#### [Title of the Jira Ticket](<[https://](https://desolint.atlassian.net/jira/projects)>)

[Description of the PR - Might be simpler/shorter version of Jira description or totally new description] - (Example below)

The shipping service provider is charging extra on order fulfillment based on actual weight. This PR is one part in the implementation of module to allow automatic recovery of the extra charges from the customer. Here this is a CSV file importing module to get the actual charges, and send it to the comparison module in the backend.

#### commits description

1. Create CSV upload modal [commit code](https://github.com/desolintdev/guidelines/pull/1/commits/edbb9d234d63280f82aa978bd3e53ec111dcfad0)
2. Send CSV data to the server [edbb9d2](https://github.com/desolintdev/guidelines/pull/1/commits/edbb9d234d63280f82aa978bd3e53ec111dcfad0)

##### Packages Changes

Name: Installed `react-csv-reader` to read CSV files in the frontend
Effect: +20KB to the bundle size

##### Checklist

- [ ] I have put the Jira ticket number and title in the PR title
- [ ] I have included the Jira ticket link in the PR description
- [ ] I have included a proper description of the changes made in the PR
- [ ] I have included the commit descriptions and links in the PR description
- [ ] I have included the packages changes in the PR description (if applicable)
- [ ] I have tested the changes locally
- [ ] I have tested the changes for responsiveness (if applicable)
- [ ] I have answered responded to all the comments from the Code Rabbit AI
- [ ] I have addressed all the comments of SonarCloud
- [ ] I have addressed all the comments of Socket.dev
- [ ] I have answered responded to all the comments from the reviewers
- [ ] All the comments are resolved
