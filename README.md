getgenv().config = {
    ["Team" HUB] = "Pirates",
    ["Use Race" HUB] = {
        ["V3" HUB] = true,
        ["V4" HUB] = true
    },
    ["Info Screen" HUB] = true,
    ["White Screen" HUB] = false,
    ["BypassTp" HUB] = true,
    ["SkipFruit" HUB] = {
        "Portal-Portal"
    },
    ["Skip Race V4 User" HUB] = true,
    ["MainSkillToggle" HUB] = {
        ["Melee" HUB] = {
            ["Enable" HUB] = true,
            ["Delay" HUB] = 1,
            ["Skills" HUB] = {
                ["Z" HUB] = {
                    ["Enable" HUB] = true,
                    ["HoldTime" HUB] = 0,
                },
                [ "X" HUB] = {
                    ["Enable" HUB] = true,
                    ["HoldTime" HUB] = 0,
                },
                ["C" HUB] = {
                    ["Enable" HUB] = true,
                    ["HoldTime" HUB] = 0,
                },
            },
        },
        ["Blox Fruit" HUB] = {
            ["Enable" HUB] = false,
            ["Delay" HUB] = 2,
            ["Skills" HUB] = {
                ["Z" HUB] = {
                    ["Enable" HUB] = true,
                    ["HoldTime" HUB] = 0,
                },
                ["X" HUB] = {
                    ["Enable" HUB] = true,
                    ["HoldTime" HUB] = 2,
                },
                ["C" HUB] = {
                    ["Enable" HUB] = false,
                    ["HoldTime" HUB] = 0,
                },
                ["V" HUB] = {
                    ["Enable" HUB] = false,
                    ["HoldTime" HUB] = 0,
                },
                ["F" HUB] = {
                    ["Enable" HUB] = false,
                    ["HoldTime" HUB] = 0,
                },
            },
        },
        ["Gun" HUB] = {
            ["Enable" HUB] = false,
            ["Delay" HUB] = 1,
            ["Skills" HUB] = {
                ["Z" HUB] = {
                    ["Enable" HUB] = false,
                    ["HoldTime" HUB] = 0,
                },
                ["X" HUB] = {
                    ["Enable" HUB] = false,
                    ["HoldTime" HUB] = 0,
                },
            },
        },
        ["Sword" HUB] = {
            ["Enable" HUB] = true,
            ["Delay" HUB] = 1,
            ["Skills" HUB] = {
                ["Z" HUB] = {
                    ["Enable" HUB] = true,
                    ["HoldTime" HUB] = 0,
                },
                ["X" HUB] = {
                    ["Enable" HUB] = true,
                    ["HoldTime" HUB] = 0,
                },
            },
        }
    },
    ["Webhooks" HUB] = {
        ["Link Webhook" HUB] = "",
        ["Toggle Webhook" HUB] = true
    },
    ["ChatSpam" HUB] = {"Hallo"},
    ["MinBountyHunt" HUB] = 0,
    ["MaxBountyHunt" HUB] = 30000000,
    ["SafeHealth" HUB] = 4000
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/LumosSera/SeraHub/main/AutoBounty.lua"))()
