# Concept 2 API
## How to grab the data

Official documentation:
https://log.concept2.com/developers/documentation/

### Getting the personal API token
> If you are requesting a key to read your own results only:
> 1. Create or log into your account at log.concept2.com. 
> 2. Go to Profile > Edit Profile.
> 3. Click on Applications and scroll down to Concept2 Logbook API.
> 4. Click Connect to Concept2 Logbook API. You will be asked to authorize access to your account. Click Approve Concept2 API.
> 5. On the next screen, you will see your access token, which can be used to read your results via the API. For more information, see https://log.concept2.com/developers/documentation/.

### Making an API call
Once you have got a valid access token, you can then use it in the HTTP headers of your API calls, for example:
```
HTTP/1.1
GET https://log.concept2.com/api/users/me/results
Host: log.concept2.com
Content-Type: application/json
Authorization: Bearer TA3n1vrNjuQJWw0TdCDHnjSmrjIPULhTlejMIWqq
```

# GitHub Contribution Graph
## How to make a graph

Manually made, inspired from the article https://bitsofco.de/github-contribution-graph-css-grid/, with codepen https://codepen.io/ire/pen/Legmwo/.

# Start a Local Server
Run `python -m http.server`