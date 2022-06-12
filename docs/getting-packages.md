---
sidebar_position: 2
---

# Getting Packages

Getting Packages is easy. Just determine what you want to use (listed [here](https://github.com/izesw/packager/tree/main/index)). Then, write the package name in the **Packages.Index** Module.

Example (DataStore2 & Roact):

```lua
local packages = {
	Shared = {
		Roact = true;
	},
	Server = {
		DataStore2 = true;
	},
}

return packages
```

Then, just press the Start button (2nd Item in Plugins tab) to get the packages from our github!