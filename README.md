# newbound_mcp3008
A collection of useful Newbound Metabot controls for measuring and logging analog singnals with the mcp3008 on a Raspberry Pi and Pi-compatible computers.

# Dependencies
This project requires an up-to-date working installation of the Newbound software
https://github.com/mraiser/newbound

# Installation
1. Move the data/mcp3008 and runtime/mcp3008 folders into your Newbound installation's data and runtime folders, respectively
2. Launch the Newbound software
3. Publish the "mcp3008" control in the "mcp3008" library using the Metabot app
4. Restart the Newbound software

*Instead of moving the data/mcp3008 and runtime/mcp3008 folders you can create symbolic links to them, leaving your git project folder intact for easy updating*
