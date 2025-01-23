# QR-Code-Snake-Game

Submitted to the [SayCheese](https://saycheese.hackclub.com) YSWS(You Ship, We Ship) event organized by [Hackclub](https://hackclub.com/)!

Task: Fit something into a QR code (holds at most 3kb of data)

<img src="/Snake_Game_Display.png">

## Features
- Classic snake game
- Score and Highscore tracking
- Restart button
- Faded tail and glowing border effects
- Uses arrow keys to control

## How to Play

### Scan this QR code to run it in a browser:

<img src="/Snake_Game_QR_Code.png">


### Copy and paste this Data URI directly into your browser:

```
data:text/html;charset=utf-8;base64,PCFET0NUWVBFIGh0bWw+CjxodG1sPgo8aGVhZD4KICA8c3R5bGU+CiAgICBodG1sLGJvZHl7aGVpZ2h0OjEwMCU7bWFyZ2luOjA7YmFja2dyb3VuZDojMDAwO2Rpc3BsYXk6ZmxleDtmbGV4LWRpcmVjdGlvbjpjb2x1bW47YWxpZ24taXRlbXM6Y2VudGVyO2p1c3RpZnktY29udGVudDpjZW50ZXI7Y29sb3I6IzM5RkYxNH0jc2NvcmVze2ZvbnQtc2l6ZToyMHB4O21hcmdpbi1ib3R0b206MjBweH1jYW52YXN7Ym9yZGVyOjJweCBzb2xpZCByZ2JhKDU3LDI1NSwyMCwwLjUpO2JveC1zaGFkb3c6MCAwIDEwcHggcmdiYSg1NywyNTUsMjAsMC41KX1idXR0b257ZGlzcGxheTpub25lO3BhZGRpbmc6MTJweCAyNHB4O2JhY2tncm91bmQ6IzM5RkYxNDtjb2xvcjojMDAwO2JvcmRlcjpub25lO2JvcmRlci1yYWRpdXM6MjVweDtjdXJzb3I6cG9pbnRlcn1idXR0b246aG92ZXJ7YmFja2dyb3VuZDojMmRmZjAwO3RyYW5zZm9ybTp0cmFuc2xhdGVZKC0ycHgpfQogIDwvc3R5bGU+CjwvaGVhZD4KPGJvZHk+CiAgPGRpdiBpZD0ic2NvcmVzIj5TY29yZTogPHNwYW4gaWQ9InNjb3JlIj4wPC9zcGFuPiB8IEhpZ2ggU2NvcmU6IDxzcGFuIGlkPSJoaWdoc2NvcmUiPjA8L3NwYW4+PC9kaXY+CiAgPGNhbnZhcyBpZD0iZyIgd2lkdGg9IjQwMCIgaGVpZ2h0PSI0MDAiPjwvY2FudmFzPgogIDxidXR0b24gaWQ9InJlc3RhcnQiPlJlc3RhcnQ8L2J1dHRvbj4KICA8c2NyaXB0PgogICAgbGV0IGM9ZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoImciKSx4PWMuZ2V0Q29udGV4dCgiMmQiKSxidG49ZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoInJlc3RhcnQiKSxzPTE2LHQ9MCxwbGF5PTEsc2NvcmU9MCxoaWdoU2NvcmU9MCxuLGEscj0obSx2KT0+TWF0aC5mbG9vcihNYXRoLnJhbmRvbSgpKih2LW0pKSttLHVwZHQ9KCk9Pntkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgic2NvcmUiKS50ZXh0Q29udGVudD1zY29yZSxkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgiaGlnaHNjb3JlIikudGV4dENvbnRlbnQ9aGlnaFNjb3JlfSxpbml0PSgpPT57bj17eDoxNjAseToxNjAsZHg6cyxkeTowLGNlbGxzOltdLGxlbjo0fSxhPXt4OnIoMCwyNSkqcyx5OnIoMCwyNSkqc30scGxheT0xLGJ0bi5zdHlsZS5kaXNwbGF5PSJub25lIixzY29yZT0wLHVwZHQoKX0sZHJhdz0oKT0+e2lmKCFwbGF5KXJldHVybiBidG4uc3R5bGUuZGlzcGxheT0iYmxvY2siLHVwZHQoKTtyZXF1ZXN0QW5pbWF0aW9uRnJhbWUoZHJhdyk7aWYoKyt0PDQpcmV0dXJuO3Q9MCx4LmNsZWFyUmVjdCgwLDAsYy53aWR0aCxjLmhlaWdodCksbi54Kz1uLmR4LG4ueSs9bi5keTtpZihuLng8MHx8bi55PDB8fG4ueD49Yy53aWR0aHx8bi55Pj1jLmhlaWdodClyZXR1cm4gcGxheT0wO24uY2VsbHMudW5zaGlmdCh7eDpuLngseTpuLnl9KSxuLmNlbGxzLmxlbmd0aD5uLmxlbiYmbi5jZWxscy5wb3AoKSx4LmZpbGxTdHlsZT0icmVkIix4LmZpbGxSZWN0KGEueCxhLnkscy0xLHMtMSksbi5jZWxscy5mb3JFYWNoKChlLGkpPT57bGV0IG9wYWNpdHk9MS0oaS9uLmNlbGxzLmxlbmd0aCk7eC5maWxsU3R5bGU9YHJnYmEoNTcsMjU1LDIwLCR7b3BhY2l0eX0pYDt4LmZpbGxSZWN0KGUueCxlLnkscy0xLHMtMSksZS54PT09YS54JiZlLnk9PT1hLnkmJihuLmxlbisrLHNjb3JlKyssaGlnaFNjb3JlPU1hdGgubWF4KGhpZ2hTY29yZSxzY29yZSksdXBkdCgpLGEueD1yKDAsMjUpKnMsYS55PXIoMCwyNSkqcyk7Zm9yKGxldCBqPWkrMTtqPG4uY2VsbHMubGVuZ3RoO2orKyllLng9PT1uLmNlbGxzW2pdLngmJmUueT09PW4uY2VsbHNbal0ueSYmKHBsYXk9MCl9KTtjLnN0eWxlLmJveFNoYWRvdz0iMCAwIDE1cHggMTBweCByZ2JhKDU3LDI1NSwyMCwwLjgpIn07YnRuLm9uY2xpY2s9KCk9Pntpbml0KCk7ZHJhdygpfSxkb2N1bWVudC5hZGRFdmVudExpc3RlbmVyKCJrZXlkb3duIixlPT57aWYocGxheSl7aWYoZS5rZXk9PT0iQXJyb3dMZWZ0IiYmbi5keD09PTApbi5keD0tcyxuLmR5PTA7ZWxzZSBpZihlLmtleT09PSJBcnJvd1VwIiYmbi5keT09PTApbi5keT0tcyxuLmR4PTA7ZWxzZSBpZihlLmtleT09PSJBcnJvd1JpZ2h0IiYmbi5keD09PTApbi5keD1zLG4uZHk9MDtlbHNlIGlmKGUua2V5PT09IkFycm93RG93biImJm4uZHk9PT0wKW4uZHk9cyxuLmR4PTB9fSk7aW5pdCgpO2RyYXcoKTsKICA8L3NjcmlwdD4KPC9ib2R5Pgo8L2h0bWw+
```
