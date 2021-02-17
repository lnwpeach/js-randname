<!DOCTYPE html>
<html lang="th" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <style media="screen">
    body {
      background-image: url('bg01.png');
      background-size: cover;
    }
    #btn {
       width: 80px;
       height: 40px;
       font-size: 12pt;
       background-color: #4A4A4A;
       border-color: : #4A4A4A;
       font-weight: bold;
    }
    #luckyname {
       font-size: 30pt;
       color: white;
    }
    #footer {
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      color: #5E5E5E;
      text-align: center;
      margin-bottom: 10px;
    }
  </style>
  <body>
    <div id='a' style="color: white;" hidden></div>
    <script type="text/javascript">
      function readTextFile(file)
      {
          var names;
          var rawFile = new XMLHttpRequest();
          rawFile.open("GET", file, false);
          rawFile.onreadystatechange = function ()
          {
              if(rawFile.readyState === 4)
              {
                  if(rawFile.status === 200 || rawFile.status == 0)
                  {
                      var allText = rawFile.responseText;
                      names = allText.split("\n");
                      names.pop();
                  }
              }
          }
          rawFile.send(null);
          return names;
      }

      function rand(min, max) {
          return Math.floor(Math.random() * (max - min)) + min;
      }

      var names = readTextFile("namelist.txt");
      var lucknum = new Array();
      function randomName() {
        document.getElementById('btn').style.visibility = 'hidden';
        var count = 0;
        var round = 50;
        var ms = 50;
        var step = 1;
        var n;
        var counter = setTimeout(timer, ms); //1000 will  run it every 1 second
        function timer()
        {
          var luckyname;
          count = count + 1;
          if(lucknum.length == names.length - 1) count = round;
          if (count <= round) {
            //Do code for showing the number of seconds here
            n = rand(0, names.length);
            while(lucknum.includes(n)) {
              n = rand(0, names.length);
            }
            luckyname = names[n].trim();
            /* if(luckyname == 'Peach' && count == round && lucknum.length != names.length - 1) {
              while(luckyname == 'Peach') {
                n = names.indexOf('Peach')
                luckyname = names[n].trim();
              }
            } */
            document.getElementById("luckyname").innerHTML = luckyname; // watch for spelling
            if(lucknum.length == names.length - 1 && count == round) {
              lucknum = new Array();
              count = round + 2;
              document.getElementById('btn').style.visibility = 'visible';
            }
            ms = ms + step;
            if(count % 6 == 0) step += 1;
            counter = setTimeout(timer, ms);
          } else if(count == round + 1) {
            lucknum.push(n);
            document.getElementById('btn').style.visibility = 'visible';
          }
        }
      }
      </script>

      <table align='center' width='1000px' height='80px' border='0' style="margin-top:25%">
        <tr align='center'>
          <td width='85%'><div id='luckyname'></div></td>
          <td><button id='btn' onclick="randomName();">Random</button></td>
        </tr>
      </table>
      <div id='footer'>Developed by lnwpeach ITI 22</div>
  </body>
</html>
