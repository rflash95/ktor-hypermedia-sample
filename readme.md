## HyperMedia
Tell the client how to continue or what to do with the current resource

----

```json
{
   "book":{
      "id":"2233",
      "title":"How to grow apples",
      "author":"Mr. Appleton"
   },
   "links":[
      {
         "href":"http://localhost:8080/library/book/2233/checkout",
         "rel":"checkout",
         "type":"GET"
      },
      {
         "href":"http://localhost:8080/library/book/2233/reserve",
         "rel":"reserve",
         "type":"GET"
      }
   ]
}
```