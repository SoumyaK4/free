---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

<div id="seki-board"
  class="seki-board-static"
  
  data-game="(;
    FF[4]
    CA[UTF-8]
    AP[Seki v1.3.17]
    GM[1]
    XL[2]
    XR[0]
    XT[3]
    XB[0]
    KM[0]
    HA[0]
    TM[0]
    ST[2]
    SZ[9]
    PB[Black]
    PW[White]
    ;AB[fh][gg][fg][hf][ge][dg]AW[gh][hg][hi][ih]
  )"
  data-config="{
    'showCoordinates': true,
    'showStarPoints': true
  }"
></div>
<br>
<div id="seki-board"
  class="seki-board-dynamic fixed-size square"
  data-config="{
    'showCoordinates': false,
    'showLastMoveNumber': true,
    'board': {
      'size': 9
    }
  }"
></div>

See [Seki Player](https://github.com/adamreisnz/seki) for more info.