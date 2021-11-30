# GithubPowerQuery
Repository with Power Queries for Github Reporting

This repo contains queries that you can use in PowerBI and Excel Power Query for fetching report from GitHub. One of the big problems with Github is the lack of reporting for managing an Enterprise. This can be used in excel to pull data on users in an organisation, including email address.

The queries are a combination of GraphQL and apis

Replace myorganization with your organization.

Create two parameters called AccessToken and AccessUser.
Fill them with your account name and an AccessToken with the following permissions:

admin:org, public_repo, manage_billing:enterprise, read:discussion, read:enterprise, read:gpg_key, read:public_key, read:repo_hook, repo:invite, repo:status, repo_deployment, user

The main query references the GraphQL query, so make sure to rename that reference as well.
