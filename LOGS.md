# Day 1

- Project -> Project Settings
  - Display -> Window -> ViewPort Width: 1280, ViewPort Height: 720
  - Display -> Window -> Stretch -> Mode: canvas_items, Aspect: keep
- Add input actions events
  - Project -> Project Settings -> Input Map
    - add actions: move left, move right, jump
    - key binding: move left-D, move right-A, jump-W
- Add Directories in FileSystem Dock
  - scenes, actors, levels, ui, scripts, art, data
- Preapared Git Version Control for Project
  - ```git init```
  - ```git remote add origin https://github.com/hydracsnova13/Revive-GoDot-Game.git```
  - ```git pull origin main --allow-unrelated-histories```
  - ```git checkout -b <branch name>```
  - ```git add .```
  - ```git commit -m "<commit message>"```
  - ```git push -u origin <branch name>```

# Day 2

- Added Prod and Dev setup for the project, added files:
  - scenes -> app, dev, shared
  - levels -> blockouts, prod
- Created Main scene in prod(app): scenes -> app -> main_prod.tscn
- Set main_prod.tscn as Main Scene for game
  - Project -> Project Settings -> Application -> Run; set it to "res://scenes/app/main_prod.tscn"
- Setup Dev environment:
  - Save dev_lab.tscn in "res://scenes/dev/dev_lab.tscn"
  - Created directories: cameraMarkers, spawnPoints, testObjects, UI, world

