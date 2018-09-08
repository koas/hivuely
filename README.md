# hivuely
Convert .vue files to JS / CSS. Requires PHP to be installed in your computer.

Download the hiveuly file and mark it as executable.

Usage: hivuely componentFolder jsOutputFile cssOutputFile

The script will look in the _componentFolder_ folder for .vue files. The `style` blocks will be added to the _cssOutputFile_, the `template` block will be inserted inside the template member of the Vue.component parameter and then the `script` block will be added to the _jsOutputFile_.

**IMPORTANT**: the template member of the Vue.component parameter MUST be `` (an empty string with backticks).
