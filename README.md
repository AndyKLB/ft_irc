# ft_irc

Summary
-------
`ft_irc` is likely an IRC-related project (server or bot). It typically demonstrates network programming, sockets, and protocol parsing in C.

Features
--------
- Basic IRC server or bot functionality (channels, messages, user handling)
- Socket programming and connection handling

Requirements
------------
- Linux
- `gcc` / `make`

Build
-----
From the project root:

```
make
```

Build details:

```
CXX = c++
CXXFLAGS = -Wall -Wextra -Werror -std=c++98 -g3
```

Object files are built into `objs/`. To build both server and bot:

```
make
```

To run the server or bot:

```
./ircserv          # server binary
./wall-e           # bot binary
```

Usage
-----
- Start the server/bot according to the project's `main` entry. Example:

```
./irc_server [port]
```

Project Layout
--------------
- `Bot/` — bot-related code
- `srcs/` — server source code
- `header/` — header files

Notes
-----
- Check configuration files or source for default ports and commands. Network projects often require running with appropriate firewall rules.

Author / Attribution
--------------------
Authors: wzeraig and ankammer (Walid Zeraig and Andy Kammerer)

License
-------
Unlicensed.
