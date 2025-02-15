[![Go Reference](https://pkg.go.dev/badge/github.com/m9d2/termbox-go.svg)](https://pkg.go.dev/github.com/m9d2/termbox-go)
![Build](https://github.com/m9d2/termbox-go/actions/workflows/test-ubuntu.yml/badge.svg)

## IMPORTANT

This library is somewhat not maintained anymore. But I'm glad that it did what I wanted the most. It moved people away from "ncurses" mindset and these days we see both re-implementations of termbox API in various languages and even possibly better libs with similar API design. If you're looking for a Go lib that provides terminal-based user interface facilities, I've heard that [gdamore/tcell](https://github.com/gdamore/tcell) is good (never used it myself). Also for more complicated interfaces and/or computer games I recommend you to consider using HTML-based UI. Having said that, termbox still somewhat works. In fact I'm writing this line of text right now in godit (which is a text editor written using termbox-go). So, be aware. Good luck and have a nice day.

## Termbox
Termbox is a library that provides a minimalistic API which allows the programmer to write text-based user interfaces. The library is crossplatform and has both terminal-based implementations on \*nix operating systems and a winapi console based implementation for windows operating systems. The basic idea is an abstraction of the greatest common subset of features available on all major terminals and other terminal-like APIs in a minimalistic fashion. Small API means it is easy to implement, test, maintain and learn it, that's what makes the termbox a distinct library in its area.

### Installation
Install and update this go package with `go get -u github.com/m9d2/termbox-go`

### Examples
For examples of what can be done take a look at various examples in the `_demos` directory. You can try them with go run: `go run _demos/keyboard.go`

There are also some interesting projects using termbox-go:
 - [godit](https://github.com/nsf/godit) is an emacsish lightweight text editor written using termbox.
 - [gotetris](https://github.com/jjinux/gotetris) is an implementation of Tetris.
 - [sokoban-go](https://github.com/rn2dy/sokoban-go) is an implementation of sokoban game.
 - [hecate](https://github.com/evanmiller/hecate) is a hex editor designed by Satan.
 - [httopd](https://github.com/verdverm/httopd) is top for httpd logs.
 - [mop](https://github.com/mop-tracker/mop) is stock market tracker for hackers.
 - [termui](https://github.com/gizak/termui) is a terminal dashboard.
 - [termloop](https://github.com/JoelOtter/termloop) is a terminal game engine.
 - [xterm-color-chart](https://github.com/kutuluk/xterm-color-chart) is a XTerm 256 color chart.
 - [gocui](https://github.com/jroimartin/gocui) is a minimalist Go library aimed at creating console user interfaces.
 - [dry](https://github.com/moncho/dry) is an interactive cli to manage Docker containers.
 - [pxl](https://github.com/ichinaski/pxl) displays images in the terminal.
 - [snake-game](https://github.com/DyegoCosta/snake-game) is an implementation of the Snake game.
 - [gone](https://github.com/guillaumebreton/gone) is a CLI pomodoro® timer.
 - [Spoof.go](https://github.com/sabey/spoofgo) controllable movement spoofing from the cli.
 - [rat](https://github.com/ericfreese/rat) lets you compose shell commands to build terminal applications.
 - [httplab](https://github.com/gchaincl/httplab) An interactive web server.
 - [wot](https://github.com/kyu-suke/wot) Wait time during command is completed.
 - [2048-go](https://github.com/1984weed/2048-go) is 2048 in Go.
 - [jv](https://github.com/maxzender/jv) helps you view JSON on the command-line.
 - [pinger](https://github.com/hirose31/pinger) helps you to monitor numerous hosts using ICMP ECHO_REQUEST.
 - [vixl44](https://github.com/sebashwa/vixl44) lets you create pixel art inside your terminal using vim movements.
 - [zterm](https://github.com/varunrau/zterm) is a typing game inspired by http://zty.pe/.
 - [gotypist](https://github.com/pb-/gotypist) is a fun touch-typing tutor following Steve Yegge's method.
 - [cointop](https://github.com/miguelmota/cointop) is an interactive terminal based UI application for tracking cryptocurrencies.
 - [pexpo](https://github.com/nnao45/pexpo) is a terminal sending ping tool written in Go.
 - [jid](https://github.com/simeji/jid) is an interactive JSON drill down tool using filtering queries like jq.
 - [nonograminGo](https://github.com/N0RM4L15T/nonograminGo) is a nonogram (aka. picross) in Go.
 - [tower-of-go](https://github.com/kjirou/tower-of-go) is a tiny maze game that runs on the terminal.
