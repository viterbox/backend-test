# Back-end Developer Test

Be sure to read **all** of this document carefully, and follow the guidelines within.

## Context

Build a RESTful API that can `create/read/update/delete` user data from a persistence store. 

### User Model

```
{
  "id": "xxx",                  // user ID (must be unique)
  "name": "backend test",       // user name
  "dob": "",                    // date of birth
  "address": "",                // user address
  "description": "",            // user description
  "createdAt": ""               // user created date
  "updatedAt": ""               // user updated date
}
```

### Functionality

- The API should follow typical RESTful API design pattern.
- The data should be saved in the DB, use any persistence store, NoSQL DB is preferred.
- Provide proper API documentation.
- Proper error handling should be used.

## What We Care About

Use any libraries that you would normally use if this were a real production App. Please note: we're interested in your code & the way you solve the problem, not how well you can use a particular library or feature.

_We're interested in your method and how you approach the problem just as much as we're interested in the end result._

Here's what you should strive for:

- Good use of the backend stack selected
- API design best practices.
- Solid testing approach.
- Extensible code.

### Basic Requirements

  - Use Springboot (Java or Kotlin), NodeJs (Express, Loopback or Hapi framework) or DotNetCore Framwork (C#)
  - Use any persistence store. NoSQL DB is preferred.
  - Write concise and clear commit messages.
  - Write clear **documentation** on how it has been designed and how to run the code.

### Bonus

  - Provide proper unit tests.
  - Add a read only endpoint to fetch location information based off the user's address (use [NASA](https://api.nasa.gov/api.html) or [Mapbox](https://www.mapbox.com/api-documentation/) APIs)
  - Providing an online demo is welcomed, but not required.

## Good luck!

We look forward to seeing what you can do. Remember, although it is a test, there are no specific right or wrong answers that we are looking for - just do the job as best you can.