# pivotal-trello-sync

This project provides a worker that can keep a Pivotal and Trello board in sync.

## Instructions

Deploy to Heroku.
Set up the following environment variables:

* PIVOTAL_API_KEY
* PROJECT_BOARD_MAPPINGS - A comma-delimited list of projects mapped between Trello and Pivotal, in the format:
<Pivotal Project #>:<Trello Board Number>, <Pivotal Project #>:<Trello Board Number>
