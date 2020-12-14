# Netra | Android App | TRF Level 1 Workshop [![Build Status](https://travis-ci.org/The-Robotics-Forum/netra.svg?branch=develop)](https://travis-ci.org/The-Robotics-Forum/netra) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Netra is the Android Application that [TRF](https://vitpunerobotics.com/) uses for Level 1 Workshop.

The motive of the application is to control Bot in the most possible ways and make it semi-autonomous in some specific circumstances. In semi-autonomous mode, the mobile device itself is embedded on Bot, and the application commands the bot to take certain decisions based on the situation.

# Features

Please check out the in-development features of the app. by enabling the Developer mode from the settings menu.

|   **Image**       |   **Feature**          | **Description**                               | **Current Status**         |
|-------------------|------------------------|-----------------------------|--------------------|
| <img src = "" width="200"/>  |  Face Follower  | In this feature, the mobile device is embedded on the bot and the device tracks the user’s face to follow him/her according to movements. Commands are sent to bot via Bluetooth using standard [conventions]().      | Enchancement Phase |
| <img src = "" width="200"/>    |  Manual Control  | Joystick with predefined button left, right, forward, backward and circular joystick along with  terminal to send diverse commands.   | In Progress |
| <img src = "" width="200"/>    |  [OCR](https://en.wikipedia.org/wiki/Optical_character_recognition) + Distance  | The mobile device is embedded on the bot and it continuously scan for the character on detecting character L(left), R(right), F(forward), B(backward) it sends a command to the bot using standard convention. BUT the command should be sent only if the character is at a particular distance. | In Progress |
| <img src = "" width="200"/>    |  Voice Control | On a specific keyword let say "TRF" the voice command should get activated and depending upon inputs from the user command should be sent to bot via Bluetooth.| Development Phase |

    
    
# Screenshots


# Contribution Guidelines

This is an Open Source Project. All contributions are welcome. Please follow the steps below for contributing.

- To file an issue or a feature request, use the [GitHub Issue Tracker](https://github.com/The-Robotics-Forum/workshop-android/issues) and describe briefly what you are expecting.
- To raise a Pull Request:
    1. Fork the repository
    2. Create a branch. Preferable name it the same as the issue you want to solve. Eg name `issue-712`.
    3. Commit your changes to the new branch you created in your forked repository.
    4. Raise a Pull Request to the `develop` branch of this repository.

**Make sure to follow these guidelines**
1. Run `gradlew check` or `./gradlew check` locally before pushing any commits or creating a Pull Request.
    - If `gradlew check` is failing locally, your Pull Request will also fail and won't be able to merge.
2. If you are taking up any issue from the issue tracker, please name your commits in this form. This will automatically link the Issue to your commit.
    - `Fix #{Issue Number}: Whatever change you did`
    - Example commit message: `Fix #9: Added a new function`
3. Give "easy to understand" names to the branches you create in your forked repository
4. While creating a Pull Request, explain in brief what changes you made.

# License
    

