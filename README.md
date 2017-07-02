# Swift Snippets

![video](https://raw.githubusercontent.com/imaizume/swift-snippets/master/assets/swift-snippets.gif)

A handy snippets for swift programming on XCode.

## List of Snippets
```
mark                                 MARK annotation
markline                             MARK annotation with line
markmethod                           MARK annotation for method declaration
markproperties                       MARK annotation for property declaration
vclifecycle                          View Controller lifecycle method template
vcmethod                             View Controller method template
vctemplate                           View Controller template
```

To generate snippet list, run: `python generate_list.py`.
The script is cloned that of [burczyk/XcodeSwiftSnippets](https://github.com/burczyk/XcodeSwiftSnippets).

## Install
```
git clone git@github.com:imaizume/swift-snippets.git \
  && rsync -a swift-snippets/*.codesnippet ~/Library/Developer/Xcode/UserData/CodeSnippets/
```

