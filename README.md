# graphql_module
```
query{
    nodeQuery(filter:{conditions:[{field: "type", value: ["article"]}]}){
        entities {
            entityBundle
            entityType
            entityPublished
            entityUuid
            entityCreated
            entityLabel
            entityChanged
            entityId
    }
  }
}