# Vscode React Typescript snippets
A collection of user snippets for Vscode for scaffolding Redux-connected React components and actions. I've created and used them for a long time for my own use and though it might be helpful to share with the community.

## Usage

In an empty TSX file, type any of the following snippets to scaffold:


`cccrw`: Create a React.js class component with the filename that is `connect`ed to Redux with empty `mapStateToProps` and `mapDispatchToProps` functions. References a CSS module file in the same directory with the same name of the file and sets its style. (the shortcut stands for "Create Class Component React Web")

`cccrn`: Create a React Native class component with the filename that is `connect`ed to Redux with empty `mapStateToProps` and `mapDispatchToProps` functions. Has a default container view and its style set. (the shortcut stands for "Create Class Component React Native")

`ss`: Create a stylesheet for React Native with an empty `container` key. (the shortcut stands for "StyleSheet")

`fc`: Create a React Native functional component with the filename. Has a default container view and its style set. (the shortcut stands for "Functional Component")


In an empty TS file, type any of the following snippets to scaffold:

`cac`: Create standard set of three action constants with specified action name ending with PENDING, SUCCESS, and FAILURE. (the shortcut stands for "Create Action Constants")
