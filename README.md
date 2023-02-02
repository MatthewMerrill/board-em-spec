
## Games

### POST /games
```json5
{ type: "" }
```

### GET /games/:game_id([a-z0-9-]+)
```json5
{ id: "", moves: [], board: [[],[],[]], render: "" } 
```

### GET /games/:game_id([a-z0-9-]+)/validMoves
Body returns JSON list of move strings

### GET /games/:game_id([a-z0-9-]+)/moves/:move_id(\\d+)
Body returns move in plain text

### POST /games/:game_id([a-z0-9-]+)/moves/:move_id(\\d+)
Body must be move in plain text
