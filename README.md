# scripts4fgo
Scripts that extract data from the json(s) provided by https://api.atlasacademy.io/
## Dependencies:
recode (remove accents from names)
<br/>
wget (downloading files)
<br/>
jq (processing json file)
## Optional dependencies:
dash (change #!/usr/bin/dash to #!/bin/sh if not present)
<br/>
bash (used for looping)
<br/>
rg (supposedly faster grep)
<br/>
frawk (supposedly faster awk)
## Change #!/usr/bin/dash/ to #!/bin/sh
> cd "$( whereis scripts4fgo | cut -d' ' -f2 )" && find . -type f -exec sed -i 's|#!/usr/bin/dash|#!/bin/sh|g' {};
