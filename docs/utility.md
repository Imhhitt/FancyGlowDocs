## Commands and Permissions

| Permission | Command |
|:---|:---:|
| `fancyglow.command.gui`       | Access to `/glow` (access to GUI). |
| `fancyglow.command.disable`   | Access to `/glow disable` to stop the glowing mode without opening the GUI. |
| `fancyglow.command.color`     | Access to `/glow color <color>` to glow without opening the GUI. |
| `fancyglow.admin`             | Access to `/glow reload` to reload the `config.yml` file. |
| `fancyglow.admin`             | Access to `/glow disable <player>` to stop the glowing mode for any player. |
| `fancyglow.rainbow`           | Access to rainbow mode at the GUI. |
| `fancyglow.<color>`           | Access to choose the color of glow that you want at the GUI. Full list [here](#every-individual-color-permission). |
| `fancyglow.all_colors`        | Access to choose any glow color in the GUI. |

#### Every individual color permission:

- `fancyglow.dark_red`
- `fancyglow.red`
- `fancyglow.gold`
- `fancyglow.yellow`
- `fancyglow.dark_green`
- `fancyglow.green`
- `fancyglow.dark_aqua`
- `fancyglow.aqua`
- `fancyglow.dark_blue`
- `fancyglow.blue`
- `fancyglow.dark_purple`
- `fancyglow.light_purple`
- `fancyglow.black`
- `fancyglow.dark_gray`
- `fancyglow.gray`
- `fancyglow.white`
- `fancyglow.rainbow`

## Placeholders

| Placeholder | Usage |
|:---|:---:|
| `%fancyglow_color%`  | Returns the glow color. Useful for any scoreboard management plugin. |
| `%fancyglow_status%` | Shows enabled/disabled status of glow. See `config.yml` to change format of output. |