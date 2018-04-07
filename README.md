# PMS_restful
A management system (oo design + restful)

1)	Display all projectors’ name
@GET http://localhost:8080/projector_management_system_war_exploded/resources/pm/projectors
2)	Reserve a projector
@POST http://localhost:8080/projector_management_system_war_exploded/resources/pm/reservation
3)	Get a reservation’s detail by inputting a reservation id.
@GET http://localhost:8080/projector_management_system_war_exploded/resources/pm/reservation/1-0
4)	Delete a reservation by id
@DELETE http://localhost:8080/projector_management_system_war_exploded/resources/pm/reservation/1-0
5)	Show all the reservations
@GET http://localhost:8080/projector_management_system_war_exploded/resources/pm/reservation
6)	Show a projector’s empty time
@GET http://localhost:8080/projector_management_system_war_exploded/resources/pm/projectors/2/


Tools: Postman + Grassfish server
Lib: JAX-RS, Junit
java version 1.8.0_111
java EE version java EE 8
ide: Intellij
