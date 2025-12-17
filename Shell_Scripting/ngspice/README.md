**Shell Script to run ngspice file**

#!/bin/bash
echo "Enter the name of the ngspice file with extension : "
read fileName
ngspice -b $fileName
