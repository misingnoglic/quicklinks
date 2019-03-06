# Quicklinks
Quicklinks is a short command-line script that allows you to quickly switch to a a pre-configured link.

On OsX, this would be the same thing as doing the following:

`ql google` -> `open https://google.com`

## Usage and Installation
1. Run the following script:
    ```bash
    pip install quicklinks
    ```

1. Create a `.quicklinks` file in your user root:
    ```bash
    touch ~/.quicklinks
    ```
    
1. Populate the `.quicklinks` file like the following:
    ```bash
    {your-link-key}:{your-link-value}
    ```
    
    **Example:**
    ```bash
    google:https://google.com
    wiki:https://wikipedia.com
    ```
    
1. Run the program
    ```bash
    ql wiki
    ```
    
    And you will be redirected to your browser of choice, opening your link
    
## Contributing
Fork this code and open a PR, all code is welcome as long as it follows the 

## Credits
Quicklinks was inspired by my use of `alias ql="open"` as well as the very cool [GoLinks](http://golinks.io/), check them out if you want the same thing as quicklinks but in your browser itself!