# Tutorial_GenericHostConsoleApp\n<br>
My steps to setup a Microsoft generic host console application.<br>

Project Setup

1) New project<br>
![image](https://github.com/XanNava/Tutorial_GenericHostConsoleApp/assets/19845462/dedf2185-a36e-45b4-abca-054966081250)<br>

2) C# Console App<br>
![image](https://github.com/XanNava/Tutorial_GenericHostConsoleApp/assets/19845462/5865a142-55b9-4ffe-90b1-0a292b7f194d)<br>

3) Fill out project info<br>
![image](https://github.com/XanNava/Tutorial_GenericHostConsoleApp/assets/19845462/86596413-abb4-4657-abd7-026ce260c2db)<br>
Place solution and project...: (Ussually don't do Place solution and project in the same directory as it makes it cluttered, and more complicated to work with multiple connected projects)<br>

4) Choose language version, and enable Do not use top-level statements, and Enable native AOT publish.<br>
![image](https://github.com/XanNava/Tutorial_GenericHostConsoleApp/assets/19845462/60acd74e-4a3f-4893-a3ea-60b8dc0ffaa9)<br>
Framework: (For the framework)<br>
Do not use top-level statements: (The top-level I don't like, and you are gonna use top levels statements everywhere else in your app, best used for quick tests or very basic learning)<br>
Enable native AOT publish: (AOT may have unintended consiquences on functionality, but majority of the time is fine)<br>

Generic Host Setup<br>

1) go to nuget packages<br>
![image](https://github.com/XanNava/Tutorial_GenericHostConsoleApp/assets/19845462/4f4e6155-9b40-4347-9539-5c40427e391c)<br>

2) Search for Microsoft.Extensions.Hosting<br> and install desired version
![image](https://github.com/XanNava/Tutorial_GenericHostConsoleApp/assets/19845462/d4582b55-0fbd-479d-bde6-64c4bf9a9173)<br>
Projects: (Select wich project to add the package)<br>
Version: (Go with what makes sense, I am using .net 8 so as of this tut I am using the 8.0.0 release and not the preview, though this can be updated later).<br>
