# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

The Roadmap looks as follows
- Providing toys/inflatables/something as a easy service for kids to have fun.
- Ability to book and pay for the service online without the assistance from customer support.
  - Customer should select date and time, check availability and select package.
- The company associates are repsonsible for installing/getting ready/unpacking the products vice versa.
- Trained associates are responsible for safety features.
- Planning to introduce only in weekends initially.
- Initially Products and services are given as packages like - Basic, Standard and Pro.

Open questions
  - How to maintain product inventory.
  - How to maintain services like (availability).
  
  Data Model
  `Customer` will have `Events` and `Order`
  - Order belongs to Customer. Each order will have Event.  
  - Event - `date and time`, `packages`
  - Package - has_many products/services


