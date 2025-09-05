# Multiplayer-Chase-Sockets
A multiplayer survival game server where 3 players navigate a 16×16 grid to escape a ghost. Each player joins with a name, symbol, and MAC ID. The ghost chases players, doubling speed when someone is caught. Survival times decide the leaderboard after 60s or when all are caught.

🚀 Features

Multiplayer support (3 players)

Player lobby with name, MAC address & in-game symbol

16×16 grid with real-time movement

Ghost with adaptive speed (chases nearest player)

Timer & leaderboard based on survival time

🛠️ Requirements

Python 3.x

Standard libraries only (socket, threading, time, uuid, os, re)
