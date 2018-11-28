# What is it?
GifBot is a Reddit bot that will return a list of highlight gifs as a reply to any comment on the NFL subreddit that starts with !gifbot.

# How does it work?
Arguments are your friend. GifBot will search for your highlights using the arguments you submit to it. Here's a list of the different arguments that you can use:

- **Players:** `!gifbot odell` will return all highlights involving Odell Beckham.
The bot will also recognize full names: `!gifbot barry sanders` will return just Barry Sanders highlights, and not highlights of any other Sanders players.
- **Opponents:** `!gifbot broncos` will return all highlights where the opponent was the Denver Broncos.
- **Season:** `!gifbot 2007` will return all highlights in the 2007 season.
- **Titles:** Each highlight has been tagged and titled, so you can still find "famous" plays by name. For instance, I think you all know what the result would be if you typed `!gifbot butt fumble`

# Usage Examples
Arguments can be chained together. Here are some examples:

- `!gifbot moss 2007 dolphins` will return all highlights of Randy Moss in the 2007 season against the Dolphins.
- `!gifbot brady brown falcons 2001` will return all highlights that include both Tom Brady AND Troy Brown in the 2001 season against the Falcons.
- `!gifbot rams chiefs` will return highlights where both of those teams are involved, which usually means games where they've played each other.

# Current Limitations
The obvious limitation is content. Despite what people say, I'm only human. This means I haven't actually gone back and created highlight gifs for every play of every game. We in the Patriots subreddit have been lucky enough to have our beloved /u/timnog creating highlight gifs for us over the past few years, and I've been working on helping out with creating historical Patriots gifs. So right now the bot is going to start out as pretty Patriot-highlight heavy, at least for older stuff.

However, I have actually gone through the nfl subreddit and converted as many posts tagged with the "Highlight" flair into gfycat videos and added them to the site, and this will continue. I've set up a listener to convert and add any future Highlight posts to the bot's database. I'll still be manually tagging them, but the list will be growing. So at the beginning, most of the highlights will be from this season onwards.

I've also posted in each team's subreddit asking for the best plays of every team, and I've started adding those into the system as well. 

# Call for Help
I'm looking for anyone with troves of their own highlights. Does your team subreddit have their own version of our /u/timnog? Do you want to start helping out by creating your own highlight gifs? Send me a PM and we'll talk. 

# Have a Suggestion?
Are we missing a key highlight? Is there something you want to see that isn't there? Did you find a bug? Send a direct message to /u/nflgifbot.
