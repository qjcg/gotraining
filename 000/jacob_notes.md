Hey John!

Okay so I'm assuming you know the materials are at
github.com/ardanlabs/gotraining/topics/web

For tech setup I just have them go get github.com/ardanlabs/gotraining and use
whatever editor they like. I usually recommend VS Code with the Go plugin.

For a 1 day class I try to cover these sections:

    basics 
        cover the types in the readme except http.HandlerFunc.
        cover all 6 exercises. The last one is where it gets interesting and you have a "wow factor"
        have them do the exercise
    testing
        do the exercise
    posts 
        Skip the file handler part and the exercise. Just showing them some cool stuff here
    muxers
        I only show gorilla/pat. IMO it has the easiest API for beginners to use
    templates
        skip the exercise here too
    serializers
        just show the JSON parts. 
        Can skip the custom json marshaler if you're short on time
    middleware
        I don't focus on the Negroni one too much. Just show the basics, alice, and using conext
    apis
        just show the CRUD part
        If you think you'll have time these exercises are great and honestly depending on how things are going you could end the day here if you need. 

These are cool if you have time

    auth 
        show basic auth and Goth. 
        Skip JWT.
        Have them do the exercise to get a working GitHub application authenticated
    consuming
        This exercise is a lot of fun. Just show them how to make requests, add headers, and send them with a client then they can get into the exercise.
    tls
        The acme one doesn't really have anything for them to do but you can show the shell output in the comments to see how easy it is to use Lets Encrypt if you're exposed to the internet and behind a domain name.
    shutdown
        This one is a lot of fun. Get the server running in one terminal and get the "hey" program running in another. Start the server, start sending traffic, then ctrl-c the server and see it drain connections.


I don't cover these sections

    rest
    sessions_cookies
    sockets

Hit me up with questions
