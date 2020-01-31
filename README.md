# WeblogChallenge
This is an interview challenge for Paytm Labs. Please feel free to fork. Pull Requests will be ignored.

The challenge is to make make analytical observations about the data using the distributed tools below.

## Assumptions:

1. visitor_id = client_port + "_" + user_agent

2. Session THRESHOLD time is assumed to be 15 minutes:

  * A session can last longer than 15 minutes if the requests are actively received

  * A session can last shorter than 15 minutes if there is no activity beyond 15 minutes from the last received request and max_timestamp - min_timestamp is a session is less than 15 minutes

3. A session is specific to a user. Every user can have:

- Different number of sessions

- Different duration of sessions

## Instructions to view the code:

- Google Colab iPython Notebook is used for this assignment and it can be viewed in the URL given below
- When prompted to login, you can choose to ignore/cancel and view the file in read-only mode
- Noetbook URL - https://colab.research.google.com/drive/1jj44HefY8aslmMty8EUg2hdXwCAUMNjz

## Other notes:

- Some of the dataframes shown in the notebook are 'wide'
- If the file is being viewed by the ![Colab Notebook URL](https://colab.research.google.com/drive/1jj44HefY8aslmMty8EUg2hdXwCAUMNjz), please scroll horizontally towards right to view the entire dataframe
