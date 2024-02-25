# Install git-lfs (large file system) to upload/download oversize files from/to github. 
>sudo apt-get install zip
>sudo apt-get install unzip
>sudo apt-get install mbt
>sudo apt-get install git
>sudo apt-get install git-lfs 
>git clone https://github.com/Amit-A2Z/hana-xs-cli.git
>unzip Your-git-app-path/hana-xs-cli/xs.ZIP .

# Export and add path to xs-cli in .bashrc or any such-related file
export xs="$HOME/bin/xs"
alias xs="$HOME/bin/xs"
alias xsd="xs login -a https://mindset-india:30230/ -u AMITA2Z -p ********************* -o ORGNAME -s SPACE --skip-ssl-validation"

# Source the .bashrc to get the cli working
>source ~/.bashrc
>xs -v
