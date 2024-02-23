Copy the contents of `complex_mods_snippet` using the Karabiner-Elements UI: Complex Modifications > Add your own rule.

You could also try editing `~/.config/karabiner/karabiner.json` directly. Specifically, you would have to edit "profiles" (find specific profile in the list, most likely the one where `"name": "Default profile"`) > "complex_modifications" > "rules" section. This is ultimately where the contents of `complex_mods_snippet` will be copied when using the UI approach. However, you will notice that (1) the snippet comments (i.e. lines starting "// ... " which are not valid JSON) get removed and (2) there is also some formatting applied when the application adds your rules. Given this 'behind the scenes' activity you might want to be careful before editing the file directly as there must be some constraints (and perhaps other non-obvious ones) that you have to respect. 
