<link href="style.css" rel="stylesheet">

{% include navbar.html %}

<p style="margin: 60px 0px 0px 0px;" />
# Technical Information

NinJo was developed by a consortium of National Meteorological Services with assistance of experienced IT companies.

The involvement of the different partners in the development of the system ensures both its broad applicability and its continued maintenance. It also ensures that recommendations and requirements of users, configurators, administrators and IT specialists are considered in the development process. As a result, NinJo already encompasses a wide range of the functionalities expected from a workstation system used in operational meteorology. Furthermore, customer-specific functionalities can easily be incorporated into the system.

Distributed offices with central servers in the headquarters are common practice for the Consortium Members, who also share the need for a comprehensive workstation capable of

- visualizing meteorological and oceanographic data from various sources and in various formats,
- producing standard and customized products, and
- editing the data and products.

General Architecture

NinJo is a client-server system built using an extremely modular and scalable design. On the client’s side there is the interactive NinJo application, which is installed locally on the user's computer. Batch applications can be implemented on the server as well as on the client’s side. All other data is managed by the relevant server entities and administered centrally. The import/export modules for the different data types as well as decoding of the incoming data also run at the server level.

Optional integration of the GloBUS decoding system allows further optimisation to be achieved. GloBUS was developed on behalf of the German Meteorological Service (DWD) for processing incoming data.

NinJo is open for future developments. The system can easily be extended by further layers and applications according to user-specific requirements.

NinJo is programmed entirely in JAVA. As a result, the workstation system can be installed on different operating systems (e.g. Unix, Linux and Microsoft Windows). This avoids the necessity of porting the source code onto a specific operating system.

In principle, NinJo is able to run on any computer, be it a laptop or a supercomputer. However, adequate hardware for the expected volume of data is necessary. Both the client and server platforms need to have sufficient main memory and processor speed. In addition, a sufficiently fast network connection is required.

NinJo relies on some external systems, e.g. for file handling, decoding of meteorological reports and bulletins, document management and scheduling.

On the NinJo Server, different import and data servers are responsible for the importing of the data and making it accessible to the Clients. Furthermore, the NinJo server comprises 

- the Event Service for the automatic warning (notifications to the Clients),
- Export Services, e.g. for warnings or products,
- Infrastructure Services, and
- the Production Services, e.g. for the NinJo Batch System, Application Servers or Web Services.

On the client side, there is the NinJo Workstation for

- Visualisation,
- Monitoring,
- Production of warnings,
- Interactive editing and
- Configuration of NinJo Batch products.
