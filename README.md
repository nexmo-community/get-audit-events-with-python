# get-audit-events-with-python

Uses Nexmo Audit API to retrieve a list of audit event types and audit events.

Tested with Python 3

## Requirements

* [Requests](http://docs.python-requests.org/en/master/)
* [Flask](http://flask.pocoo.org/)

## Installation

1. `pip install requests` 
2. `pip install Flask`

## Running the application

1. Run the app `python3 audit_events.py` 
2. Navigate to `localhost:3000`
3. Select a specific event type or ALL (to retrieve all event types)
4. Click `Submit`

You will be presented with a table of audit events.
