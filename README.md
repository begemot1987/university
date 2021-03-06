# UNIVERSITY

## Project description

Spring Boot REST service that simulates the work of a university and provides a schedule of lectures for a specific student on a specific day. The schedule is
the list of lectures that the student has on a particular day.

### Following diagram shows relations between models
![cinema_tape](https://i.ibb.co/Wgtf3Z0/models-diagram.jpg)

## Used technologies
* PostgreSQL
* Hibernate
* Spring Boot
* Maven
* Docker
* Mockito

## Schedule endpoint

There are already some test data initialized on application startup.<br>
To get schedule for student by particular day you can use following endpoint<br>
`/students/{id}?day={day}`


