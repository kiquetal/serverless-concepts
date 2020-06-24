##### Severless

   	Concepts

	1- No management of server hosts or processes
	2- Self auto-scale and auto-provision based on load
	3- Cost based on precise usage
	4- Perfomance capabilities defined in terms other than host/size
	5- Implicit High Availability
	

	Function As A service FAAS
	Database As a Service BAAS
	Storage


##### Brief Overview of Function as Service (Faas)

	The old World: One machine->dependencies->applications-
	1- Setup of compute
	2- Reacting to scale
	3- Pay even if it's not in use.
	4- Configuration on hosts.
	

	Faas in nutshell

	No host config
	Pay for what's running
	Scale-up on demand
	Automatic spin down


	Undifferentiated Heavy lifting/remove obstacles

##### FaaS use cases

	Act on data change
	->Upload file on a S3-> trigger lambda
	->Listen to message queue
	
##### Backend as Services

	Managed database on the cloud
	Think about primary/secondary

#### What are microservices?

	Are independently deployable services that work together, modelled around a business domain
	Ships software more quickly.
	Data owned by service.

#### Problems with 'traditional' microservices.
	
	You must patch in every layer.

#### Baas as Microservices

	Database coupling problemas
	service-invoicing,service-payroll,service-insights------> same db. (can't change[resource protection]).
			

