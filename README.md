# ChatApp

For this project, I used Unity 3D for the frontend development, and C#/.NET Core for the Backend development, and MongoDB for the Database development, gRPC for Protocol to establish connection between frontend and backend. The Unity 3D version is 2020.2.1f1.

The Frontend's source files of scenes, scripts and prefabs are under the Chat/Assets folder.

The source files for backend with databse is in the server/ChatsApi folder.

The protobuf files is in the server/ChatsApi/Protos folder.

The instruction on deploying the MongoDB database is in Database_deployment_script.txt file.

To run the application, first go to the server/ChatsApi folder, open it with Visual Studio Code, and run "dotnet build", then "dotnet run". This will start up the server.

Then, to run the Unity frontend, go to Chat/Build folder, and run the Chat.exe file.

To open the Unity project, use Unity 2020.2.1f1 to open the /Chat folder.
