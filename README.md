YAES - Yet Another Expense Splitter
-----------------------------------

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

    $ createdb yaes-dev

    $ glide install

  ## Run Server

    $ ./scripts/build-and-run.sh

  ## Docs

    $ go get -u github.com/go-swagger/go-swagger/cmd/swagger

    $ swagger serve swagger.yml
