# vivado-example-project
This repository serves as a project skeleton for Vivado projects. The project structure is designed to satisfy the following two requirments:
- It is possible to write VHDL code in a team
- Works well with Git (or any other version control tool)

# Motivation
Vivado creates a lot of auto-generated code inside a project, which makes it impossible to host a Vivado project on Github.
Also the auto-generated files cannot be put on the `.gitignore` list because they are essential for the project. This skeleton tries to fix this and shows how a team can work with a Vivado project.
