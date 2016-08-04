**DevBox setup**

# Tools and dependencies
 - No tools are required (Note: Tools download takes time )
 - Only vagrant boxes need to be downloaded for now
    
# How to run ?
1. Clone this repo 
2. Create a config file **Ex: `example.json`**
3. Add the access_token, git_name, list of organizations and organization config file name to `example.json`
4. Make sure that your organization has a **devBoxSetup** repository and a json file named as the `organization config file name` in `example.json` in it which contains list of 
    - services 
    - assets
5. Make the `setup` file executable
    - **`chmod +x ./setup`**
3. Run the setup file through the following command 
    - **`./setup.sh example.json`**