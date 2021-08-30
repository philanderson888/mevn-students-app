# mevn students app

## contents

- [mevn students app](#mevn-students-app)
  - [contents](#contents)
  - [introduction](#introduction)
  - [mongo database](#mongo-database)
  - [back end api](#back-end-api)
  - [front end application](#front-end-application)

## introduction

this work continues on from the local version of the app which has been built here https://github.com/philanderson888/MEVN/tree/master/projects/students where I build a full-stack application locally which builds

- a VueJS front end application
- a back-end API which provides end points for reading and writing data powered by NodeJS with Express
- a Mongo database which holds the data locally 

Now that this app is working fine we ask ourselves the question - can it be ported online so it's available from anywhere on the internet, including

- VueJS front end deployed online
- Back end api deployed online
- Mongo database deployed online

## mongo database

the mongo database has been deployed online at https://mongodb.com where, for free, we can add a new `cluster` and create our first database

apologies the steps are not here but if you need help with this let me know

## back end api

to get the back end api working we need something called `serverless functions` which can be deployed, for free, with our `Netlify` application.  This means that we can have, with the same `Netlify` deployment, both our `front end` and our `back end` code which is handy.

## front end application

to get started with this application I am going to copy the working files from the local version of the application at https://github.com/philanderson888/MEVN/tree/master/projects/students/mevn-05 and remove the `api` folder which provides the back end.

I'll then deploy this to `netlify` so the front end part of the application is deployed

