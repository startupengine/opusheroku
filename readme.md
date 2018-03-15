generation for the ease of sharing.

## Features

* Create manage Wikis (group of knowledge pages)
* Create nested pages inside wikis
* Manage wikis and pages by spaces and tags
* Invite employees by email
* Powerful ACL to assign different roles and permissions to employees.
* Slack notifications for the wiki updates
* Mark wikis and pages as favorite
* Watch wiki/pages to get notified
* In-app notifications
* Discussions using comments
* Create reusable page templates
* Search across the knowledge base
* ..and more

## Requirements

* PHP 7.0+
* MySQL 5+

## Installation

- Run the below command in your terminal:
  ```bash
  composer create-project zeeshanu/opus
  ```
- Create `.env` using `.env.dist` and populate the relevant information
- Install the dependencies
  ```bash
  composer install
  ```
- Open the project directory and run the below
  ```bash
  php artisan migrate
  ``` 
- Generate an application key
  ```bash
  php artisan key:generate
  ```
- Run the database seeder
  ```bash
  php artisan db:seed
  ```

## Todo

- [x] ~~Access Control~~
  - [x] ~~Create and Update User Roles~~ 
  - [x] ~~Create User Roles~~
  - [x] ~~Assign Roles to Employees~~
  - [x] ~~Invite employees by email~~
- [x] ~~Wikis~~
  - [x] ~~Create Spaces (Group of Wikis)~~ 
  - [x] ~~Create Wikis inside Spaces~~
  - [x] ~~Update and Delete Wikis~~
  - [x] ~~Create Pages inside Wikis~~
  - [x] ~~Syntax Highlighting for Code~~
  - [x] ~~Update and Delete Pages~~
  - [x] ~~Hierarchical Page Trees~~
  - [x] ~~Rearrange Pages in Wikis~~
  - [x] ~~Mark Pages as Favorite~~
  - [x] ~~Leave Comments~~
    - [x] ~~Mention Team Members~~
    - [x] ~~Add Emojis~~
  - [x] ~~Watch Wikis to get notified for updates~~
  - [x] ~~Save pages in Read List (Like Watch Later in Youtube)~~
  - [x] ~~Add Tags to Pages~~
  - [x] ~~List all Pages available in a tag~~
- [x] ~~Team Dashboard (Monitor Team Activity)~~
- [x] ~~User Dashboard (Monitor User Activity)~~
- [x] ~~Export Documents~~
    - [x] ~~Export Page as PDF~~
    - [x] ~~Export Page as MS Word File~~
- [x] ~~Notifications~~
  - [x] ~~Add slack integration in team~~
  - [x] ~~Notify on slack~~
  - [x] ~~In-app Notification balloon~~
  - [x] ~~Mentioned in comment notifications~~
- [x] ~~Global Search~~
- [ ] Responsive
- [x] ~~Upload demo somewhere~~

## Contribution

* Report issues
* Open pull request to **DEV BRANCH** with improvements
* Spread the word
* Reach out to me directly at ziishaned@gmail.com or on twitter [@ziishaned](https://twitter.com/ziishaned)

## License
The license holder is allowed to use the software for free, as long as they don't make money using it. [Read more in License](https://github.com/zeeshanu/opus/blob/master/LICENSE.md)

# Deploying

Click the button below to deploy a new instance of StartupEngine to Heroku instantly.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/luckyrabbitllc/Opus-Heroku)

