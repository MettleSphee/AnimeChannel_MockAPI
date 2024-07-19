# AnimeChannel_MockAPI
This is my "Mock API" implementation for the Nintendo Anime Channel catalog, which allows to easily add channels and videos, modularly, to your desired server.

Note: This is in no way an actual API, since the only endpoint is the PHP file. The notation was done as an inside joke towards a project done in my cybersec master's degree

This uses PHP and allows you to add multiple catalog segments from all over the internet, given that they're added properly in the files as seen in the examples. 
Which is why I'm clarifying that this should work properly on an unedited, SSL patched 3DS, with a PHP-enabled and https (can use self-signed certificates) webserver that you're going to host this on.



Multiple entries can be added easily, without having to keep adding the catalog headers and whatnot. 

This can be used alongside this tool: https://github.com/MettleSphee/3DS_EpisodeGenerator_AnimeTemplate


## WARNING! This project *expects* you to:
- know exactly what you're doing;
- to know PHP language and JSON file structure;
- to know how the AnimeChannel works (reference: https://github.com/MettleSphee/3DS_EpisodeGenerator_AnimeTemplate);
