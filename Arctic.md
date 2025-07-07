# Arctic

Custom functions that can be found in Arctic Roblox internal executor -->> https://discord.gg/xDB7phZtxk

---

## Arctic.info

```lua
function Arctic.info(message: string): ()
```

Simply prints blue in the Roblox console, as it's done internally.

### Parameters

 * `message` - The message that will be printed.


---

## Arctic.messagebox

```lua
function Arctic.messagebox(text: string, title: string, flags: number): number
```

Creates a messagebox with the specified text, title, and flags. Doesn't yields because Roblox detects it.

Documentation regarding the flags and return codes can be found here.

### Parameters

 * `text` - The text to display in the messagebox.
 * `title` - The title of the messagebox.
 * `flags` - The flags to use.

---

## Arctic.pausepackets

```lua
function Arctic.pausepackets(): ()
```

Pauses the detection packets used by Roblox.

### Parameters

This function takes no parameters.

## Arctic.resumepackets

```lua
function Arctic.resumepackets(): ()
```

Resumes the detection packets used by Roblox.

### Parameters

This function takes no parameters.

### More functions will be added within Arctic updates
