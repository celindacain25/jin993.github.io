---
layout: default
---
[back](./scriptedblizzMain){: .btn.btn-default}

# Get Started with SC2 API Template

[Blizzard SC2 API Github link](https://github.com/Blizzard/s2client-proto){: target="_blank"}

To start with the basic template of a SC2 bot, I explain the tutorial.cc file of SC2 API.

In main
	Coordinator coordinator;
    coordinator.LoadSettings(argc, argv);
Coordinator coordinate clients. LoadSetting function patch the input options of a client, and configure the client with that options.  
	Bot bot;
    coordinator.SetParticipants({
        CreateParticipant(Race::Terran, &bot),
        CreateComputer(Race::Zerg)
    });
This code 