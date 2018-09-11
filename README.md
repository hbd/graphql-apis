# Public GraphQL APIs

*A collective list of public [GraphQL](https://graphql.org/) APIs. PRs are welcome :smile:*
If you are interested in GraphQL in general, check out [awesome-graphql](https://github.com/chentsulin/awesome-graphql).

## Official APIs

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| Brandfolder | Digital asset management platform | [Try it!](https://graphql.brandfolder.com/) | [Repo](https://github.com/brandfolder/graphqlify)
| Buildkite | Continuous integration and deployments | [Try it!](https://graphql.buildkite.com/) | [Docs](https://building.buildkite.com/tutorial-getting-started-with-graphql-queries-and-mutations-11211dfe5d64#.7uhjusw1q)
| Catalysis Hub | Chemical surface reaction energies and structures | [Try it!](http://api.catalysis-hub.org/graphql) | [Repo](https://github.com/SUNCAT-Center/CatalysisHubBackend)<br> [Docs](http://docs.catalysis-hub.org/en/latest/tutorials/index.html#graphql)
| Deutsche Bahn | Infrastructure Data, like realtime facility status, stations, timetables and more | [Try it!](https://bahnql.herokuapp.com/graphql) | [Repo](https://github.com/dbsystel/1BahnQL)
| Digitransit HSL | Transit routes and realtime schedules from Helsinki Regional Transport Authority, Finland | [Try it!](https://api.digitransit.fi/graphiql/finland) | [Docs](https://digitransit.fi/en/developers/apis/1-routing-api/1-graphiql/)
| EHRI | Holocaust-related archival materials | [Try it!](https://portal.ehri-project.eu/api/graphql/ui) | [Docs](https://portal.ehri-project.eu/api/graphql)
| EtMDB | Ethiopian Movie Database | [Try it!](https://etmdb.com/graphql?query=%7B%0A%20%20allCinemaDetails(before%3A%20%222017-10-04%22%2C%20after%3A%20%222010-01-01%22)%20%7B%0A%20%20%20%20edges%20%7B%0A%20%20%20%20%20%20node%20%7B%0A%20%20%20%20%20%20%20%20slug%0A%20%20%20%20%20%20%20%20hallName%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A) | [Docs](https://etmdb.com/api/docs/)
| Gdom | DOM Traversing and Scraping using GraphQL | [Try it!](http://gdom.graphene-python.org/graphql?query=%7B%0A++page%28url%3A%22http%3A%2F%2Fnews.ycombinator.com%22%29+%7B%0A++++items%3A+query%28selector%3A%22tr.athing%22%29+%7B%0A++++++rank%3A+text%28selector%3A%22td+span.rank%22%29%0A++++++title%3A+text%28selector%3A%22td.title+a%22%29%0A++++++sitebit%3A+text%28selector%3A%22span.comhead+a%22%29%0A++++++url%3A+attr%28selector%3A%22td.title+a%22%2C+name%3A%22href%22%29%0A++++++attrs%3A+next+%7B%0A+++++++++score%3A+text%28selector%3A%22span.score%22%29%0A+++++++++user%3A+text%28selector%3A%22a%3Aeq%280%29%22%29%0A+++++++++comments%3A+text%28selector%3A%22a%3Aeq%282%29%22%29%0A++++++%7D%0A++++%7D%0A++%7D%0A%7D) | [Repo](https://github.com/syrusakbary/gdom)
| GitHub | Web-based Git repository hosting service | [Try it!](https://developer.github.com/v4/explorer/) | [Docs](https://developer.github.com/v4/)
| GraphLoc  | Find a geolocation of an IP address including latitude, longitude, city, country, time zone and area code. Free to use, SSL supported | [Try it!](https://graphloc.com) | [Docs](https://www.graphloc.com)
| GraphQL Community Graph | This is an Graph Database full of activity of the GraphQL community, including Twitter, StackOverflow, GitHub, Meetups, Slack. | [Try it!](https://graphql.communitygraph.org/graphiql/) | [Repo](https://github.com/neo4j-graphql/graphql-community)
| GraphQL Europe | Europe's first GraphQL conference | [Try it!](https://api.graphql-europe.org/?query=%7B%0A%20%20conferences%20%7B%0A%20%20%20%20name%0A%20%20%20%20year%0A%20%20%7D%0A%7D) |
| HIVDB | A curated database to represent, store and analyze HIV drug resistance data | [Try it!](https://hivdb.stanford.edu/page/graphiql/) | [Docs](https://hivdb.stanford.edu/page/webservice/)
| Hollowverse | The religions and political views of the influentials. | [Try it!](https://api.hollowverse.com/playground) | [Docs](https://github.com/hollowverse/hollowverse/wiki/API-Development)<br>[Repo](https://github.com/hollowverse/api)
| Idobata | Dedicated chat for team development. | [Try it!](https://idobata.io/api) | |
| Memair | Quantified self / extended mind platform | [Try it!](https://memair.com/graphiql) | [Docs](https://docs.memair.com)
| melodyRepo | Fast and reliable dependency manager for Go | [Try it!](https://melody.sh/play/) | [Docs](https://melody.sh/docs/api)
| Microsoft Graph (DEMO) | Connect to the data that drives productivity – mail, calendar, contacts, documents, directory, devices, and more. | [Try it!](https://graphql-demo.azurewebsites.net/) | [Repo](https://github.com/microsoftgraph/graphql-demo)
| Shopify Storefront | The Storefront API gives you full creative control to build customized purchasing experiences for your customers. | [Try it!](https://help.shopify.com/api/storefront-api/graphql-explorer) | [Docs](https://help.shopify.com/api/storefront-api)<br>[Examples](https://github.com/Shopify/storefront-api-examples)
| Universe |  Check what your friends are doing & find unique events near you using our filter. | [Try it!](https://developers.universe.com/page/graphql-explorer) | [Docs](https://developers.universe.com/docs/graphql)
| Yelp  | User Reviews and Recommendations of Top Restaurants, Shopping, Nightlife, Entertainment, Services and More | [Try it!](https://www.yelp.com/developers/graphiql) | [Docs](https://www.yelp.com/developers/graphql/guides/intro)

## Unofficial API proxies

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| Contentful | "CMS as a Service". Graph*i*QL demo allows to query a simple blog, but the library itself generates a schema automatically for any content model you store in Contentful. | [Try it!](https://cf-graphql-demo.now.sh/) | [Repo](https://github.com/contentful-labs/cf-graphql)
| Discord | Access the Discord API in GraphQL, powering WidgetBot widgets | [Try it!](https://widgetbot.io/api/graphql/) | [Repo](https://github.com/widgetbot-io)
| Hacker News<br>Reddit<br>Twitter<br>Giphy | GraphQL Hub | [Try HN!](https://www.graphqlhub.com/playground/hn2)<br>[Try Reddit!](https://www.graphqlhub.com/playground/reddit)<br>[Try Twitter!](https://www.graphqlhub.com/playground/twitter)<br>[Try Giphy!](https://www.graphqlhub.com/playground/giphy) | [Docs](https://www.graphqlhub.com/)<br>[Repo](https://github.com/clayallsopp/graphqlhub)
| MusicBrainz |  Open music encyclopedia that collects music metadata | [Try it!](https://graphbrainz.herokuapp.com/?query=query%20NirvanaAlbumSingles%20%7B%0A%20%20lookup%20%7B%0A%20%20%20%20artist(mbid%3A%20%225b11f4ce-a62d-471e-81fc-a69a8278c7da%22)%20%7B%0A%20%20%20%20%20%20name%0A%20%20%20%20%20%20releaseGroups(type%3A%20ALBUM)%20%7B%0A%20%20%20%20%20%20%20%20edges%20%7B%0A%20%20%20%20%20%20%20%20%20%20node%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20title%0A%20%20%20%20%20%20%20%20%20%20%20%20firstReleaseDate%0A%20%20%20%20%20%20%20%20%20%20%20%20relationships%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20releaseGroups(type%3A%20%22single%20from%22)%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20edges%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20node%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20target%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20...%20on%20ReleaseGroup%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20title%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20firstReleaseDate%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A&operationName=NirvanaAlbumSingles) | [Repo](https://github.com/exogen/graphbrainz)
| NYC Restaurant Grades |  NYC Restaurant Inspection Results data (letter ratings for restaurants) | [Try it!](https://nyc-restaurant-grades.com/graphql) | [Docs](https://github.com/bswinnerton/nyc-restaurant-grades)
| PokeAPI | Pokémon Data API | [Try it!](https://pokeapi-graphiql.herokuapp.com/) | [Repo](https://github.com/patrickshaughnessy/PokeAPI-GraphQL)
| Spotify | Spotify gives you instant access to millions of songs - from old favorites to the latest hits. | [Try it!](https://spotify-api-graphql-console.herokuapp.com/) | [Repo](https://github.com/thefrenchhouse/spotify-graphql)<br>[Examples](https://github.com/thefrenchhouse/spotify-graphql-examples)
| SWAPI | Star Wars API | [Try it!](https://graphql.org/swapi-graphql/) | [Repo](https://github.com/graphql/swapi-graphql)
| League of legends | Riot unofficial api that allow us to get summoner, matches and match info | |[Repo](https://github.com/jsparanoguy/riot-graphql-api)

## Demonstration-only APIs

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| GraphQL Pokémon | Get information of a Pokémon with GraphQL or [Demo App](https://react-relay-pokemon.now.sh/#/)! | [Try it!](https://graphql-pokemon.now.sh/?query=%7B%0A%20%20pokemon(name%3A%20%22Pikachu%22)%20%7B%0A%20%20%20%20id%0A%20%20%20%20number%0A%20%20%20%20name%0A%20%20%20%20attacks%20%7B%0A%20%20%20%20%20%20special%20%7B%0A%20%20%20%20%20%20%20%20name%0A%20%20%20%20%20%20%20%20type%0A%20%20%20%20%20%20%20%20damage%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%20%20evolutions%20%7B%0A%20%20%20%20%20%20id%0A%20%20%20%20%20%20number%0A%20%20%20%20%20%20name%0A%20%20%20%20%20%20weight%20%7B%0A%20%20%20%20%20%20%20%20minimum%0A%20%20%20%20%20%20%20%20maximum%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20attacks%20%7B%0A%20%20%20%20%20%20%20%20fast%20%7B%0A%20%20%20%20%20%20%20%20%20%20name%0A%20%20%20%20%20%20%20%20%20%20type%0A%20%20%20%20%20%20%20%20%20%20damage%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D) | [Repo](https://github.com/lucasbento/graphql-pokemon)<br>[ClientRepo](https://github.com/lucasbento/react-relay-pokemon)
| MongoDB Northwind demo | [Demo App](https://nodkz.github.io/relay-northwind/) build on top of [graphql-compose](https://github.com/nodkz/graphql-compose) and [mongoose](https://github.com/Automattic/mongoose) | [Try it!](https://graphql-compose.herokuapp.com/northwind/)<br>[Try Relay version!](https://nodkz.github.io/relay-northwind/) | [Docs](https://github.com/nodkz/graphql-compose)<br>[ServerRepo](https://github.com/nodkz/graphql-compose-examples)<br>[ClientRepo](https://github.com/nodkz/relay-northwind-app)
| MongoDB TODO-List | TODO List using GraphQL and MongoDb | [Try it!](https://todo-mongo-graphql-server.herokuapp.com/) | [Docs](https://www.compose.com/articles/using-graphql-with-mongodb/)<br>[Repo](https://github.com/igorlima/todo-mongo-graphql-server)
| Spotify GraphQL Server | This demonstrates how to build a GraphQL server which fetches data from an external API (Spotify) | [Try it!](https://spotify-graphql-server.herokuapp.com/)<br> [Repo](https://github.com/lowsky/spotify-graphql-server)
| Three.js demo | Declare a Three.js program with GraphQL | [Try it!](https://jwerle.github.io/three.graphql/) | [Repo](https://github.com/jwerle/three.graphql)
| UFC GraphQL Server | Public UFC API turned into a GraphQL server. It's hosted by [now.sh](https://now.sh/) then, sometimes, it gets freeze. | [Try it!](https://graphql-ufc-api.now.sh/) | [Repo](https://github.com/jgcmarins/graphql-ufc-api)
