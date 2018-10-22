# Provinces of Spain
An SVG map with all the provinces of Spain, [original file](https://commons.wikimedia.org/wiki/File:Provinces_of_Spain.svg) from Wikimedia Commons.

Changes to the original SVG:
- Removed province colors.
- Added group IDs according to [ISO 3166-2:ES](https://en.wikipedia.org/wiki/ISO_3166-2:ES).
- Grouped labels & province shapes together.
- Cleaned up SVG data.

The resulting SVG fragment for every province has this format:
```
<g id="ES-M">
    <path ... />
    <text ... >
        <tspan>Madrid</tspan>
    </text>
</g>
```
## License
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

Original by Emilio Gómez Fernández & Javi C. S. [GFDL](http://www.gnu.org/copyleft/fdl.html) or [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0), from Wikimedia Commons.

Additional changes by Joost-Wim Boekesteijn.