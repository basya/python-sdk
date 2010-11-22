Facebook Python SDK
====

[Our other repo](https://bitbucket.org/basya/django-oauth/wiki/Home)
[Our tumblar](http://basyab.tumblr.com/)

This client library is designed to support the
[Facebook Graph API](http://developers.facebook.com/docs/api) and the official
[Facebook JavaScript SDK](http://github.com/facebook/connect-js), which is
the canonical way to implement Facebook authentication. You can read more
about the Graph API at [http://developers.facebook.com/docs/api](http://developers.facebook.com/docs/api).

Basic usage:

    graph = facebook.GraphAPI(oauth_access_token)
    profile = graph.get_object("me")
    friends = graph.get_connections("me", "friends")
    graph.put_object("me", "feed", message="I am writing on my wall!")

If you are using the module within a web application with the
[JavaScript SDK](http://github.com/facebook/connect-js), you can also use the
module to use Facebook for login, parsing the cookie set by the JavaScript SDK
for logged in users. For example, in Google AppEngine, you could get the
profile of the logged in user with:

    user = facebook.get_user_from_cookie(self.request.cookies, key, secret)
    if user:
        graph = facebook.GraphAPI(user["oauth_access_token"])
        profile = graph.get_object("me")
        friends = graph.get_connections("me", "friends")

You can see a full AppEngine example application in examples/appengine.

[Pornstar XXX Tube - NakedNovices.COM](http://www.nikednovices.com/xxx/) | [2 hot sluts cum swapping](http://www.nikednovices.com/xxx/2-hot-sluts-cum-swapping.html) | [Alexandra nice and serenity](http://www.nikednovices.com/xxx/alexandra-nice-and-serenity.html) | [Amateur hardcore brunette](http://www.nikednovices.com/xxx/amateur-hardcore-brunette.html) | [Amateurs play with each other](http://www.nikednovices.com/xxx/amateurs-play-with-each-other.html) | [Anal with jenna haze](http://www.nikednovices.com/xxx/anal-with-jenna-haze.html) | [Anal with milf on stair case](http://www.nikednovices.com/xxx/anal-with-milf-on-stair-case.html) | [Ariana jollee eating ass 1/2](http://www.nikednovices.com/xxx/ariana-jollee-eating-ass-1/2.html) | [Ariana jollee garage gangbang](http://www.nikednovices.com/xxx/ariana-jollee-garage-gangbang.html) | [Ass jewel](http://www.nikednovices.com/xxx/ass-jewel.html) | [Avy scott](http://www.nikednovices.com/xxx/avy-scott.html) | [Beer can size dick in the ass](http://www.nikednovices.com/xxx/beer-can-size-dick-in-the-ass.html) | [Big fuck](http://www.nikednovices.com/xxx/big-fuck.html) | [Biker dreams](http://www.nikednovices.com/xxx/biker-dreams.html) | [Black girls doggystyled](http://www.nikednovices.com/xxx/black-girls-doggystyled.html) | [Blond domina blond slave](http://www.nikednovices.com/xxx/blond-domina-blond-slave.html) | [Blondes and black](http://www.nikednovices.com/xxx/blondes-and-black.html) | [Blonde swallows pov](http://www.nikednovices.com/xxx/blonde-swallows-pov.html) | [Blow job cum swallow](http://www.nikednovices.com/xxx/blow-job-cum-swallow.html) | [Brianna love sofa fuck](http://www.nikednovices.com/xxx/brianna-love-sofa-fuck.html) | [Busty michelle b anal](http://www.nikednovices.com/xxx/busty-michelle-b-anal.html) | [Candy is topless](http://www.nikednovices.com/xxx/candy-is-topless.html) | [Caroline big phat ass](http://www.nikednovices.com/xxx/caroline-big-phat-ass.html) | [Cassie young my dirty angels](http://www.nikednovices.com/xxx/cassie-young-my-dirty-angels.html) | [Courtney cummz music video](http://www.nikednovices.com/xxx/courtney-cummz-music-video.html) | [Cum craving sluts](http://www.nikednovices.com/xxx/cum-craving-sluts.html) | [Cute girl sofa fuck](http://www.nikednovices.com/xxx/cute-girl-sofa-fuck.html) | [Cytherea squirts all over you](http://www.nikednovices.com/xxx/cytherea-squirts-all-over-you.html) | [Emma cummings interracial](http://www.nikednovices.com/xxx/emma-cummings-interracial.html) | [Gia paloma](http://www.nikednovices.com/xxx/gia-paloma.html) | [Harley blowjob 2](http://www.nikednovices.com/xxx/harley-blowjob-2.html) | [Hillary scott ass to mouth](http://www.nikednovices.com/xxx/hillary-scott-ass-to-mouth.html) | [Horny nymph eve laurence](http://www.nikednovices.com/xxx/horny-nymph-eve-laurence.html) | [Hot latina sativa rose](http://www.nikednovices.com/xxx/hot-latina-sativa-rose.html) | [Hot mom june summers](http://www.nikednovices.com/xxx/hot-mom-june-summers.html) | [Internal affairs](http://www.nikednovices.com/xxx/internal-affairs.html) | [Lauren at big tit bangers](http://www.nikednovices.com/xxx/lauren-at-big-tit-bangers.html) | [Lexi cruz blowjob](http://www.nikednovices.com/xxx/lexi-cruz-blowjob.html) | [Milf lips penetrated](http://www.nikednovices.com/xxx/milf-lips-penetrated.html) | [Milf with big juggs](http://www.nikednovices.com/xxx/milf-with-big-juggs.html) | [Natural ashley long](http://www.nikednovices.com/xxx/natural-ashley-long.html) | [Petite teen huge cock fuck](http://www.nikednovices.com/xxx/petite-teen-huge-cock-fuck.html) | [Phoenix marie ass gape](http://www.nikednovices.com/xxx/phoenix-marie-ass-gape.html) | [Sandra romain and jada fire](http://www.nikednovices.com/xxx/sandra-romain-and-jada-fire.html) | [Sarah and patricia having fun](http://www.nikednovices.com/xxx/sarah-and-patricia-having-fun.html) | [Sarah feel it](http://www.nikednovices.com/xxx/sarah-feel-it.html) | [Sex scene iron fisted monk](http://www.nikednovices.com/xxx/sex-scene-iron-fisted-monk.html) | [Simone peach group sex](http://www.nikednovices.com/xxx/simone-peach-group-sex.html) | [Sleeping heather gables](http://www.nikednovices.com/xxx/sleeping-heather-gables.html) | [Suzana alves loves anal sex](http://www.nikednovices.com/xxx/suzana-alves-loves-anal-sex.html) | [Tasty cum shot](http://www.nikednovices.com/xxx/tasty-cum-shot.html) | [Teen huge cock fuck](http://www.nikednovices.com/xxx/teen-huge-cock-fuck.html) | [Teen roxanne hall dominated](http://www.nikednovices.com/xxx/teen-roxanne-hall-dominated.html) | [Teen sensations maya hills](http://www.nikednovices.com/xxx/teen-sensations-maya-hills.html) | [Trina tames the monster](http://www.nikednovices.com/xxx/trina-tames-the-monster.html) | [Trip in london](http://www.nikednovices.com/xxx/trip-in-london.html) | [Velicity von bubble ass](http://www.nikednovices.com/xxx/velicity-von-bubble-ass.html) | [Very hot wild college sex](http://www.nikednovices.com/xxx/very-hot-wild-college-sex.html) | [Victoria at gag on my cock](http://www.nikednovices.com/xxx/victoria-at-gag-on-my-cock.html) | [White and black 2 p4](http://www.nikednovices.com/xxx/white-and-black-2-p4.html) | [Kayla paige](http://www.nikednovices.com/xxx/kayla-paige.html)