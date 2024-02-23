# backendChallenge
Challenge for backend engineer candidates

Hi! This is our little coding challenge. It is within one of our business domains but
totally made up, of course. Also the API design is questionable but good enough for
this little task.

As we work within the scrum framework we have written a story for you.

## Context
Our partners sell insurance contracts. As we want to be as digital as possible,
we provide APIs for creating the contracts within our systems for our partners.
However, sometimes our partners can't use the API currently so they send us lists
and we need to transform these lists and interface to our API on the partner's behalf.

Because we are an insurance company, we cannot grant access to our production API
for development purposes. Anyway the API provides the following endpoint for the task.

**//insert made up API description here//**

## User Stories
This is the ordered list of stories. The most valuable story is on top.
## User Story
This is how a user story would look like.

```
Read partner's list and create contracts in the API

As
    King's Bike Leasing (partner)
I like
    to report contracts for new customers as a CSV
so that
    hepster can import them into their systems

Acceptance criteria
- The list is deliverd as attached (KingsBikeLeasingImportList.csv).
- The partner's product names are mapped to hepster's product UUIDs.
- The fields firstname, lastname, email, product are mandatory.
- In case of an error, the CSV's row is in an errorfile with an
  additional field describing the error
```


