SussyBot stores certain data about the games that occur.

In-between games and persistent per-server, SussyBot stores:
**List of Data persistent Between Games:**
- Config `config`
- Profile `profile` `user`
- Tasks `tasks` `id`

And of course there is data stored during games, about the roles, tasks everybody has completed, etc. there is a lot and for this you should consult the actual code (don't worry it should be pretty readable!)

**Here are some important default values:**
Configs are assigned how they are represented in each respective file.
Profiles are based off the discord profile first until they are chosen to change.
Tasks are initially empty and must be mass added by the server.