# WeblogChallenge
This is an interview challenge for Paytm Labs. Please feel free to fork. Pull Requests will be ignored.

The challenge is to make make analytical observations about the data using the distributed tools below.

## Assumptions:

1. visitor_id = client_port + "_" + user_agent

2. Session THRESHOLD time is assumed to be 15 minutes:

- A session can last longer than 15 minutes if the requests are actively received

- A session can last shorter than 15 minutes if there is no activity beyond 15 minutes from the last received request

3. A session is specific to a user. Every user can have:

- Different number of sessions

- Different duration of sessions
