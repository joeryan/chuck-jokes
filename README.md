# chuck-jokes
Chuck Norris joke api translator

This API simplifies the response retrieved from the Chuck Norris joke API.

A request to api/random returns a json object with only the id, url, and value extracted from the 
normal json returned from api.chucknorris.io/jokes/random 
{"categories":[],"created_at":<datetime>,"icon_url":<url_stnirg>,"id":<string>,"updated_at":<datetime>,"url":<url_stnirg>,"value":<string>}

GET api/random

response: {'id': <string>, 'url': <url_string>, 'value': <string>}
