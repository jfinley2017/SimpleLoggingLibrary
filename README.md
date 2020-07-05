# SimpleLoggingLibrary
A collection of native logging macros and blueprint utilities surrounding logging in UE4. 

- Provides access to SimpleLog variants, which include information about which netmode the log is being ran on as well as the signature of the calling function.
- Blueprint logging, with Netmode and callsite information as well as LogCategory and verbosity support via ```USimpleLoggingBlueprintLibrary::SimpleBlueprintLog```.
- Macro wrappers for otherwise verbose debugging/logging utilities.

<p align=center>
  <img src = "https://media.discordapp.net/attachments/381955162387906572/729433491699138670/unknown.png"/>
  <img src = "https://cdn.discordapp.com/attachments/381955162387906572/729436619517722744/unknown.png"/>
</p>

# 1.) Enabling the plugin
- Clone this repo.
- Move ```SimpleLoggingToolsPlugin/``` into ```{PathToYourGame}/{YourGame}/Plugins/```.
- Open your project enable the plugin in Edit->Plugins. The plugin should appear under "Project->Other".


#  2.) Documentation.
All logging macros can be found in ```Source/Public/SimpleLoggingLibrary.h``` with documentation. Blueprint utilities can be found in ```Source/SimpleLoggingBlueprintLibrary.h``` with documentation.
