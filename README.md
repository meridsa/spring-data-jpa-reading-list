# Understanding Spring Data JPA

Not as easy an undertaking as desired but here some supplementary 
reading with the [main docs](https://spring.io/projects/spring-data-jpa#learn)

 - [Spring Transactional tests are a pitfall](https://www.nurkiewicz.com/2011/11/spring-pitfalls-transactional-tests.html) 
really good overview of common 
issues related to transactions where test-cases indicate the easy and simple 
errors you may encounter
 - [The meaning of cascadetypes for many-to-one relations](https://stackoverflow.com/questions/13027214/what-is-the-meaning-of-the-cascadetype-all-for-a-manytoone-jpa-association)
 self explanatory, shows using cascade in many-to-one relation is most often a mistake!
 - [Hibernate many-to-one ignores lazy-load](https://stackoverflow.com/questions/17155452/hibernate-lazy-loading-for-reverse-one-to-one-workaround-how-does-this-work)
 a little gotcha from your favourite ORM