Download Link : https://programming.engineering/product/project1-e-r-design-and-relational-schema-design/


# Project1.-E-R-design-and-Relational-Schema-design
Project1. E-R design and Relational Schema design
Package Delivery System

“You are a DBA in this company”

Goal : The goal of this project is to provide a realistic experience in the conceptual design, logical design and maintenance of a small relational database.

 

Application Description :

The application is a package delivery company (e.g. FedEx, UPS, DHL, CJ Logistics). The company needs to keep track of packages shipped and their customers. To find out more about this application, think about any experiences you may have had shipping packages and receiving packages, and browse shippers’ web sites.

In our hypothetical company, the manager assigned to solicit database design proposals is not very computer literate and is unable to provide a very detailed specification.

Here are a few points to consider :

 

            There are different kinds of service possibly based upon the type of package(flat envelope, small box, larger boxes), the weight of the package, and the timeliness of delivery (overnight, second day, or longer).

            Some customers have a contract with the shipper and bill their shipments to an account number. They are billed monthly. Other customers are infrequent customers and pay with a credit card. Certain shipments are prepaid, as is might be the case of someone is returning something that was purchased by phone or Internet (e.g. returning clothes that don’t fit, or returning malfunctioning electronics, returning damaged book ).

            For the most part, the shipping company does not care what is being shipped. However, there are cases where it matters. Some examples include

– hazardous materials

– international shipments, for which a customs declaration stating the
contents and their value is needed

            The company needs to track packages from the time the customer drops it off (or it is picked up by the company) until the time is is delivered and signed for. Take a look at the online tracking offered by various shipping companies to get an idea of how this service works. If you are having something shipped to you, you’ll find you can get every little detail of where the package is, where it has been, and to where it is currently headed. Beyond what the customer sees, the company itself needs to know on which truck or plane or warehouse the package is at any point in time.

            Tracking is not just an “in the present” issue. The company may want to look back in time and find out where the package was yesterday, for example. It may also want to look at data from the standpoint of a truck or warehouse.

            There are other aspects to the operation of the company besides package tracking such as the routing of trucks and planes, the assignment of staff to them, etc. For this project, we’ll consider only the package handling and billing aspects of the database.

Project Requirements :

    E-R Model

            Construct an E-R diagram representing the conceptual design of the database.
            Be sure to allow us to store information without unnecessary redundancy.
            At minimum you must include all the entity and relationship sets implied by this description. You may go beyond the minimum. Remember that the manager who defined the specifications is not computer literate so the specifications should not be viewed as necessarily being precise and complete.
            Be sure to identify primary keys, relationship cardinalities, foreign key and so far.

2. Relational Schema Diagram

            After creating an E-R model, reducing it into Schema diagram (discussed in Chapter 6.7)
            Create the schema diagram in ERwin Data Modeler we discussed in practice session.
            Be sure to allow us to store information without unnecessary redundancy.
            Be sure to identify primary keys, foreign keys, relationship cardinalities, relationship type, allowing nulls and so far.
            Every entities should have name and primary key(s).

3. Queries

The queries listed below are those that your client (the manager from
the package delivery company) wants turned in. They may provide
further hints about database design, so think about them at the outset of
the project.

            Assume truck 1721 is destroyed in a crash. Find all customers who had a package on the truck at the time of the crash. Find all recipients who had a package on that truck at the time of the crash. Find the last successful delivery by that truck prior to the crash.
            Find the customer who has shipped the most packages in the past year.
            Find the customer who has spent the most money on shipping in the past year.
            Find those packages that were not delivered within the promised time.
            Generate the bill for each customer for the past month. Consider creating several types of bills.
            – A simple bill: customer, address, and amount owed.
            – A bill listing charges by type of service.
            – An itemize billing listing each individual shipment and the charges for it.

Customers like their bills to be readable. While the client will accept a
relational table coming from Oracle as the bill, it would be “nice” to have
a good-looking bill.

What to turn in :

            E-R diagram (not hand drawn) made by any chosen tools
            (e.g. https://online.visual-paradigm.com/diagrams/features/erd-tool/
            or you can feel free to use any tools such as MS Powerpoints, keynotes etc.)
            Relational Scheme diagram ERwin file (.erwin)
            – student_id.erwin (submitted filename ) e.g. 120220422.erwin

– Be sure to same display options in practice session. ( IE notation, display relationship cardinality)

– Use the title in schema diagram and description if you needed.

            Report file (.pdf)

– [project1]student_id.pdf (submitted filename)
e.g. [project1]120220422.pdf

– Describe the detail explanation about your E-R model and Schema
diagram that you made.

– MAKE YOUR OWN DESCRIPTION on every entities and
relationships you made.

– Feel free to use any template you made.
Solution
