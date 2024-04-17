# Scenario
We'd like to keep track of the number of our security vulnerabilites across our repositories so that we are able to track the health of our services.

We host repositories in Github that has built-in Dependabot tooling that reports on known security vulnerabilities

# Your task

For https://github.com/pkiddie/fluffy-succotash, write a tool that can return the number of detected vulnerabilities 
- The response you construct should be in a format that is suitable for dashboarding/graphing over a long term period
- Provide a way to run across a set of repositories
- Provide a way to run the tool on a schedule
