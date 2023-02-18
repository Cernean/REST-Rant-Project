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
| DELETE | /places/:id/rant/:rantId | Delete a rant (comment) about a particular place |
| GET | * | 404 page (matches any route not defined above) |

---

1. As a dev, I need to request data from 
the server about a specific places using a new endpoint, so i can populate the places detail page. 
2. As a user, i need a place to view the specifiv details of one of my pages on a new JSX page, so i can use the app
2. As a user, I need to edit a place 
 
