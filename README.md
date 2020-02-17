# Challenges with Docker replication package

## Description

User study to assess the challenges and practices used when working with Docker technologies, namely Docker and Docker Compose. [A preliminary run](#preliminary-research) of the survey was conducted with students. Running this study with a wider audience of professionals will allow to study how the results may generalize to experienced software developers.

## Methodology

This study makes use of an online questionnaire as a data collection method, to make the most effective use of the time of participants and researchers. The [questionnaire](challenges_with_docker_technologies_questionnaire.pdf) is available in this repository and can be distributed using an online _survey administration system_, such as _Google Forms_. 

## Future Research

This questionnaire will be used in the context of the [on-site research track](https://www.agilealliance.org/xp2020/call-for-submissions/call-for-onsite-research/) of the XP 2020 conference. 

To disseminate it, we will use the support of the conference organizers and of the _on-site research_ track in particular. The form will remain open during the entire time of the conference (June 8-12, 2020) and until one week after the conference.

The raw results will be published in this repository and reported in peer-reviewed publications.

## Preliminary Research

An early version of the questionnaire was conducted with informatics students at [FEUP](https://www.fe.up.pt/) and rendered a total of 68 responses. The questionnaire that was used and the data that was collected is also [available in this repository](preliminary_research/).

### Procedure

The data collection was executed in 2 stages:

1. Initially performed physically in 6 classes with an average of 26 students, taking approximately 1 hour in total. For each class the following procedure was performed:
   * The link to access the form online was written on the classroom's whiteboard.
   * The researchers briefly explained the context, goal, motivation and how the students could access the form.
   * The researchers oversaw the filling procedure until completion, and aided the participants with any doubts about how the questions were posed.
2. After the classes, the questionnaire was distributed through e-mail to the same target audience, to allow answers to be received from students that were not physically in the classroom during the first stage. The form was closed after a period of 1 week.

### Findings

In this run of the study we were able to take the following tentative conclusions:

* 45% of participants agreed that a lot of time is spent on most `Dockerfile` development stages.
* The most time consuming tasks were:
    * Trying to understand if the resulting container is working as intended (50%).
    * Trying to understand why the resulting container is not working as intended (54%).
    * Rebuilding the image and re-running the container to confirm that it is working as intended (54%).
* Low usage of ancillary tools when working with `Dockerfile`s (10%).
* Low usage of ancillary tools when working with Docker Compose (4.4%).
* The most common strategy to debug and correct a malfunctioning configuration is "trial-and-error" followed by searching online for a possible solution.
* Slightly more participants feel they spend too much time when reading a `docker-compose.yml` file (54.4%) rather than editing one (47%).
* Out of the 4 main artifacts of Docker Compose (services and their properties, service dependencies, volumes and networks) the most time consuming tasks were:
  * Configuring services and their properties when configuring a `docker-compose.yml` (30.9%).
  * Understanding networks and their connection with services when reading a `docker-compose.yml` (36.8%).
