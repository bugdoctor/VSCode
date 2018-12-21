# VSCode
VSCode configure

```
{
    "gitlens.advanced.messages": {
        "suppressCommitHasNoPreviousCommitWarning": false,
        "suppressCommitNotFoundWarning": false,
        "suppressFileNotUnderSourceControlWarning": false,
        "suppressGitVersionWarning": false,
        "suppressLineUncommittedWarning": false,
        "suppressNoRepositoryWarning": false,
        "suppressResultsExplorerNotice": false,
        "suppressUpdateNotice": false,
        "suppressWelcomeNotice": true
    },
    "gitlens.codeLens.authors.enabled": false,
    "gitlens.codeLens.recentChange.enabled": false,
    "gitlens.codeLens.enabled": false,
    "gitlens.blame.line.enabled": false,
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontSize": 13,
    "files.autoSave": "afterDelay",
    "terminal.external.osxExec": "iTerm.app",
    //go
    "go.autocompleteUnimportedPackages": true,
    "workbench.colorTheme": "Dracula Soft",
    "gitlens.currentLine.enabled": false,
    "gitlens.hovers.currentLine.enabled": false,
    "gitlens.keymap": "alternate",
    //python
    // "python.linting.pep8Enabled": true,
}
```

# enables colorin the terminal bash shell export
export CLICOLOR=1
# sets up thecolor scheme for list export
export LSCOLORS=gxfxcxdxbxegedabagacad
# sets up theprompt color (currently a green similar to linux terminal)
export PS1='\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;36m\]\w\[\033[00m\]\$ '
# enables colorfor iTerm
export TERM=xterm-color

alias grep='grep --color'
alias egrep='egrep --color'
alias fgrep='fgrep --color'
#alias npm='tnpm'
alias cnpm="npm --registry=https://registry.npm.taobao.org \
--cache=$HOME/.npm/.cache/cnpm \
--disturl=https://npm.taobao.org/dist \
--userconfig=$HOME/.cnpmrc"

# proxy
#export http_proxy="127.0.0.1:50183"
#export https_proxy="127.0.0.1:50183"

# Go
export GOPATH=/Users/zhaoxinyu/go
export GOROOT=/usr/local/opt/go/libexec
export GOBIN=$GOPATH/bin
export PATH=$GOROOT/bin:$GOBIN:$PATH

# Java
export JAVA_HOME="/Library/Java/JavaVirtualMachines/jdk1.8.0_161.jdk/Contents/Home"
export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
export PATH=$JAVA_HOME/bin:$PATH

# Maven
export M2_HOME=/usr/local/opt/maven/libexec
export PATH=$M2_HOME/bin:$PATH

# Python2
export PATH="/usr/local/opt/python2/libexec/bin:$PATH"

# Node
export PATH="/usr/local/opt/node@8/bin:$PATH"

# Python3
#export PATH="/usr/local/opt/python/libexec/bin:$PATH"

# Groovy
export GROOVY_HOME=/usr/local/opt/groovy/libexec
