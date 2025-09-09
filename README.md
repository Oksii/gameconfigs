# Game Configs Repository

A comprehensive collection of player config files, managed through Discord bot integration.

## Overview

This repository serves as a centralized hub for sharing and managing player configuration files across multiple games. Players can upload, search, and download configs through an integrated Discord bot.

### Features

- **Search**: Fuzzy search with 80%+ similarity matching
- **User Management**: Personal config storage with automatic naming
- **Config Analysis**: Automatic parsing of key game settings
- **Version Control**: Git-based config versioning and history
- **Discord Integration**: Full bot integration for seamless usage
- **Real-time Updates**: Automatic repository synchronization

## Supported Games

| Game | Folder | Description |
|------|--------|-------------|
| **Return to Castle Wolfenstein** | `rtcw/` | RTCW configs |
| **Enemy Territory** | `et/` | ET: Legacy configs |


## Usage

### Discord Bot Commands

Use these commands in game-specific Discord channels:

#### Basic Commands
```
!cfg                    # Show your own config (or help if none exists)
!cfg help               # Show command help
!cfg list               # List all available configs  
!cfg <name>             # Search for configs by name
!cfg @user              # Find a specific user's config
```

#### Upload Commands
```
!cfg add                # Upload config files (attach to message)
                        # • Single .cfg file → saved as yourname.cfg
                        # • Multiple .cfg files → compressed to yourname.zip
                        # • Upload .zip file → saved as yourname.zip
```
