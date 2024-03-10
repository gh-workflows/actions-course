# Slides

[GitHub Actions Fundamentals](https://github.com/Atmosera-actions-prep/actions-course/blob/main/slides/en-v2-github-actions-fundamentals.pdf)

# GitHub Actions Quick Links

## Workflow Syntax
### 👇🔗 Click the dropdown menu below for Workflow Syntax links 🔗 👇

<details>

### Basic Syntax

[GitHub Actions workflow syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions/) 

### Webhook Events

[Workflow syntax for scheduled events](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#onschedule/) 

[Scheduled events](https://docs.github.com/en/actions/reference/events-that-trigger-workflows#schedule/) 

### Scheduled Events

[Workflow syntax for events](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#on/)

[Events that trigger workflows](https://docs.github.com/en/actions/reference/events-that-trigger-workflows#webhook-events/) 

[Webhook event payloads](https://docs.github.com/en/developers/webhooks-and-events/webhooks/webhook-events-and-payloads/)

### Manual Events

[Manual events](https://docs.github.com/en/actions/reference/events-that-trigger-workflows#manual-events/)

[Workflow_dispatch API](https://docs.github.com/en/rest/reference/actions#create-a-workflow-dispatch-event/)

[Create a repository dispatch event](https://docs.github.com/en/rest/reference/repos#create-a-repository-dispatch-event/)

[GitHub CLI - trigger a workflow_dispatch event](https://cli.github.com/manual/gh_workflow_run/) 

### Runners

[Workflow syntax for runners](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idruns-on)

[Using GitHub-hosted runners](https://docs.github.com/en/actions/using-github-hosted-runners)

[Using self-hosted runners](https://docs.github.com/en/actions/hosting-your-own-runners)

### GitHub Hosted Runners

[About GitHub-hosted runners](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners) 

[Customizing GitHub-hosted runners](https://docs.github.com/en/actions/using-github-hosted-runners/customizing-github-hosted-runners) 

[List of pre-installed software on GitHub-hosted runners](https://github.com/actions/virtual-environments)

[Billing for GitHub Actions](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions)

[Usage limits for GitHub-hosted runners](https://docs.github.com/en/actions/reference/usage-limits-billing-and-administration#usage-limits) 

### Self Hosted Runners

[About self-hosted runners](https://docs.github.com/en/actions/hosting-your-own-runners/about-self-hosted-runners)

[Self-hosted runners usage limits](https://docs.github.com/en/actions/reference/usage-limits-billing-and-administration#usage-limits)

[Adding self-hosted runners](https://docs.github.com/en/actions/hosting-your-own-runners/adding-self-hosted-runners)

[Using a proxy with self-hosted runners](https://docs.github.com/en/actions/hosting-your-own-runners/using-a-proxy-server-with-self-hosted-runners) 

### Actions

[Workflow syntax for steps](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idsteps)

[Essential features of GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/essential-features-of-github-actions) 

### Marketplace

[GitHub Marketplace](https://github.com/marketplace?type=actions)

[Publishing Actions to the GitHub Marketplace](https://docs.github.com/en/actions/creating-actions/publishing-actions-in-github-marketplace) 

### Starter Workflows

[Repository containing the starter workflows](https://github.com/actions/starter-workflows)

[Setting up CI using templates](https://docs.github.com/en/actions/guides/setting-up-continuous-integration-using-workflow-templates)

### Advanced Syntax

[Example permissions syntax](https://github.blog/changelog/2021-04-20-github-actions-control-permissions-for-github_token/)

[Workflow syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)

[Service Containers](https://docs.github.com/en/actions/using-containerized-services/about-service-containers)

### Function Expressions

[Functions](https://docs.github.com/en/actions/reference/context-and-expression-syntax-for-github-actions#format)
  
</details>

## Environments and Secrets
### 👇🔗 Click the dropdown menu below for Environments and Secrets links 🔗 👇

<details>

[Environment docs](https://docs.github.com/en/actions/reference/environments)

[Workflow syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idenvironment)

[Deployment API](https://developer.github.com/v3/repos/deployments/)

### GitHub Secret Store

[Secrets](https://docs.github.com/en/actions/reference/encrypted-secrets)

### Types of Secrets

[Encrypted secrets](https://docs.github.com/en/actions/reference/encrypted-secrets) 

[Environment secrets](https://docs.github.com/en/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-an-environment)

[Repository secrets](https://docs.github.com/en/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository)

[Organization secrets](https://docs.github.com/en/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-an-organization)

### Using Secrets in Workflows

[GITHUB_TOKEN](https://docs.github.com/en/actions/reference/authentication-in-a-workflow) 

[GITHUB_TOKEN permissions](https://docs.github.com/en/actions/reference/authentication-in-a-workflow#permissions-for-the-github_token)

### Permissions for GITHUB_TOKEN

[Source blog](https://github.blog/changelog/2021-04-20-github-actions-control-permissions-for-github_token/)
  
</details>

## Managing Workflows & Actions
### 👇🔗 Click the dropdown menu below for Managing Workflows & Actions links 🔗 👇

<details>

### Actions Policies

[Report Actions usage](https://github.com/ActionsDesk/report-action-usage)

[Enforcing Actions policies in your enterprise](https://docs.github.com/en/github/setting-up-and-managing-your-enterprise/setting-policies-for-organizations-in-your-enterprise-account/enforcing-github-actions-policies-in-your-enterprise-account)

[Enforcing Actions policies in your organizations](https://docs.github.com/en/organizations/managing-organization-settings/disabling-or-limiting-github-actions-for-your-organization) 

[Enforcing Actions policies in your repositories](https://docs.github.com/en/github/administering-a-repository/managing-repository-settings/disabling-or-limiting-github-actions-for-a-repository)

### Sharing Workflows in an organization

[Sharing workflows with your organization](https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization/)

[Sharing workflows with GitHub Apps](https://github.github.io/practices-knowledge-base/3-actions/auth-as-github-app/)

[Actions best practices](https://github.github.io/practices-knowledge-base/3-actions/actions-best-practices/)

[Reusable workflows](https://docs.github.com/en/enterprise-cloud@latest/actions/learn-github-actions/reusing-workflows/)

### Sharing Actions

[Sharing actions and workflows](https://docs.github.com/en/enterprise-cloud@latest/actions/creating-actions/sharing-actions-and-workflows-with-your-enterprise/)

### Caching

[Cache support for GHES](https://github.com/github/roadmap/issues/273/) 

[GitHub Docs - Caching dependencies to speed up workflows](https://docs.github.com/en/actions/guides/caching-dependencies-to-speed-up-workflows/) 

[GitHub Action - actions/cache](https://github.com/actions/cache/)

### Best Practices on Actions in an Organization

[Actions best practices:](https://github.github.io/practices-knowledge-base/3-actions/actions-best-practices/)

  </details>

## Building Actions
### 👇🔗 Click the dropdown menu below for Building Actions links 🔗 👇

<details>

### Writing Your Own Actions

[Creating Actions](https://docs.github.com/en/actions/creating-actions/)

[Metadata syntax](https://docs.github.com/en/actions/creating-actions/metadata-syntax-for-github-actions/)

[JavaScript Actions](https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action/)

[Typescript Actions](https://github.com/ActionsDesk/ps-typescript-template/)

[Docker Action](https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action/)

[Composite action](https://docs.github.com/en/actions/creating-actions/creating-a-composite-run-steps-action/) 

### Using the GitHub API

[REST libraries](https://docs.github.com/en/rest/overview/libraries/) 

[GraphQL API](https://docs.github.com/en/graphql/) 

[JS Octokit documentation](https://octokit.github.io/rest.js/v18/) 

### Best Practices

[SOLID design principles](https://en.wikipedia.org/wiki/SOLID/)

[Semantic versioning https://semver.org/)

[Publish to the Marketplace](https://docs.github.com/en/actions/creating-actions/publishing-actions-in-github-marketplace/) 

[Actions templates](https://github.com/actions/) 

[Actions toolkit](https://github.com/actions/toolkit/) 

[TypeScript template from ActionsDesk](https://github.com/ActionsDesk/ps-typescript-template/)

[GitHub script](https://github.com/actions/github-script/)

[CLI pattern](https://github.com/ActionsDesk/admin-support-issueops-actions/)

</details>

## CI/CD
### 👇🔗 Click the dropdown menu below for CI/CD links 🔗 👇

<details>

### Basic CI workflow

[Learning lab](https://lab.github.com/githubtraining/github-actions:-continuous-integration/)

[Go CI workflow](https://github.com/gh-mentor/actions-go/blob/main/.github/workflows/CI.yml/)

### Linting

[Super-linter](https://github.com/github/super-linter/)

[Go lint](https://github.com/gh-mentor/actions-go/blob/main/samples/workflow-syntax/golangci-lint.yml/)

## Runners

[GitHub-hosted runners docs](https://docs.github.com/en/actions/using-github-hosted-runners/) 

[GitHub-hosted runner virtual environments](https://github.com/actions/virtual-environments/) 

[Self-hosted runner docs](https://docs.github.com/en/actions/hosting-your-own-runners/) 

### Adding Self-Hosted Runners

[Adding self-hosted runners](https://docs.github.com/en/enterprise-cloud@latest/actions/hosting-your-own-runners/adding-self-hosted-runners/)

### Runner Groups

[Managing access to self-hosted runners using groups](https://docs.github.com/en/enterprise-cloud@latest/actions/hosting-your-own-runners/managing-access-to-self-hosted-runners-using-groups/)

### Security with Self-Hosted Runners

[Security guides](https://docs.github.com/en/enterprise-cloud@latest/actions/security-guides/)

### Scaling Runners

[Roadmap for customizable runners on GHEC](https://github.com/github/roadmap/issues/161/)

## Additional Samples and Documentations

[Actions Changelog](https://github.blog/changelog/label/actions/)

[Azure](https://github.com/Azure/actions/)

[Actions workflow samples](https://github.com/Azure/actions-workflow-samples/)
  
[Publishing packages](https://docs.github.com/en/actions/publishing-packages)

</details>


## Action links
### 👇🔗 Click the dropdown menu below for more action links 🔗 👇

<details>

[Marketplace](https://github.com/marketplace)
  
[Checkout](https://github.com/actions/checkout)

[Super Linter](https://github.com/github/super-linter)
  
[CodeQL](https://github.com/github/codeql)

(CRON Helper)[https://cron.help/]

</details>























