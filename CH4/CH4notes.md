ERD - Entity Relationship Diagram
    clean end user visual of db
    main take aways of db
        entities - class not object
        attributes
        relationships
    
Attributes
    charicteristics of entities
    `required attributes`
    `optional attribute`
    Domain -set of possible values for a griven attribute
    `Identifiers`- one or more attributes that uniquely identify each entity instance
    `Composite identifier`-Primary key with more than one attribute
    `Composite attribute` attribute that can be divided into more attributes
    `Simple attribute` indivisible attribute
    `Singel-valued attribute`Attribute that has only a single value
    `Multivalued attributes` attributes that have many values
    `Derived attribute` calculated by other attributes

Relationships
    Association between entities that ALWAYS OPERATE in BOTH DIRECTIONS
    `Participants`
    `Connectivity` describes relationship
    `Cardinality` how many connections to related entities

Existance Dependence
    dependent
        only exists whith another entity
    independence -Strong entity/regular entity
        exists apart from all other entities
Relationship Strength
    Weak `baseball player has a ball its their ball`
        Primary key of the related entity does not contain a primary key component of the parent entity
    Strong `baseball player has a ball and the ball has their name on it`
        Primary key of the related entity contains a primary key component of the parent entity


# Relationship Participation
    Optional
        an entity doesn't need another to exist
    Manditory
        an entity needs another entity to exist
    
# Relationship Degree
    Indicates the number of entities with a relashionship
    