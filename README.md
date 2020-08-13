# moco-cli
**Mo**ney **Co**nverter on the CLI

## Features
<ul>
    <li>Quick and Simple</li>  
    <li>Standalone (only <em>bash</em> and <em>bc</em>)</li>  
    <li>Supports 166 currencies</li>  
</ul>

## Installation
Clone repository  
    ```
    git clone https://github.com/Besnn/moco-cli
    ```  




When you type `ls && ls moco-cli` you should have something like this:  
![ls && ls moco-cli](/assets/ls.png)


Open you `.bashrc` now: `nano ~/.bashrc`  


Add `export PATH=<absolute_directory_of_script>:$PATH` (no angle brackets)

You can get the absolute path with `realpath <directory>/moco-cli`  
If that doesn't work try `echo $(pwd)` while inside `moco-cli`.

Finally, type `source ~/.bashrc`.  


## Usage
![usage0](/assets/usage0.gif)  
Syntax is: `moco <amount> <from_currency> <to_currency> [<to_currency>]`  
You can set an alias for _moco_ by adding `alias <alias>="moco"`
The script can accommodate a maximum of one extra to-currency as that is the limit of the free API version.  

If you encounter any problems, make sure to get [your own API key](https://free.currencyconverterapi.com/)   
and put it in the `API_KEY` variable in the beginning of the script.

## To Do/Add
<ul>
    <li>Prettier printing</li>
</ul>
