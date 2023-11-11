
.. _service:

The following sections of Training profile provide detailed information on the elements.

Training
========

        
1. Basic
########

        
.. list-table:: EOSC Service Profile Elements of "Basic" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - id
     - A persistent identifier, a unique reference to the Resource in the context of the EOSC Portal.
     - string
     - 1
     - N
   * - name
     - Resource Full Name as assigned by the Provider.
     - string
     - 1
     - Y
   * - abbreviation
     - An abbreviation of the Resource Name as assigned by the Provider
     - string
     - 1
     - Y
   * - resourceOrganisation
     - The name (or abbreviation) of the organisation that manages or delivers the resource, or that coordinates resource delivery in a federated scenario.
     - string
     - 1
     - Y
   * - resourceProviders
     - The name(s) (or abbreviation(s)) of Provider(s) that manage or deliver the Resource in federated scenarios.
     - string
     - 1
     - N
   * - webpage
     - Webpage with information about the Resource usually hosted and maintained by the Provider.
     - anyURI
     - 1
     - Y
2. Detailed and Access
########

        
.. list-table:: EOSC Service Profile Elements of "Detailed and Access" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - description
     - A high-level description in fairly non-technical terms of a) what the Resource does, functionality it provides and Resources it enables to access, b) the benefit to a user/customer delivered by a Resource; benefits are usually related to alleviating pains (e.g., eliminate undesired outcomes, obstacles or risks) or producing gains (e.g. increased performance, social gains, positive emotions or cost saving), c) list of customers, communities, users, etc. using the Resource.
     - string
     - 1
     - Y
   * - tagline
     - Short catch-phrase for marketing and advertising purposes. It will be usually displayed close to the Resource name and should refer to the main value or purpose of the Resource.
     - string
     - 1
     - Y
   * - logo
     - Link to the logo/visual identity of the Resource. The logo will be visible at the Portal. If there is no specific logo for the Resource the logo of the Provider may be used.
     - anyURI
     - 1
     - Y
   * - multimedia
     - Link to video, slideshow, photos, screenshots with details of the Provider.
     - tns:multimediaPair
     - Multiple
     - N
   * - useCases
     - Link to use cases supported by this Resource.
     - tns:useCasesPair
     - 1
     - N
3. Learning
########

        
.. list-table:: EOSC Service Profile Elements of "Learning" block
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
   * - categories
     - A named group of Resources that offer access to the same type of Resources.
     - tns:serviceCategory :doc:`Vocabulary <_vocabularies/CATEGORY>`.
     - 1
     - Y
   * - category
     - 
     - tns:serviceCategory
     - Multiple
     - N
   * - targetUsers
     - Type of users/customers that commissions a Provider to deliver a Resource.
     - string :doc:`Vocabulary <_vocabularies/TARGET_USER>`.
     - 1
     - Y
   * - accessTypes
     - The way a user can access the service/resource (Remote, Physical, Virtual, etc.).
     - string :doc:`Vocabulary <_vocabularies/ACCESS_TYPE>`.
     - 1
     - N
   * - accessModes
     - Eligibility/criteria for granting access to users (excellence-based, free-conditionally, free etc.).
     - string :doc:`Vocabulary <_vocabularies/ACCESS_MODE>`.
     - 1
     - N
   * - tags
     - Keywords associated to the Resource to simplify search by relevant keywords.
     - string
     - 1
     - N
4. Availability
########

        
.. list-table:: EOSC Service Profile Elements of "Availability" block
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
   * - languageAvailabilities
     - Languages of the (user interface of the) Resource.
     - string
     - 1
     - Y
5. Classification
########

        
.. list-table:: EOSC Service Profile Elements of "Classification" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - resourceGeographicLocations
     - List of geographic locations where data, samples, etc. are stored and processed.
     - string
     - 1
     - N
6. Contact
########

        
.. list-table:: EOSC Service Profile Elements of "Contact" block
   :widths: 25 50 10 10 10
   :header-rows: 1

   * - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory


   * - mainContact
     - Service's Main Contact/Resource Owner info.
     - tns:serviceMainContact
     - 1
     - Y
   * - publicContacts
     - List of the Service's Public Contacts info.
     - tns:servicePublicContact
     - 1
     - Y
   * - helpdeskEmail
     - The email to ask more information from the Provider about this Resource.
     - string
     - 1
     - Y
   * - securityContactEmail
     - The email to contact the Provider for critical security issues about this Resource.
     - string
     - 1
     - Y
