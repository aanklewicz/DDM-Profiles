# DDM-Profiles

In macOS 15.4, Apple went and added the functionality. You will need:

1) A token from ABM
Microsoft has created a bash script which can be used to generate that token. https://github.com/microsoft/shell-intune-samples/tree/master/macOS/Tools/getBetaTokens It's pretty intuitive, but please note that it must be run through bash and not zsh (I was running it through Code Runner and had it set to always use zsh and it failed.)

2) Access to ABM

3) Access to an MDM that will accept a json DDM configuration file, such as FleetDM.