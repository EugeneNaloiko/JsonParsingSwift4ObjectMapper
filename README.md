# JsonParsingSwift4ObjectMapper
The starter project for educational task - to parse the given JSON to structures and objects and perform some changes on it.

The purpose of this test task:
1. Verify that the skills to update pods
2. Use Alamofire for Get Requests. https://raw.githubusercontent.com/15Dkatz/jokes-api-ruby/master/data/jokes.json
3. Use ObjectMapper to parse to Objects, AlamofireObjectMapper to parst to Structures for JSON Parsing
4. Perform modification manipulations with Structures and Objects, feel the difference between value types and reference types

Task description:
1. Get your local copy of this starter project
2. Install Pods
3. Start the project, verify it's working
4. Prepare the JokeObject, JokeStruct to parse the JSON Objects. Joke types parse as an Enum - as JokeTypeEnum. 
5. Prepare the GetJokesRequestHandler - to get the Jokes JSON using alamofire, and parse it. Use Generics to initiate the GetJokesRequestHandler, so that it can return array of both JokeObject, JokeStruct.
6. In the ViewController viewDidLoad function:

        /*
         1. Request the array of JokeObject
         2. Assign the first object of the array to the variable
         3. Modify the punchline property
         4. Get the first object of the array once more. Print out the punchline property. It got changed. (Objects are reference types)
         */
        
        /*
         1. Request the array of Joke Struct
         2. Assign the first struct of the array to the variable
         3. Modify the punchline property
         4. Get the first struct of the array once more. Print out the punchline property. It didn't change. (Structs are value types)
         */



You'll have 15 minutes to complete this task. While performing the task - make the screen recording. After passing the test successfully - present the screen recording video to your mentor.

To receive the BUDU.ua certificate for JsonParsingSwift4ObjectMapper Test Project - you'll need to pass the test, staying in the same room with your mentor, and he confirms the successful test passing.

Who passed the task:
1. Eugene https://www.youtube.com/watch?v=xGZIRNmD9QQ&feature=youtu.be
