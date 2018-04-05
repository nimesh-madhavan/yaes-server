YAES - Yet Another Expense Splitter
-----------------------------------

### Master Build Status
[![CircleCI](https://circleci.com/gh/gauravagarwalr/Yet-Another-Expense-Splitter/tree/master.svg?style=svg)](https://circleci.com/gh/gauravagarwalr/Yet-Another-Expense-Splitter/tree/master)

Expense Splitting Web App ( similar to Splitwise):

Primary purpose of the web app is to keep track of your expenses, payables and receivables to individuals.

## Planned Features

    - Add users to your app. You will eventually split expense with them.
    - Add expense and it can be sharable among selected users.
    - Visibility of payables and receivables per user.
    - Visibility of total payables and receivables.
    - Visibility of all the individual expenses involving you at once place.
    - Settle up with any user.
    - Delete any expense.

# Dev

  ## Setup

    $ go get -u github.com/golang/dep/cmd/dep # Install Dep

    $ go get -u github.com/gauravagarwalr/Yet-Another-Expense-Splitter

    $ cd $GOPATH/src/github.com/gauravagarwalr/Yet-Another-Expense-Splitter

    $ make setup

  ## Run Server

    $ make run

  ## Dev Run

    $ make dev-run

  ## Docs

    $ make setup-docs

    $ make docs

  ## Tests

    $ DB_NAME="yaes-test" make setup-db # Only first time
    $ make test
