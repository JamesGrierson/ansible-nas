###

-  Create a playbook to capture and log docker container versions each time the anisble nas playbook is run


- Create a home assistant test env
    - Call the role twice with vars - done
    - Edit the role to use the vars
        - Work out what to set "homeassistant_data_directory" to
    - Add a homeassistant_test_enabled var in the inventory - done
    - Add auto user setup for home assistant. ChatGPT output for this is here - https://chatgpt.com/c/68584a21-4020-800b-9f95-fe2fbdb2adfe