# spottyshare
(a.k.a Project "Does everyone like Taylor Swift or just us")


This project has two goals:

1) Make use of Spotify API data to figure out, roughly speaking, how much overlap countries have in their top 50 user charts over time. This is motivated by the year I spent traveling around Asia, where I would download the Spotify top 50 for each country I arrived in and would find overlap / dissimilarities interesting.
2) Dust off my development skills as I slowly re-enter the workforce.

I don't know exactly what this will end up looking like. It'll probably some kind of relatively simple web service with a TON of bits and bobs attached to it (e.g. local development + testing via Docker and some local data store, fiddling with goreleaser + golangci, maybe CircleCI or Github Actions + ArgoCD, dorking around with some AWS stuff and maybe even Terraform to go with it. I know I wanna explore gRPC, and get back into OpenAPI integrations with Golang, trying out some web service frameworks in the process too. The core code will probably be pretty simple, honestly.

Some Spotify-related links:
* https://github.com/spotify/web-api/issues/33
* https://developer.spotify.com/dashboard/c93488432ca044f58c482094ce2eac98/settings (my Spotify app)
* https://developer.spotify.com/documentation/web-api/tutorials/getting-started
* https://developer.spotify.com/documentation/web-api/reference/get-a-categories-playlists (entry point for finding top 50 playlist IDs)
	* Charts Category ID: 0JQ5DAudkNjCgYMM0TZXDw
* https://github.com/zmb3/spotify (Golang library)
* https://github.com/envoy49/go-spotify-cli (Golang CLI, probably won't use)

