
.. _service:

The following sections of Training profile provide detailed information on the elements.

Training
========

        
1. Basic
########

        
.. list-table:: EOSC Training Profile Elements of "Basic" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - title
     - The human readable name of the learning resource.
     - string
     - 1
     - Y
   * - resourceOrganisation
     - The name of the organisation that manages or delivers the resource, or that coordinates the Resource delivery in a federated scenario.
     - string
     - 1
     - Y
   * - resourceProviders
     - The name(s) of (all) the Provider(s) that manage or deliver the Resource in federated scenarios.
     - string
     - 1
     - N
   * - authors
     - The name of entity(ies) authoring the resource.
     - string
     - 1
     - Y
   * - url
     - The URL that resolves to the learning resource or to a "landing page" for the resource that contains important contextual information including the direct resolvable link to the resource, if applicable.
     - anyURI
     - 1
     - Y
   * - urlType
     - The designation of identifier scheme used for the resource URL. It represents the type of the URL of the resource, that is the used scheme (e.g., Web Address URL, DOI, ARK, etc.).
     - string
     - 1
     - N
   * - eoscRelatedServices
     - The name(s) of (all) the Provider(s) that manage or deliver the Resource in federated scenarios.
     - string
     - 1
     - N
2. Detailed and Access
########

        
.. list-table:: EOSC Training Profile Elements of "Detailed and Access" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - description
     - A brief synopsis about or description of the learning resource.
     - string
     - 1
     - N
   * - 
     - 
     - 
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
3. Learning
########

        
.. list-table:: EOSC Training Profile Elements of "Learning" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - scientificDomains
     - The branch of science, scientific discipline that is related to the Resource.
     - tns:serviceProviderDomain Vocabularies: :doc:`Domain <_vocabularies/SCIENTIFIC_DOMAIN>` / :doc:`Subdomain <_vocabularies/SCIENTIFIC_SUBDOMAIN>`.
     - 1
     - Y
   * - 
     - 
     -  :doc:`Vocabulary <_vocabularies/CATEGORY>`.
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
   * - 
     - 
     -  :doc:`Vocabulary <_vocabularies/TARGET_USER>`.
     - 1
     - Y
   * - 
     - 
     -  :doc:`Vocabulary <_vocabularies/ACCESS_TYPE>`.
     - 1
     - Y
   * - 
     - 
     -  :doc:`Vocabulary <_vocabularies/ACCESS_MODE>`.
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
4. Availability
########

        
.. list-table:: EOSC Training Profile Elements of "Availability" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - geographicalAvailabilities
     - Locations where the Resource is offered.
     - string
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
5. Classification
########

        
.. list-table:: EOSC Training Profile Elements of "Classification" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - 
     - 
     - 
     - 1
     - Y
6. Contact
########

        
.. list-table:: EOSC Training Profile Elements of "Contact" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - 
     - 
     - 
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
   * - 
     - 
     - 
     - 1
     - Y
