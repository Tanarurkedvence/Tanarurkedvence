## Marcell Urbán

I build automation that runs on its own. Recording in, finished video out, no human click.

I'm a junior developer from Hungary, out of technical college in 2026 (software developer and tester). I'm looking for a junior role in Python, .NET or web, remote or hybrid.

### Start here

**[BabszemAPI](https://github.com/Tanarurkedvence/BabszemAPI)** is an ASP.NET Core Web API over SQL Server with Entity Framework Core. Eight endpoints, each documented with the status codes it actually returns, including the 409 you get when you try to delete a product that still has orders. Swagger is wired up and there's a `.http` file so you can fire the requests without a client.

**[BetMatchBonus](https://github.com/Tanarurkedvence/BetMatchBonus)** is a sports betting web app in PHP and MySQL, built by three of us. The bet slip's combination checker is mine: 274 lines, 28 rules about which two betting markets can't go on the same slip. "Both teams to score" means at least two goals. "Under 1.5 goals" means at most one. They can't both come in, so they can't sit on one slip together. The odds API hands you the markets, but it won't tell you which two contradict each other.

**[LinqPeldak](https://github.com/Tanarurkedvence/LinqPeldak)** is 44 LINQ examples over 325 real records: filtering, grouping, set operations, both syntaxes, and a plain foreach version of the same query so you can see what LINQ is saving you.

**[jegyzetek](https://tanarurkedvence.github.io/jegyzetek/)** is my own notes on C#, LINQ and Web APIs, with a search over them. I wrote it for myself and it is still the first place I look.

### Why there is so much C# here

In October 2026 I worked through a long set of practice exercises and pushed each one as its own repository. Console apps, desktop GUIs, two Web APIs. They're small on purpose, and there are a lot of them, so the language bar on this account reads mostly C#. They're mine and they run, but the four above are the ones I'd actually show you.

### What you cannot see here, and why

My largest project is a video pipeline in Python. 14,510 lines across 34 files. It watches a folder, picks the strongest segment of a long recording, cuts it vertical, adds word level captions and music, and uploads it to YouTube on a schedule. Four steps in one chain, no human click.

It's a business tool, so the source stays private. I'm glad to walk through it on a call or give read access on request. Just email me.

One decision I'll defend in an interview: downloaded material that is not mine gets held back, and the bot asks before it goes anywhere. An automatic uploader plus a downloader is a re-publishing machine, and I didn't want to build one.

### Stack

C#, .NET, ASP.NET Core, Entity Framework Core, SQL Server, Python, JavaScript, PHP, MySQL, Kotlin, Docker, Git, REST APIs, ffmpeg, OAuth

### Contact

urban.marcell44@gmail.com
[linkedin.com/in/urbanmarcell](https://www.linkedin.com/in/urbanmarcell)
