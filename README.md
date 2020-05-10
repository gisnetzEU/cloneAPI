# Readme
## How to run the server

1. posts and static file server
    ``` shell
    npx json-server posts.json --static .
    ``` 

 2. Create a file named clone.json with this content:
    ``` json
    {
        "clone": [
            
        ]
    }
    ``` 
  
3. clone server
    ``` shell
    npx json-server clone.json --port 5005
    ``` 

  
4. execute localApi.js
    ``` shell
    node localApi.js
    ``` 
