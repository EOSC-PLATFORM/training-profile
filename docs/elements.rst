
.. _service:

EOSC Training resource
========

In addition tothe properties defined in the profile for EOSC Resource (ADD LINK), the profile for Training Resources include the following properties:

.. list-table:: 
   :widths: 10, 15, 50, 15, 15, 15, 15
   :header-rows: 1

   * - Group
     - Element name
     - Description
     - Type
     - Multiplicity
     - Mandatory
     - Suggestions
   * - Basic
     - eoscRelatedServices
     - The name(s) of (all) the Provider(s) that manage or deliver the Resource in federated scenarios.
     - string
     - 1
     - O
     - 
   * - 
     - keywords
     - The keyword(s) or tag(s) used to describe the resource.
     - string
     - 1
     - O
     - 
   * - 
     - licenseURL
     - A license document that applies to this content, typically indicated by URL.
     - string
     - 1
     - M
     - 
   * - 
     - licenseName
     - License name
     - String
     - 1
     - M
     - 
   * - 
     - accessRights
     - The access status of a resource (open, restricted, paid).
     - string
     - 1
     - M
     - 
   * - 
     - versionDate
     - The version date for the most recently published or broadcast resource.
     - dateTime
     - 1
     - M
     - 
   * - Learning
     - targetGroups
     - The principal users(s) for which the learning resource was designed.
     - string
     - 1..n
     - M
     - 
   * - 
     - learningResourceTypes
     - The predominant type or kind that characterizes the learning resource.
     - string
     - 1
     - O
     - 
   * - 
     - learningOutcomes
     - The descriptions of what knowledge, skills or abilities students should acquire on completion of the resource.
     - string
     - 1
     - M
     - 
   * - 
     - expertiseLevel
     - Target skill level in the topic being taught.
     - string
     - 1
     - M
     - 
   * - 
     - contentResourceTypes
     - The predominant content type of the learning resource (video, game, diagram, slides, etc.).
     - string
     - 1
     - O
     - 
   * - 
     - qualifications
     - Identification of certification, accreditation or badge obtained with course or learning resource.
     - string
     - 1
     - O
     - 
   * - 
     - duration
     - Approximate or typical time it takes to work with or through the learning resource for the typical intended target audience.
     - string
     - 1
     - R
     - 
   * - Availability
     - languages
     - The language in which the resource was originally published or made available.
     - string
     - 1
     - M
     - ISO standard
   * - Classification
     - scientificDomains
     - The branch of science, scientific discipline that is related to the Resource. 
     - tns:serviceProviderDomain Vocabularies: Domain / Subdomain.
     - 0..n
     - O
     - 
   * - 
     - tags
     - Keywords associated to the Resource to simplify search by relevant keywords.
     - string
     - 0..n
     - O
     - 
   * - Creators
     - creators
     - The main researchers involved in producing the data, or the authors of the publication, in priority order. To supply multiple creators, repeat this property.
     - object
     - 1...n
     - M
     - 
   * - 
     - creatorName
     - The full name of the creator
     - string
     - 1
     - M
     - Surname, Name
   * - 
     - creatorRole
     - The role of the creator
     - Credit vocabulary
     - 1
     - O
     - 
   * - 
     - creatorPIDSchema
     - PID schema
     - 
     - 
     - O
     - e.g. ORCID, ROR.org
   * - 
     - creatorPID
     - Uniquely identifies an individual or legal entity, according to various schemes.
     - string
     - 1
     - O
     - 
   * - 
     - affiliations
     - The organizational or institutional affiliation of the creator.
     - object
     - 0..n
     - O
     - 
   * - 
     - affiliationName
     - Name of the organisation
     - string
     - 1
     - M
     - 
   * - 
     - affiliationIdentifier
     - Uniquely identifies the organizational affiliation of the creator.
     - string
     - 1
     - O
     - ROR.org, ISNI, Wikidata
   * - 
     - email
     - email of the creator
     - string
     - 0..1
     - O
     - 
