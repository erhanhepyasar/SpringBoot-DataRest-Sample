Spring Boot Application
-----------------------------------------------

Dependencies: JPA, Rest Repositories, H2 Database


Explanation:
------------------------------------------------
- In this project by using Spring Data Rest (Rest Repositories dependency) we don't need to create a controller class.
- Just add create the interface and add necessary annotaion as below:

@RepositoryRestResource(collectionResourceRel="aliens", path="aliens")
public interface AlienRepo extends JpaRepository<Alien, Integer> {

}

- Use Postman and perform GET, PUT, POST and DELETE methods


Source: https://www.youtube.com/watch?v=XmAISyK2FsU&list=PLsyeobzWxl7qednPdXyD2yd502artL7Kz&index=8
