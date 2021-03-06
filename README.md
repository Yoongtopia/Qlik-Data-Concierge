# Qlik Data Concierge (QDC)

####**Qlik Data Concierge in action**

 [![Qlik Data Concierge in action](https://raw.githubusercontent.com/QlikPreSalesDACH/Qlik-Data-Qoncierge/master/IMAGES/sneakpeek.JPG)](https://www.youtube.com/watch?v=MsRgWh_7Xs4)

####**What is it?**

A self-service solution for non-technical BEx users based on Qlik Sense, the Qlik SAP BEx Connector, a web wizard to select the BEx query and its parameters and the Sense API (on-demand app generation) to generate a new app filled with cached BEx data.


----------


####**What it is not?**

It is not a built-in function of Qlik Sense. It is rather an example solution, a self-service app providing access to SAP BEx queries, and perhaps, in the future, to other SAP structures, Big Data systems or high-performance databases. It will most likely need customizations or adaptations to run on a productive customer environment. We work closely with Qlik Consulting Services to offer this as a Solution Services package - the customize outcome of which could be supported by Qlik Services according to individual agreements with the customer. Please see also below, section “Implementation”.


----------


####**What's the motivation?**

We see SAP BW on HANA as the preferred, long-term IT strategy in most of the large enterprise accounts in Germany, Switzerland and many other sales regions. BEx queries are designed by SAP for self-service data consumption by the business user as they generally provide rather small, aggregated data sets based on the user's individual selection of dimension, measures and variables. 

As the old SAP BEx Analyzer Excel plugin is phased out, newer, more modern, web based ad-hoc visualization and reporting tools will fill the gap with their promises of rich & advanced analytical features combined with direct (live) connection to BEx queries. With the shift towards BW systems boosted by HANA, this notion of "live" consumption of BEx queries by the self-service user becomes a key requirement for any new (strategic) BI project in the enterprise.

The Qlik Data Concierge (QDC) has been developed to fulfill Enterprise IT demands, providing self-service live access to SAP BEx queries for business users.


----------


####**How does it work?**

The QDC is a 2 component solution. The **first component** of the solution is a Qlik Sense document (.qvf) which helps you to collect the metadata of your necessary BEx Query's out of your SAP BW System(s).

 - Define your SAP BW system(s)
 - Define a set of possible BEx Query's
 - Delivers selection-dialogue-information to Frontend (Mashup)

After that this qvf file delivers all necessary metadata-information to the Frontend within the green, white and grey logic from Qlik Solutions.

The **second component** is a Webmashup. The Mashup enables the user to select the BEx Query containing the necessary filter-logic.

 - Web-based UI 
 - Selection-logic wizard
 - Self-Service Load-Script-Generation
 - Ad-hoc App-Generation process

----------


####**Where do I find a documentation?**

The documentation for Qlik Data Concierge will be maintained through the internal WIKI section of this repository.

- [Go to documentation](https://github.com/QlikPreSalesDACH/Qlik-Data-Qoncierge/wiki)


----------



####**Contribution**

 **I like to build my own Data-Acquisition-Wizard based on a different data source e.g. Hadoop etc.**
 
*You are welcome! We are highly interested to gain your contribution. Please contact Qlik PreSales Organization.*
 


----------


####**Implementation**
 **I like to implement the solution in a production environment. Where can I get assistance from?**
 
 *Please contact Qlik Consulting Services to gain help in your project.*
 


----------

 
Process-Overview of QDC:

![Process-overview](https://raw.githubusercontent.com/QlikPreSalesDACH/Qlik-Data-Concierge/master/IMAGES/Process%20Overview.png)


----------
Welcome to QDC:

![Welcomescreen](https://raw.githubusercontent.com/QlikPreSalesDACH/Qlik-Data-Qoncierge/master/IMAGES/INTRO.JPG)


----------
How the data-acquisition-wizard looks like:

![Mashupe](https://raw.githubusercontent.com/QlikPreSalesDACH/Qlik-Data-Qoncierge/master/IMAGES/MASHUP.JPG)


----------
