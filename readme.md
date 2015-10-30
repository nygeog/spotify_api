##Getting Data About Artists https://developer.spotify.com/spotify-echo-nest-api/

The Echo Nest API provides methods to return a wide range of data about artists. As well as basic profile information and statistics like familiarity, years active, Twitter handle, and links to official sites. Here is an example of a typically useful call that you can make to the Echo Nest API to get artist’s location:

	http://developer.echonest.com/api/v4/artist/profile?api_key={echonest_api_key}&id=spotify:artist:5l8VQNuIg0turYE1VtM9zV&format=json&bucket=artist_location
and here is the response:

	{
	  "response": {
	    "status": {
	      "version": "4.2",
	      "code": 0,
	      "message": "Success"
	    },
	    "artist": {
	      "id": "ARTQ8QP1187FB3D220",
	      "artist_location": {
	        "city": "Montreal",
	        "region": null,
	        "location": "Montreal, Canada",
	        "country": "Canada"
	      },
	      "name": "Leonard Cohen"
	    }
	  }
	}