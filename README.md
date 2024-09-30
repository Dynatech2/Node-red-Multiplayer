# Node-red-Multiplayer
### Step 1: Open Node-RED Settings File
  - Access your server using PuTTY (or directly, if you have access).
  -Navigate to the Node-RED settings directory:
  ```
  cd ~/.node-red
  ```
  - Open the settings.js file in a text editor like nano
  ```
  nano settings.js
  ```
  - Then scroll until find
            },

        multiplayer: {
            /** To enable the Multiplayer feature, set this value to true */
            enabled: false
        },
    },
  - Change to true
            },

        multiplayer: {
            /** To enable the Multiplayer feature, set this value to true */
            enabled: true
        },
    },
