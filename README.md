# Azure template for jobs nested build

An application can use nested jobs to manage subsets of processes. Nested jobs also enable an application that uses jobs to host other applications that also use jobs.

Nested jobs have a parent-child relationship in which each child job contains a subset of the processes in its parent job. If a process that is already in a job is added to another job, the jobs are nested by default if the system can form a valid job hierarchy and neither job sets UI limits.

## Properties

**template string.** Required as first property.
Reference to a template for this deployment.

**parameters template parameters.**
Parameters used in a deployment template.

