# Getting Started

## :material-download-circle: 1 - Installation

1. Download the repository as a zip file, or clone it using git to your local machine.
2. Navigate to your maya scripts directory. On windows, this is usually located at `C:\Users\USERNAME\Documents\maya\VERSION\scripts`.
3. Place the "WombatAutoRig-main" folder into the maya script folder
4. Rename the "WombatAutoRig-main" folder to "wombatAutoRig"




## :material-rocket-launch: 2 - Starting the tool

1. Open maya and run the following python code in the script editor to run the tool:

```python
from wombatAutoRig import wombatAutoRig
wombatAutoRig.run()
```

!!! note
    I suggest you to create a shelf button to run the tool easily. To do so, you can simply drag and drop the code above into the shelf.
