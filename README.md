# Overtime Tracker

 App that keeps track of overtime hours logged by salaried workers

## Set-up
- `git clone `
- `cd overtime-tracker`
- `bundle install`
- `rake db:migrate && rake db:seed`
- `rails server` or `rails s`
- navigate to *localhost:3000*

## Features
- Approval workflow
- SMS sending: link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers/superusers for approval
- Needs to be documented if employee did not log overtime

## Tech Used
- Ruby
- Rails (devise, administrate, .dotenv) gems
- JS
- Bootstrap (UI)
- RSpec (Testing)
- Twilio API (Messaging)
