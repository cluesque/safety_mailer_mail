# Safety Mailer Mail Demo

This project demonstrates how to use the [safety_mailer](https://github.com/cluesque/safety_mailer) gem in a standalone Ruby application without Rails.

## Overview

The safety_mailer gem provides email safety features to prevent accidentally sending emails to real recipients in development and staging environments.

This demo shows how to configure and use safety_mailer with the standard Ruby `mail` gem outside of a Rails application.

## Usage

```bash
bundle install
bundle exec mail_the_time bob@example.com
```
