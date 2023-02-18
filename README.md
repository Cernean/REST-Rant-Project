# Project REST-Rant

REST-Rant is an app where users can review restaurants.

|Method | Path | Purpose |
|------ | ---- | ------- |
| GET | / | Homepage |
| GET | /places | List all places |
| POST | /places | Create new place|
| GET | /places/new | Form page for creating a new place |
| GET | /places/:id | Details about a particular place |
| PUT | /places/:id | Update a particular place |
| GET | /places/:id/edit | Form page for editing an existin place | 
| DELETE | /places/:id | Delete a particular place |
| POST | /places/:id/rant | Create a rant (comment) about a particular place |
| DELETE | /places/:id/rant/:rantld | Delete a rant (comment) about a particular place |
| GET | * | 404 page (matches any route not defined above)|

---

1. As a dev, I need to request data from 
the server about a specific places  
 
