# The API that i used in the website this ones

- API For LocationIQ:

1. Description:
 LocationIQ provides flexible enterprise-grade location based solutions.

2. API Usage:

- static map : Requests can be sent to the following endpoint.
GET [https://maps.locationiq.com/v3/staticmap](https://maps.locationiq.com/v3/staticmap)

3. API Endpoints/Request URLs:

- Depending on which Maps SDK you decide to use, you will need to use either the Style Specification URL or Tile URLs.

- Style Specification URL:
For Map box-GL SDKs, use a Style Specification URL. A Style URL looks like this:

[https://tiles.locationiq.com/v3/<theme>/<type>.json?key=<access_token>
](https://tiles.locationiq.com/v3/<theme>/<type>.json?key=<access_token>
)

- Tile URLs:
For LeafletJS and other mapping libraries, you need to specify Tile URLs instead:
[https://{s}-tiles.locationiq.com/v3/<theme>/r/{z}/{x}/{y}.<format>?key=<access_token>](https://{s}-tiles.locationiq.com/v3/<theme>/r/{z}/{x}/{y}.<format>?key=<access_token>)

4. Authentication Key: every api you use it must have an unique key and this key allow the developers to have a specific number to use it in the code  also this key can be used in public or private context in addition it increase the security for the api it self and every key have a limit number to use to avoid problem of bad request.

***

## API For weatherbit.io

1. Description: This API returns a 16 day forecast in 1 day intervals from any point on the planet.

2. API Usage:

- 16 Day Weather Forecast API: Requests can be sent to the following endpoint.
GET [http://api.weatherbit.io/v2.0/forecast/daily](http://api.weatherbit.io/v2.0/forecast/daily)

3. API Endpoints/Request URLs:

- Get forecast by lat / lon Style Specification URL:
[http://api.weatherbit.io/v2.0/forecast/daily?lat=%7Blat%7D&lon=%7Blon%7D&key=%7BKEY%7D](http://api.weatherbit.io/v2.0/forecast/daily?lat=%7Blat%7D&lon=%7Blon%7D&key=%7BKEY%7D)

4. Authentication Key:

- every api you use it must have an unique key and this key allow the developers to have a specific number to use it in the code  also this key can be used in public or private context in addition it increase the security for the api it self and every key have a limit number to use to avoid problem of bad request.

***

## API For movie

1. Description: The API service is for those of you interested in using our movie TV show or actor images and/or data in your application.

2. API Usage:

- search by keyword GET
[https://api.themoviedb.org/3/search/keyword](https://api.themoviedb.org/3/search/keyword)

3. API Endpoints/Request URLs

- [https://api.themoviedb.org/3/search/keyword?api_key=<<api_key>>&page=1](https://api.themoviedb.org/3/search/keyword?api_key=<<api_key>>&page=1)

4. Authentication Key:

- every api you use it must have an unique key and this key allow the developers to have a specific number to use it in the code  also this key can be used in public or private context in addition it increase the security for the api it self and every key have a limit number to use to avoid problem of bad request.
