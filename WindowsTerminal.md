# Windows Terminal Config wsl, powershell, cmd
## WSL Ubuntu 20.04

```json
// This file was initially generated by Windows Terminal 1.3.2651.0
// It should still be usable in newer versions, but newer versions might have additional
// settings, help text, or changes that you will not see unless you clear this file
// and let us generate a new one for you.

// To view the default settings, hold "alt" while clicking on the "Settings" button.
// For documentation on these settings, see: https://aka.ms/terminal-documentation
{
    "$schema": "https://aka.ms/terminal-profiles-schema",

    "defaultProfile": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",

    // You can add more global application settings here.
    // To learn more about global settings, visit https://aka.ms/terminal-global-settings

    // If enabled, selections are automatically copied to your clipboard.
    "copyOnSelect": false,

    // If enabled, formatted data is also copied to your clipboard
    "copyFormatting": false,

    // A profile specifies a command to execute paired with information about how it should look and feel.
    // Each one of them will appear in the 'New Tab' dropdown,
    //   and can be invoked from the commandline with `wt.exe -p xxx`
    // To learn more about profiles, visit https://aka.ms/terminal-profile-settings
    "profiles":
    {
        "defaults":
        {
            // Put settings here that you want to apply to all profiles.        
        },
        "list":
        [
            {
                // Make changes here to the powershell.exe profile.
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "name": "PowerShell",
                "commandline": "powershell.exe",
                "hidden": false,
                "colorScheme": "Cyberpunk",
                "fontFace": "Cascadia Code PL",
                "fontSize": 12,
                "acrylicOpacity": 0.6,
                "useAcrylic": true,
                //To copy path shift + right click then select copy as path
                "backgroundImage": "G:\\My Photos\\Valorant Wallpapers\\1093220.jpg",
                "backgroundImageOpacity": 0.4,
                "backgroundImageStretchMode": "uniformToFill"
                
            },
            {
                "guid": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",
                "hidden": false,
                "name": "Ubuntu",
                "source": "Windows.Terminal.Wsl",
                "colorScheme": "Cyberpunk",
                "fontFace": "Cascadia Code PL",
                "fontSize": 12,
                "acrylicOpacity": 0.6,
                "useAcrylic": true,
                //To copy path shift + right click then select copy as path
                "backgroundImage": "G:\\My Photos\\Valorant Wallpapers\\1099887.jpg",
                "backgroundImageOpacity": 0.4,
                "backgroundImageStretchMode": "uniformToFill"
            },
            {
                // Make changes here to the cmd.exe profile.
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "name": "Command Prompt",
                "commandline": "cmd.exe",
                "hidden": false,
                "colorScheme": "Cyberpunk",
                "fontFace": "Cascadia Code PL",
                "fontSize": 12,
                "backgroundImage": "G:\\My Photos\\Valorant Wallpapers\\1104273.jpg",
                "backgroundImageOpacity": 0.6,
                "backgroundImageStretchMode": "uniformToFill",
                "acrylicOpacity": 0.6,
                "useAcrylic": true
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
                "source": "Windows.Terminal.Azure",
            }
        ]
    },

    // Add custom color schemes to this array.
    // To learn more about color schemes, visit https://aka.ms/terminal-color-schemes
    "schemes": [
      {"name": "Slate",
        "black": "#222222",
        "red": "#e2a8bf",
        "green": "#81d778",
        "yellow": "#c4c9c0",
        "blue": "#264b49",
        "purple": "#a481d3",
        "cyan": "#15ab9c",
        "white": "#02c5e0",
        "brightBlack": "#ffffff",
        "brightRed": "#ffcdd9",
        "brightGreen": "#beffa8",
        "brightYellow": "#d0ccca",
        "brightBlue": "#7ab0d2",
        "brightPurple": "#c5a7d9",
        "brightCyan": "#8cdfe0",
        "brightWhite": "#e0e0e0",
        "background": "#222222",
        "foreground": "#35b1d2"
      },
      {"name": "Andromeda",
        "black": "#000000",
        "red": "#cd3131",
        "green": "#05bc79",
        "yellow": "#e5e512",
        "blue": "#2472c8",
        "purple": "#bc3fbc",
        "cyan": "#0fa8cd",
        "white": "#e5e5e5",
        "brightBlack": "#666666",
        "brightRed": "#cd3131",
        "brightGreen": "#05bc79",
        "brightYellow": "#e5e512",
        "brightBlue": "#2472c8",
        "brightPurple": "#bc3fbc",
        "brightCyan": "#0fa8cd",
        "brightWhite": "#e5e5e5",
        "background": "#262a33",
        "foreground": "#e5e5e5"
      },
      {"name": "Cyberpunk",
        "black": "#000000",
        "red": "#ff7092",
        "green": "#00fbac",
        "yellow": "#fffa6a",
        "blue": "#00bfff",
        "purple": "#df95ff",
        "cyan": "#86cbfe",
        "white": "#ffffff",
        "brightBlack": "#000000",
        "brightRed": "#ff8aa4",
        "brightGreen": "#21f6bc",
        "brightYellow": "#fff787",
        "brightBlue": "#1bccfd",
        "brightPurple": "#e6aefe",
        "brightCyan": "#99d6fc",
        "brightWhite": "#ffffff",
        "background": "#332a57",
        "foreground": "#e5e5e5"
      },
      { "name": "Cobalt Neon",
        "black": "#142631",
        "red": "#ff2320",
        "green": "#3ba5ff",
        "yellow": "#e9e75c",
        "blue": "#8ff586",
        "purple": "#781aa0",
        "cyan": "#8ff586",
        "white": "#ba46b2",
        "brightBlack": "#fff688",
        "brightRed": "#d4312e",
        "brightGreen": "#8ff586",
        "brightYellow": "#e9f06d",
        "brightBlue": "#3c7dd2",
        "brightPurple": "#8230a7",
        "brightCyan": "#6cbc67",
        "brightWhite": "#8ff586",
        "background": "#142838",
        "foreground": "#8ff586"
      },
      {"name": "Dracula",
        "black": "#000000",
        "red": "#ff5555",
        "green": "#50fa7b",
        "yellow": "#f1fa8c",
        "blue": "#bd93f9",
        "purple": "#ff79c6",
        "cyan": "#8be9fd",
        "white": "#bbbbbb",
        "brightBlack": "#555555",
        "brightRed": "#ff5555",
        "brightGreen": "#50fa7b",
        "brightYellow": "#f1fa8c",
        "brightBlue": "#bd93f9",
        "brightPurple": "#ff79c6",
        "brightCyan": "#8be9fd",
        "brightWhite": "#ffffff",
        "background": "#1e1f29",
        "foreground": "#f8f8f2"
      },
      {"name": "Blue Matrix",
        "black": "#101116",
        "red": "#ff5680",
        "green": "#00ff9c",
        "yellow": "#fffc58",
        "blue": "#00b0ff",
        "purple": "#d57bff",
        "cyan": "#76c1ff",
        "white": "#c7c7c7",
        "brightBlack": "#686868",
        "brightRed": "#ff6e67",
        "brightGreen": "#5ffa68",
        "brightYellow": "#fffc67",
        "brightBlue": "#6871ff",
        "brightPurple": "#d682ec",
        "brightCyan": "#60fdff",
        "brightWhite": "#ffffff",
        "background": "#1d2342",
        "foreground": "#b8ffe1"
      },
      {"name": "WSL",
        "background" : "#002B36",
        "black" : "#002B36",
        "blue" : "#268BD2",
        "brightBlack" : "#657B83",
        "brightBlue" : "#839496",
        "brightCyan" : "#D33682",
        "brightGreen" : "#B58900",
        "brightPurple" : "#EEE8D5",
        "brightRed" : "#CB4B16",
        "brightWhite" : "#FDF6E3",
        "brightYellow" : "#586E75",
        "cyan" : "#2AA198",
        "foreground" : "#93A1A1",
        "green" : "#859900",
        "purple" : "#6C71C4",
        "red" : "#DC322F",
        "white" : "#93A1A1",
        "yellow" : "#B58900"
    }
    ],

    // Add custom actions and keybindings to this array.
    // To unbind a key combination from your defaults.json, set the command to "unbound".
    // To learn more about actions and keybindings, visit https://aka.ms/terminal-keybindings
    "actions":
    [
        // Copy and paste are bound to Ctrl+Shift+C and Ctrl+Shift+V in your defaults.json.
        // These two lines additionally bind them to Ctrl+C and Ctrl+V.
        // To learn more about selection, visit https://aka.ms/terminal-selection
        { "command": {"action": "copy", "singleLine": false }, "keys": "ctrl+c" },
        { "command": "paste", "keys": "ctrl+v" },

        // Press Ctrl+Shift+F to open the search box
        { "command": "find", "keys": "ctrl+shift+f" },

        // Press Alt+Shift+D to open a new pane.
        // - "split": "auto" makes this pane open in the direction that provides the most surface area.
        // - "splitMode": "duplicate" makes the new pane use the focused pane's profile.
        // To learn more about panes, visit https://aka.ms/terminal-panes
        { "command": { "action": "splitPane", "split": "auto", "splitMode": "duplicate" }, "keys": "alt+shift+d" }
    ]
}
```