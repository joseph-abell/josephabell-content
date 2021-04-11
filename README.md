# josephabell-content

Content for josephabell.co.uk

The website josephabell.co.uk gets it's content from a dynamodb table. But,
in order to get the data into the database, we need a CMS.

We use netlifycms to provide the website some data and images, and we use
netlify git hooks to push that content into the database for retrieval for the frontend.
Yes this goes against Netlify's beloved jamstack but what is the point of
a dev blog if it isn't heavily over engineered for learning's sake. 
