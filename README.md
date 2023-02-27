# pcn-content-model
Repository containing json schema for the yousee content model.

Messages contain 1 of the payload entity types.
```
── Message
   ├── Header
   └── Payload
       ├── Content
       │   └── MediaMetadata
       ├── Season
       │   └── MediaMetadata
       ├── Series
       │   └── MediaMetadata
       ├── OnDemandEvents
       ├── ScheduleEvent
       └── Manifestation
```


### gradle plugin for gradle java pojo from schema
See:  
https://github.com/joelittlejohn/jsonschema2pojo/tree/master/jsonschema2pojo-gradle-plugin  
See example:  
https://thewokecoder.io/generate-pojo-from-json/


### gradle plugin for gradle kotlin pojo from schema
See:  
https://github.com/pwall567/json-kotlin-gradle


### npm package for typescript typings from schema  
See:  
https://www.npmjs.com/package/json-schema-to-typescript