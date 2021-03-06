# Measurement Canada Front-End Developer Interview

## Assumptions
- User is someone with access to a keyboard
- User is someone who speaks, reads, and writes in english

## What else needs to be done
- Clean up accessibility
- A lot more tests
- Clean up styling to better match
- Change success message so that its responsive

## How to run
- npm i
- (necessary to get location search working. If this is excluded, location search will switch to a regular input) create file called .env in root directory and add the following line to the top: REACT_APP_GOOGLE_API_KEY=<API-KEY>
- npm start


## Interview Task

Build a Patient Referral Form using this [design spec](https://www.figma.com/file/mviScHVBuziEsW5hC5JaPr/Patient-Referral-Form-interview-Copy?node-id=0%3A1).

There is no need to build any backend (api layer, server, database). For simulating form submission, you can do a POST to /api/referrals


## Duration

Please set aside up to 8 hours to work on this challenge. We are interested in seeing how far you can get with 8 hours and therefore, completion is not the highest priority. 

Please have your submission in by <b>Sunday August 30th at midnight EST</b>.

## Submission
1.  Fork this repo
2.  Build Patient Referral Form. Suggested libraries
    -  Material UI components - [https://material-ui.com/](https://material-ui.com/)
    -  Address lookup - [https://www.npmjs.com/package/react-places-autocomplete](https://www.npmjs.com/package/react-places-autocomplete)
4.  Submit a Pull Request (PR)
5.  In the PR, include a README that includes the following:
    - If you made any assumptions, what are they
    - Outline what else needs to be done if given more time
    - Instructions on how to run it
6. Send an email to noor.syed@canada.ca and jasper.chan@canada.ca to let us know your submission has been completed.

