
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
   * - keywords
     - The keyword(s) or tag(s) used to describe the resource.
     - string
     - 1
     - N
   * - license
     - A license document that applies to this content, typically indicated by URL.
     - string
     - 1
     - Y
   * - accessRights
     - The access status of a resource (open, restricted, paid).
     - string
     - 1
     - Y
   * - versionDate
     - The version date for the most recently published or broadcast resource.
     - dateTime
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


   * - targetGroups
     - The principal users(s) for which the learning resource was designed.
     - string
     - 1
     - Y
   * - learningResourceTypes
     - The predominant type or kind that characterizes the learning resource.
     - string
     - 1
     - N
   * - learningOutcomes
     - The descriptions of what knowledge, skills or abilities students should acquire on completion of the resource.
     - string
     - 1
     - Y
   * - expertiseLevel
     - Target skill level in the topic being taught.
     - string
     - 1
     - Y
   * - contentResourceTypes
     - The predominant content type of the learning resource (video, game, diagram, slides, etc.).
     - string
     - 1
     - N
   * - qualifications
     - Identification of certification, accreditation or badge obtained with course or learning resource.
     - string
     - 1
     - N
   * - duration
     - Approximate or typical time it takes to work with or through the learning resource for the typical intended target audience.
     - string
     - 1
     - N
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


   * - languages
     - The language in which the resource was originally published or made available.
     - string
     - 1
     - Y
   * - geographicalAvailabilities
     - Locations where the Resource is offered.
     - string
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


   * - scientificDomains
     - The branch of science, scientific discipline that is related to the Resource.
     - tns:serviceProviderDomain Vocabularies: :doc:`Domain <_vocabularies/SCIENTIFIC_DOMAIN>` / :doc:`Subdomain <_vocabularies/SCIENTIFIC_SUBDOMAIN>`.
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


   * - firstName
     - First Name of the Resource's main contact person/manager.
     - string
     - 1
     - Y
   * - lastName
     - Last Name of the Resource's main contact person/manager.
     - string
     - 1
     - Y
   * - email
     - Email of the Resource's main contact person/manager.
     - string
     - 1
     - Y
   * - phone
     - Telephone of the Resource's main contact person/manager.
     - string
     - 1
     - N
   * - position
     - Position of the Resource's main contact person/manager.
     - string
     - 1
     - N
   * - organisation
     - The organisation to which the contact is affiliated.
     - string
     - 1
     - N
