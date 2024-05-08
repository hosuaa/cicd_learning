# cicd_learning

## CI/CD

**Continuous Integration (CI)**: It's a development practice where developers integrate code into a shared repository frequently, preferably several times a day. Each integration triggers automated builds and tests, ensuring early detection of integration errors.

**Continuous Deployment (CD)**: It's an extension of continuous integration where code changes are automatically deployed to production environments after passing through a series of automated tests, without human intervention.

![image](images/cicdDiagram.png)

## Webhooks

A webhook is a way to automatically trigger actions in one system when something happens in another system

For example, say you purchase something off Amazon. You then get an email for order confirmation, then later on an email saying your delivery has been dispatched. There is not a person manually sending these emails; it's automatic and is triggered from the initial purchase. So one action triggers a notification that triggers the next notification and so on...

This is implemented using (webhook) api calls

## CI/CD pipeline

**Why**: CI/CD pipelines automate the process of building, testing, and deploying code, which improves development efficiency, reduces errors, and accelerates time-to-market.

**When**: CI/CD pipelines are beneficial for any project where there's frequent code changes and a need for quick and reliable deployment.

**Where**: CI/CD pipelines are commonly used in software development projects such as web applications and mobile apps