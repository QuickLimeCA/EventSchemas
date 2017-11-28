# EventSchemas
The design of QuickLime uses an [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html) architecture to track the issuance, renewal and revocation of certificates.

In order to track the format of the data for each of the events in the system (which QuickLime will need to be able to process every version of), this repository will contain a set of JSON Schemas, versioned using [SchemaVer](https://snowplowanalytics.com/blog/2014/05/13/introducing-schemaver-for-semantic-versioning-of-schemas/) in order to make the JSON data [self-describing](https://snowplowanalytics.com/blog/2014/05/15/introducing-self-describing-jsons/).
