# DevOps Containers Excercise #

Imagine you’re part of a team that is starting a blogging application that would eventually run on the cloud (let’s assume it's AWS). The team has decided to use Wordpress to get a simple blog running as a start. Your team of developers wants you to help them monitor their application and the computers their application are running on. Since cloud is the target infrastructure, you decide to collect metrics with Prometheus and cAdvisor and to visualise with Grafana. The entire infrastructure is intended to be a container based system. In order to achieve the above, you would need to:

1. Create a Docker compose based Prometheus setup, so that it's repeatable and demonstrable on a development machine.
2. Deploy dockerized WordPress based blogging application.
3. Monitor the distributed resources and the blogging application using Prometheus and Grafana.
4. For bonus points: Demonstrate your knowledge and understanding by preparing an insightful dashboard of your choice; importing dashboards from Grafana sources is absolutely fine.

NOTE: To make things simple, you can use the official WordPress Docker image to run a web application and monitor it using Prometheus.

## Considerations ##

The solution to the exercise should show us that you are able to:
* use CI concepts in order to provision needed software for the deliverables to run
* use CI concepts to promote deliverable through environments
* use any CM tool of your choice to deploy the deliverable (could be as simple as Ansible playbooks, or Jenkins tasks that run some escalable shell script)


## Deliverables ##

* A Git repo with:
  * The Configuration Management Tool of Choice
  * Dockerfiles and Docker compose
  * Shell scripts
* Deploy the Prometheus stack.
* Finally start the blogging app as a Docker process.

## Requirements ##
Here are the specs that we would like you to use:

* Configuration Management tool of choice
* Docker 1.12+
* Prometheus
* cAdvisor
* Grafana
