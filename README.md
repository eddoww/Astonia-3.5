#Astonia 3.5

Preface

Astonia 3.5 is a small MMO. It has all the stuff a fantasy role-playing game needs (character development with attributes, skills and spells, quests, equipment and monsters), and it can handle maybe 500 players online at once per shard. A realistic limit for the number of shards is around 50. With some investments into the database server hardware more is possible.

Astonia 3.5 is a branch of Astonia 3. It changed (for better or worse is hard to say) many aspects of the gameplay.
It was developed mostly by me for Intent Software. Intent Software was so kind to allow me to release the project to the public.

Hobby License

You may use the software as you see fit, within the bounds of the law etc., provided you:

a) give proper credit (eg. "is based on the Astonia 3.5 engine by Intent Software" somewhere in your game / on your website).

b) generate no more than US$12,000 revenue per year

Commercial License

This license only applies once you are earning more than US$12,000 per year. Once this is the case, please contact me me at daniel (at) brockhaus (dot) org.

You may use the software as you see fit, within the bounds of the law etc., provided you:

a) give proper credit (eg. "is based on the Astonia 3.5 engine by Intent Software" somewhere in your game / on your website).

b) pay Intent Software 10% of the revenues, once per month, 30 days after the end of the month.

Existing Projects

Please email me at daniel (at) brockhaus (dot) org if you would like your site added to this list.

Urd - The original
Astonia Legacy
Astonia Reborn
Requirements

Server

The server needs Linux, MySQL development libraries and 32 bit gcc environment to compile. To run it needs a MySQL server on the same host.

The three files ending in .sql need to be imported into the MySQL server. The MySQL user root needs the password set to the one contained in the file MYSQLPASSWORD.

I haven't had time yet to re-create account and character creation logic. Sorry.

Check the script "start" for an example on how to start the server. A multi-area server will need the chatserver running as well.

The server compiles fine. I have no idea if it will run, no time to test it. Sorry.

Client

You will need the free Borland C++ 5.5 command line tools (available below)

Also requires libpng and zlib, but both are part of the client source code package.

I haven't had time to test if the client will compile (or run). Sorry.

Have fun and good luck.

FAQ

Ishtar character can log into game no matter the situation, but no other char can log, they get the "Server demands exit:.." message?

A god-character needs to release the area for the public via "#shutdown 0".
