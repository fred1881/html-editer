# html-editer
<!doctype html>
<html>
<head>
<style>
      body {
  background-color: lightblue;
}
      iframe{
      position: bottom;     
        width: 1000px;
        height: 500px;
        line-height: 40px;
        background-color: #ffffff;
      }
h1 {
  color: red;
  text-align: center;
      }
textarea {
position: top;
  border : solid 1px rgba(0,0,0,.32);
  background: transparent;
  font-family: verdana;
  color: black;
  width: 1000px;
  height: 500px;
  }
</style>
</head>
<body>
<h1>html editer</h1>
<iframe id=f></iframe><textarea placeholder="enter code here" oninput="f.srcdoc=value" cols="80" rows="16">
</textarea>
</body>
</html>
demo
