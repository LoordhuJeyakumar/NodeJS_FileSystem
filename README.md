# NodeJS_FileSystem

## Task Details

1.  Write API endpoint which will create a text file in a particular folder
    - Content of the file should be the current timestamp.
    - The filename should be current date-time.txt
2.  Write API endpoint to retrieve all the text files in that particular folder.

# Links
## [Render Deployed URL 👈](https://nodejs-fs-8vkr.onrender.com/) 
`https://nodejs-fs-8vkr.onrender.com/`

## [Github repository URL 👈](https://github.com/LoordhuJeyakumar/NodeJS_FileSystem) 

`https://github.com/LoordhuJeyakumar/NodeJS_FileSystem`

## [Postman documentation URL 👈](https://documenter.getpostman.com/view/27536086/2s9YsDjEPN)

`https://documenter.getpostman.com/view/27536086/2s9YsDjEPN`


# API Endpoints

 ## <span style="color:#6BDD9A">GET</span>  `api/files`
 ### view all files created in that specific folder 
Sample Output
 ```json
 {
  "all_Files": [
    "Fri Dec 29 2023 - 16_05_11 GMT+0000.txt",
    "Fri Dec 29 2023 - 16_05_17 GMT+0000.txt",
    "Fri Dec 29 2023 - 16_06_51 GMT+0000.txt",
    "Fri Dec 29 2023 - 16_07_53 GMT+0000.txt",
    "Fri Dec 29 2023 - 16_11_47 GMT+0000.txt",
    "Fri Dec 29 2023 - 16_23_12 GMT+0000.txt",
    "Fri Dec 29 2023 - 16_25_04 GMT+0000.txt",
    "Fri Dec 29 2023 - 16_57_21 GMT+0530.txt"
  ]
}
 ```

  ## <span style="color:#FFE460">POST</span>  `api/createFile`
### Create new file in that specific folder
Sample Output
 ```json
 {
  "message": "File created successfully"
}
 ```