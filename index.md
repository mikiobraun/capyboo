What's the most annoying thing about social networks? Elon Musk? Meta pulling the strings? Trump supporters? Too much clickbait? Ads? Irrelevant timelines? 

And you can't really leave because every time you did, you have to bootstrap your followers all over again!

Now what if there weren't just half a dozen social networks, but a whole zoo of social networks? And everyone could experiment with ways to make it more entertaining, more safe, or maybe more childish and more extraneous? What if changing social networks weren't like moving to a different continent, but more like trying out another restaurant and who knows, maybe you like it there!

Have you also ever wondered why you have to do so much manual work? Find followers, mute topics, block people, and so on. There are some dark patterns at work here to make you put work into the network, give you small rewards, and make it harder for you to leave. But why? With all that AI floating around, shouldn't things be much smoother? Why do I have to block people one by one? Why do I even have to see those replies? What if social networks actually felt like they were built in the 2020s and not in the 2000s? 

And what if all that is not tied to a single server but is actually a network of servers so that no one controls it all?

## Welcome to Capyboo

Capyboo is not yet another social network, it is fabric on which to build new social networks. Unlike other networks, there isn't just a single social network, but there are as many as people are willing to set up, and your profile is kept separate from them. The individual social networks have a lot of freedom how to run and how to propagate and surface content for you. They might follow a strict follower model where you see content from people you follow, or a more algorithmic approach, like TikTok where it tries to find content that is relevant for you.

The best thing about this is that Capyboo is extendable so that people can try out their ideas. We've seen so little progress because the social networks that exist today are so big and there is so much inertia.

## How does Capyboo work

The key difference for Capyboo is that it your profile is kept separate from the social networks. Your profile and your relationships stay with you as you move from social network to social network.

The social networks are called "venues" at Capyboo, and they are like separate rooms on Discord, just that they aren't just chat rooms but are their own small (or large!) social network.

Venues can use their own communication fabric to decide how to propagate information. They can decide to be organized more like subs on reddit, chat rooms on discord, or like the big social networks. It is up to the venue owner and their vision of what kind of space they want to create.

Both profiles and venues are highly configurable and can also be extended with their own timeline algorithms, trending topics extractors, or with algorithms that protect you from misuse and trolls.

Maybe all this is a bad idea, but I'm willing to try it out :)

## How is Capyboo different from mastodon, the fediverse, Twitter, or threads?

Capyboo can and will probably use ActivityPub as the main communication between profiles and venues, together with some extensions. This means there will be some interoperability with the fediverse, but as is already the case, it won't be perfect.

Capyboo is different from mastodon in that it does not try to create one big social network space. We believe there is value in being able to be small to try things out.

## Is Capyboo a commercial product

I really don't know. For now this project is run as open source. In a way the very idea of making it easy to switch networks is something that contradicts trying to make money. If this model works out, some venues might become so big or so great that people will be willing to join. Maybe we can host some of that, maybe there'll be licensing, but right now I really don't know.

## Why Go?

Capyboo will be written in Go because it is a small language designed for collaboration, and I hope this will make it easier for people to contribute. Another reason is that I believe because of the nature of the matter, performance will be an issue (although many venues will probably stay small enough that any programming language will work). Some of the extensions will also be done via REST interfaces, as I expect especially for the more advanced stuff, people will want to use Python, for example.

