# Players
```dataview
table proposed_by as Player_1, points as Points
where proposed_by = "player_1"
from #active or #inactive
sort file.name asc
```

```dataview
table proposed_by as Player_2, points as Points
where proposed_by = "player_2"
from #active or #inactive
sort file.name asc
```

```dataview
table proposed_by as Player_3, points as Points
where proposed_by = "player_3"
from #active or #inactive
sort file.name asc
```