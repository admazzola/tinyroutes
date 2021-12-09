## Tinyroutes

Simple express api config loader 

 

### config 

routes.json 

    `

        [
        ["get /ping", "pong"],
        ["get /mint", "mint"]
        ]

    `



### Getting Started 
 
  const expressApp = express();
 
  RouteLoader.loadRoutes(expressApp, apiRoutesConfig, ApiInterface)

  expressApp.listen(PORT);
       