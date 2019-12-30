
# Sublime text snippets
This sublime text package holds code snippets for common programming practices and statements in React.js. Adding this package will let you autocomplete statements and save time.

## Adding this package to your sublime text

1. Clone the repository
2. Add the `SublimeSnips` folder to your local sublime package folder
  * For linux users :  `~/.config/sublime-text-{2|3}/Packages/`
  * For macOS users : `/Users/{user}/Library/Application Support/Sublime Text {2|3}/Packages`
3. Open up sublime and use it !

## Using the snippets
The snippets have been divided into separate namespaces, one for react **r** and one for JSX tags **jsx**. You can use them to generate both react code as well as JSX tags. To access the snippet, type out the shortened syntax and hit `Tab` to load the snippet. After the snippet loads, you can give any inputs and delete the default inputs set. Some default inputs may just indicate what it expects and have to be deleted. 

Many snippets take multiple inputs, although it is not required for you to give them all, you certainly can. If you give one input and want to move to the next, press `Tab`	. Similarly, to go back to the previous input, press `Shift + Tab`. At any time if you don't want to give more inputs you can press `Esc` to end the cycle. If you call a snippet and try to call another snippet before going through all of the previous snippets inputs, if wont load until you pass through all the inputs, so if you intend to do so, use the `Esc` to escape. You can also click elsewhere.

To get a preview of the snippets, you just have to type *r* or *jsx* and it pops up a menu for you to select.

## Snippet shorthands
#### React based
1. **ReactDOM.render** - r.domr
2. **Class Component** - r.cc
3. **Pure Class Component** - r.pcc
4. **Bind To Class** - r.btc
5. **Component Did Catch** - r.cdc
6. **Component Did Mount** - r.cdm
7. **Component Did Update** - r.cdup
8. **Component Will Unmount** - r.cwu
9. **Create Element** - r.ce
10. **Destructure Props** - r.dstp
11. **Destructure State** - r.dsts
12. **Event Handler** - r.eh
13. **Export** - r.exp
14. **Export Default** - r.expd
15. **Force Update** - r.fup
16. **Fragment** - r.frg
17. **Functional Component** - r.fc
18. **Functional Component Arrow** - r.fca
19. **Import** - r.imp
20. **Inline If** - r.ii
21. **Inline If Else** - r.iie
22. **Constant JSX** - r.jsxc
23. **Let JSX** - r.jsxl
24. **Prop Types** - r.pt
25. **Set State** - r.ss
26. **Set State Arrow** - r.ssa
27. **Should Component Update** - r.scup

#### JSX based
1. **Any JSX Component** - jsx.comp
2. **JSX Form** - jsx.form
3. **JSX Header** - jsx.hdr
4. **JSX Input** - jsx.inp
5. **Any JSX Tag** - jsx.tag

*More To Come!*
