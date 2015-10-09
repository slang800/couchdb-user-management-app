# CouchDB User Management App
A web app to manage CouchDB users and database security settings.

## Setup

```
git clone git@github.com:gr2m/couchdb-user-management-app.git
cd couchdb-user-management-app
npm install
node_modules/.bin/bower install
node_modules/.bin/grunt serve
```

## Required CouchDB Settings
CORS must be enabled in the CouchDB you try to connect to, and the apps' URL must either be listed in `cors.origin`, or it must be set to `*` (allows all origins).

Section  | Option      | Value
-------- | ----------- | -----
**cors** | credentials | true
**cors** | origins     | *
