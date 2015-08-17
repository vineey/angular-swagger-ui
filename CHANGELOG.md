###CHANGELOG

##### 0.1.71 xmlify

+ use node v12 and up
+ use the first item in operation.consume and produce as the default content-type and response-type respectively

##### 0.1.7  chromatic-adornment

+ add support for application/xml response type with formatted response body
+ use the global consumes/produces definition if an operation doesn't specify its own
+ use ng-bind-html for descriptions to support html syntax, this requires ngSanitize module
+ add support for $ref definition on operation parameters
+ use bootstrap less only, to remove dependency from bootstrap js and jquery