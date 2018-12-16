# Builders_R_Us
Relational database for a fictional company that helps customers design a variety of custom home design projects.

Scenario description: 
Builder’s R Us (BRU) is a company that helps customers design a variety of custom home design
projects such as renovating a kitchen, painting the entire house, or installing a fence. The CEO
wants to you to create a database so that she can keep track of expenses, income, customer
information, employee performance, and inventory. She has already paid a consultant who has
provided an enhanced-entity relationship diagram that reflects her business needs. You should
enforce as many of the constraints outlined in the EER and the following textual description of
BRU’s business practices as the basis for your relational database design.
A project can take place either inside or outside of a customer’s home. If the project is inside, the
database should capture each room that will be affected by the project ( e.g. kitchen, living room,
bathroom ). If the scope of the project is outside then database should capture each of the outside
locations ( e.g. front yard, backyard, near the bbq ). The EER diagram includes generic term
“location” to capture either rooms or outside locations. Of course, a customer may want a project
that may require changes to both the inside and the outside of their home. Projects requiring both
inside and outside work would have multiple records within the database – one to capture the
overall project, one that captures all the work to be done inside, and a third project to capture all the
work outside. The partOf relationship which is connected to the PROJECT entity reflects this
requirement.
BRU serves two types of customers - commercial and residential. Commercial customers receive a
discount on all projects. BRU sends out a birthday card to their residential customers each year, so
they need to capture the customer’s birth date. The company can’t currently afford to include
advertising information in their database, but they plan to include that information at some point in
the future. In the meantime, she would like to keep track of the market sector for each residential
customer. In the past, employees have been less than diligent in entering the market sector, so she
would be very happy if the database helped to correct the missing data.
To ensure good service, BRU assigns one employee to be a customer’s primary contact. The primary
contact follows the project from conception through completion and may initiate new projects with
the customer. If an employee leaves the company, the company assigns their customers to a new
employee. Thus, at any given point in time, a customer has only one primary contact, but the
database will keep historical information so that the owners can keep track of who is generating the
most business. It happens infrequently, but an employee can be re-assigned to customer that they 
have previously worked with. Employees may also leave the company and then return at a later date.
In such cases the database should provide them with the same identifier.
