## Inspiration
We are all members of freeCodeCamp San Francisco, meeting twice a week to work with each other as we progress on our journey to develop a new career in software development. Many of our members are recent immigrants to the city.

Ana, having lived in San Francisco for 6 years wanted to create a simple method for connecting people who have recently moved to the city with people like her who have a strong desire to help new women immigrants thrive in their new home.

## What it does
*Using the Meetup-API to collect data on user's interests and background, inUnity provides Pioneers and Allies with potential matches.
*Each is able to send invitations to connect to their matches.
*Once an invitation is accepted the Pioneer and Ally can communicate with anonymity and privacy via the inbuilt messaging service. At any point either user can choose to cease communication.
*The Ally is able to invite their Pioneer to a Meetup event
*The Pioneer is able to accept or deny
*After the Pioneer and Ally have met at this event they are both offered the opportunity to share personal information, if they have not done so already in the face to face environment. This is a double blind opt-in that only proceeds if both are comfortable to proceed.

## How we built it
*We scraped a limited set of test data into a json file using the meetup-api
*This data has been used to test our user matching script which is based on common interests
*Our goal is to create a wider set of weighted matching criteria that includes interests, language, group memberships and home town (city of origin).
*The frontend was created in html and bootstrap 4.

## Challenges we ran into
*Our initial attempts to connect with the meetup-api using node.js in order to use live user data were unsuccessful. The technical challenges proved too great  for our current skill level.
*The decision was made to scrape the api for a limited set of data.


## Accomplishments that we're proud of
Creating the initial interest based matching algorithm
Our team focused approach
Our scoping of the platform using agile methods such as Epics and user stories. The craft.io platform was used to create, share and manage these user stories.

## What we learned
The technical overhead of integrating with an api that has limited documentation and existing use cases should NOT be underestimated.

## What's next for inUnity 
*Continuing work on integrating the meetup-api with the existing MVP.
*Extending the user matching algorithm to include additional weighted criteria
 

