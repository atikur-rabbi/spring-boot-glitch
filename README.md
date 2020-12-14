This is the **"Building a RESTful Web Service"** example from <https://spring.io/guides/gs/rest-service/>

Cloned from the repo at <https://github.com/spring-guides/gs-rest-service> and then changed as follows:
* Removed gradle stuff (Glitch doesn't include gradle and it used too much disk space to download it)
* Modified GreetingController.java so the JSON is also served from "/" in addition to "/greeting" (so something shows up when Glitch previews the app)
* Added package.json that launches the app via Maven
* Added this README